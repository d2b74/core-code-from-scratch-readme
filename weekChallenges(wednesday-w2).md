- 1.Follow up with the [HTML](https://edpuzzle.com/classes/62df4f9045ccdc4143bd6aad) course you started on Tuesday
- 2.[Char From ASCII Value](https://github.com/corecodeio/devguide-fundamentals-2022-03/tree/main/src/technologies/2022/week02/exercises/e02/desc) exercise
  ```js
  function getChar(c){
    return String.fromCharCode(c);
  }
  ```
- 3.[Binary Addition](https://github.com/corecodeio/devguide-fundamentals-2022-03/tree/main/src/technologies/2022/week02/exercises/e03/desc) exercise
  ```js
  function addBinary(a,b) {
  return (a + b).toString(2);

  }
  ```
- 4.[Student's Final Grade](https://github.com/corecodeio/devguide-fundamentals-2022-03/tree/main/src/technologies/2022/week02/exercises/e04/desc) exercise
  ```js
  function finalGrade (exam, projects) {
  if(exam > 90 || projects >10){
    return 100;
  }else if(exam > 75 && projects >= 5){
    return 90;
  }else if(exam > 50 && projects >= 2){
    return 75;
  }else{
    return 0;
  }
  }
