- 1.Follow up with the [HTML](https://edpuzzle.com/join/vawasaj) course you started on Tuesday
- 2.[Remove All Exclamation Marks From The End Of Sentence](https://github.com/corecodeio/devguide-fundamentals-2022-03/tree/main/src/technologies/2022/week02/exercises/e09/desc) exercise
  ```js
  function remove (string) { 
  let newStr;
     newStr=string.replace(/!+$/g,'');   
  return newStr
  }
  ```
- 3.[Vowel Remover](https://github.com/corecodeio/devguide-fundamentals-2022-03/tree/main/src/technologies/2022/week02/exercises/e10/desc) exercise
  ```js
  function shortcut (string) {
  return string.replace(/[aeiou]/g,"");
  }
  ```
- 4.[Rock Paper Scissors!](https://github.com/corecodeio/devguide-fundamentals-2022-03/tree/main/src/technologies/2022/week02/exercises/e11/desc) exercise
  ```js
  const rps = (p1, p2) => {
  if((p1 == 'rock' && p2 == 'scissors') || (p1== 'scissors' && p2=='paper') || (p1=='paper' && p2=='rock')){
    return "Player 1 won!";
  }else if(p1 == p2){
    return "Draw!";
  }else{
    return "Player 2 won!";
  }
  }
  ```
- 5.[Persistent Bugger](https://github.com/corecodeio/devguide-fundamentals-2022-03/tree/main/src/technologies/2022/week02/exercises/e12/desc) exercise
  ```js
  function persistence(num) {
  let times = 0;
  let digits = [];
  while (num >= 10) {
    digits = num.toString().split('');
    num = 1;
    for (let i = 0; i < digits.length; i++) {
      num *= digits[i];
    }
    times++;
  }
  return times;
  }
