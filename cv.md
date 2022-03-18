
# Firdavs Abdulloev Umarjonovich
Full Stack Web Developer
## ![photo](https://www.codewars.com/users/firdavs-projects/badges/large?logo=true&theme=light)

## Contacts
- Telegram: [@firdavs_abdulloev](https://t.me/firdavs_abdulloev)
- Phone: +992 (92) 92 777 25
- Email: [firdavs.abdulloev.7725@gmail.com](mailto:firdavs.abdulloev.7725@gmail.com)
- LinkedIn: [@firdavs-abdulloev](https://www.linkedin.com/in/firdavs-abdulloev/)

## About myself
Full Stack Web Developer. Skilled in Web Applications, Front-end and Back-end Development with Node.JS & React, Next, Angular. My passion is in solving business problems with IT solutions. I am a responsible, purposeful person and can multitask. I always try to make sure that all tasks are completed on time, while I do not feel discomfort when finding problems, but on the contrary, I like solving problems step by step, I feel comfortable in teamwork. I am a versatile person, and I am interested in many areas including marketing, business, psychology, management and IT technology. I am always ready to learn something new, provided that I'll like it.


## Skills
- Javascript/Typescript
- CSS & SCSS/Tailwind/Bootstrap
- HTML
- React/Next & Redux
- Angular & RxJS
- Git & GitHub/GitLab
- NodeJS & ExpressJS/NestJS
- MySQL/MongoDB/Postgres
- Docker 
- Webpack


## Education
- [Khujand Polytechnic institute of Tajik Technical University](http://old.ttu.tj/en/khujand-politechnical-institute/) (2014-2018) bachelor degree
- [Alif Academy](https://alif.academy/) (2020) Fullstack JS developer course


## Certificates
- [MIPT & Yandex - interface development](https://coursera.org/share/c0f5ff34c53dc9b5dd3a27e9fdd163f4) (Feb 2022)
- [React & Redux course](https://www.sololearn.com/Certificate/1097-19038626/pdf/) (Aug 2021)
- [Javascript course](https://www.sololearn.com/Certificate/1024-19038626/pdf/) (May 2021)
- [Intensive "Quick Start in Web Development"](https://gb.ru/certificates/1164585.en) (Mar 2021)
- [CSS course](https://www.sololearn.com/Certificate/1023-19038626/pdf/) (Sep 2020)
- [HTML course](https://www.sololearn.com/Certificate/1014-19038626/pdf/) (Jul 2020)


## Languages
- English: A2
- Russian: C1
- Tajik: C2 (Native)
- Uzbek: B1


## Code Example
#### [Equal Sides Of An Array (6 kyu)](https://www.codewars.com/kata/5679aa472b8f57fb8c000047)
```
function findEvenIndex(arr){
  let result = -1;
  for (let i = 0; i < arr.length; i++) {
    const left = arr.slice(0, i).reduce((a,b)=> a+b, 0);
    const right = arr.slice(i+1).reduce((a,b)=> a+b, 0);
    if (left === right ) {
      result = i;
      break;
    }
  }
  return result;
}
```
