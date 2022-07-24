- **1_Your date of birth in the matrix? exercise.**
  - Tu equipo acaba de ver la película "Matrix" y te han preguntado cómo se escribiría en binario el número de tu año     de nacimiento. Debes aprender a traducir tu fecha de nacimiento a binario y mostrárselo a tu equipo. (No utilice    una página web o una herramienta para convertir su fecha de nacimiento)
   
    ![](https://github.com/d2b74/core-code-from-scratch-readme/blob/main/binario.png)
  - 1985 
  - 11111000001 
      
  |2^10| 2^9 |2^8|2^7 |2^6 |2^5 |2^4 |2^3 |2^2 |2^1 |2^0 |
   ----|----|----|----|----|----|----|----|----|----|----|
    1  | 1  | 1  | 1  | 1  | 0  | 0  | 0  | 0  | 0  |  1|

- **2_MIPS exercise.**
 
   Con base en la guía y los ejemplos del lenguaje de bajo nivel, cree lo siguiente

  - 1.Cree un programa que agregue dos números proporcionados por el usuario
   ```assembly
   .data
	      number1: .asciiz "\nIngrese el primer numero: "
	      number2: .asciiz "\nIngrese el segundo numero: "
	      result_message: .asciiz "\nEl resultado es: "
  .text
	      main:
              li $v0, 4
              la $a0, number1
              syscall

              li $v0, 5
              syscall

              move $t1, $v0

              li $v0, 4
              la $a0, number2
              syscall

              li $v0, 5
              syscall

              move $t2, $v0

              li $v0, 1
              move $a0, $t0
              syscall

              li $t0, 10
              li $t1, 10

              add $t2, $t0, $t1

              li $v0, 4
              la $a0 result_message
              syscall

              li $v0, 1
              move $a0, $t2
              syscall
     ```
  - 2.Crea un programa que muestre tu nombre
  ```assembly
  .data
        message: .asciiz "\nBarrios Dante!\n"
  .text
        main:
              li $v0, 4
              la $a0, message
              syscall
