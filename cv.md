# [__rsschool-cv__](https://Vladislav-Peryazev77.github.io/rsschool-cv/)

# __Vladislav Peryazev__

__Future Frontend Developer__
***
## Contact information:

* __GitHub__ : [Vladislav-Peryazev77](https://github.com/Vladislav-Peryazev77)
* __Email__ : vladperyazev14@gmail.com
* __Phone__ : 953 788 5679
* __Telegram__ : [@mostrodamus77](https://t.me/mostrodamus77)
* __Codewars__ : [Vladislav-Peryazev77](https://www.codewars.com/users/Vladislav-Peryazev77)

## About me :

For a long time, I didn't know what I wanted to do with my life. I have been involved in sports all my life, I thought that in the future I would become a coach and would transfer my knowledge to people. But at the end of the first year of university, due to health problems, I quit sports. And then, at one of the computer science classes, the teacher offered to go to his __web design lessons__. I thought why not, because there wasn't much that interested me at the time. I came to him every day after classes and pretty quickly went through the material that he could give me. Then I began to immerse myself in this area. I think that my perseverance and hard work will help me become a __Senior Front End Developer__.

## Tech Stack :

* __JavaScript Basics__
* __HTML/CSS__
* __Git, GitHub__
* __Figma__
* __VS code__

## Code example :
Codewars Find the odd int(6kyu)
```
Given an array of integers, find the one that appears an odd number of times.
There will always be only one integer that appears an odd number of times.
Examples
[7] should return 7, because it occurs 1 time (which is odd).
[0] should return 0, because it occurs 1 time (which is odd).
[1,1,2] should return 2, because it occurs 1 time (which is odd).
[0,1,0,1,0] should return 0, because it occurs 3 times (which is odd).
[1,2,2,3,3,3,4,3,3,3,2,2,1] should return 4, because it appears 1 time (which is odd)

function findOdd(A) {

  const obj = {};
  const arr = [];

  A.forEach((item) => {
    if (!obj[item]) {
      obj[item] = 1;
    } else {
      obj[item]++;
    }
  })

  Object.keys(obj).forEach((item) => {
    if ( obj[item] == Object.values(obj).filter(item => item % 2 != 0)) {
      arr.push(item);
    }
  })

  return +(arr[0]);
}
console.log(findOdd([1,2,2,3,3,3,4,3,3,3,2,2,1]));
```
## Languages :
* __Russian :__ Native
* __English :__ Elementary