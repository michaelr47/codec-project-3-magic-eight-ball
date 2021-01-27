# codec-project-3-magic-eight-ball
//The user will be able to input a question, then our program will output a random fortune. js

let userName = 'Mike';
userName ? console.log(`Hello, ${userName}!`) : console.log('Hello!');

let userQuestion = 'Is the earth flat?';
console.log(`The user asked ${userQuestion}`);
let randomNumber = Math.floor(Math.random() * 8);

let eightBall = '';

switch (randomNumber) {
  case 0:
    eightBall = 'It is certain';
    break;
  case 1: 
    eightBall = 'It is decidely so'
    break;
  case 2:
    eightBall = 'Reply hazy try again';
    break;
  case 3: 
    eightBall = 'Cannot predict now';
    break;
  case 4:
    eightBall = 'Do not count on it';
    break;
  case 5: 
    eightBall = 'My resources say no';
    break;
  case 6:
    eightBall = 'Outlook not so good';
    break;
  case 7: 
    eightBall = 'Signs point to yes';
    break;
}
console.log(eightBall);
