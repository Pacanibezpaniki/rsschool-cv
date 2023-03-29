# Vladislav Semenov
## My Contact Info:
  * Phone: +7 917 310 1480
  * E-mail: semenov94va@gmail.com
  * GitHub: Pacanibezpaniki

## About Me
I am 28 years old, I work at a boring job. I want to gain new knowledge and develop as a specialist in a new direction for myself



## Skills
* HTML (basics)
* CSS (basics)
* JavaScript (basics)
* Git/GitHub (in progress)

## Code Examples
```unction rot13(message){
  let alphabetArr = 'abcdefghijklmnopqrstuvwxyzabcdefghijklmnopqrstuvwxyz'.split('')
  let upAlphabetArr = 'abcdefghijklmnopqrstuvwxyzabcdefghijklmnopqrstuvwxyz'.toUpperCase().split('')
  let messageArr = message.split('')
  let newArr = []
  for (let i = 0; i<message.length; i++) {
   let alIndex = alphabetArr.indexOf(messageArr[i])
   let upAlIndex = upAlphabetArr.indexOf(messageArr[i])
    if (alIndex !== -1) {
      newArr.push(alphabetArr[alIndex+13])
    } else if(upAlIndex !== -1){
      newArr.push(upAlphabetArr[upAlIndex+13])

    } else {
      newArr.push(messageArr[i])
    }
  }

  return newArr.join('')```

## Education
* Saratov State University (Saratov, Russia)
  * Faculty of Physics
* [HTML Academy](https://levelup.htmlacademy.ru/)
* https://learn.javascript.ru/

## Languages
* Russian - native speaker.
* English - A2 