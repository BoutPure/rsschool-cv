# JS-developer CV

name:		Anatolii

surname:	Vakulenko

age:		23 y. o.

<br/>

---
### Contacts

telegram:	[link](https://t.me/vseel_Anatolii)

discord: [link](https://discordapp.com/users/212591585915961345/)

<br/>

---
### About me

Hey! I'm Anatolii from Russia. I'm living in Kazan now because of studying in School 21 - programming school based on French School 42 franchize. I want to become a cool programmer!

Year ago I was working as Project Manager in IT company. We were developing and maintaining sites and CRM systems basically for e-commerce and real-estate industries and also for other ones but on a smaller scale.

I'm vegan already for 4 years. Feeling great!<br/>
I like cycling, longboarding, walking and exploring cities.

<br/>

---
### Skills
- C 3/5
- Bash 1/5
- JavaScript 3/5
- HTML 2/5
- CSS 1/5
- Ruby on Rails 1/5
- Git 1/5
- VS Code 3/5
- JetBrains IDEs 2/5
- Debugging tools 3/5

<br/>

---

### Code samples

[First non-repeating character](https://www.codewars.com/kata/52bc74d4ac05d0945d00054e/javascript)
```
function firstNonRepeatingLetter(s) {
 return s
    .split("")
    .map((charM) =>
      s.split("").filter((charF) => charF.toLowerCase() === charM.toLowerCase())
        .length === 1
        ? charM
        : ""
    )
    .join("")[0] || "";
}
```
[Valid Braces](https://www.codewars.com/kata/5277c8a221e209d3f6000b56/javascript)
```
function validBraces(braces) {
  let   output = braces;
  const regExp = /\(\)|\[\]|\{\}/gm;
  while (output.match(regExp)) output = output.replace(regExp, "");
  return !output;
}
```

[Roman Numerals Decorder](https://www.codewars.com/kata/51b6249c4612257ac0000005/javascript)
```
function solution(roman) {
  roman = roman.toUpperCase();
  const romanNums = {
    I: 1,
    V: 5,
    X: 10,
    L: 50,
    C: 100,
    D: 500,
    M: 1000,
  };
  const romanDigits = Object.keys(romanNums);

  let res = 0;
  for (let i = 0; i < roman.length; ++i) {
    res +=
      romanDigits.indexOf(roman[i]) < romanDigits.indexOf(roman[i + 1])
        ? -romanNums[roman[i]]
        : romanNums[roman[i]];
  }
  return res;
}
```

<br/>

---
### Work experience
Dev projects:
1. Push Swap - creation and implementation of action-performance sorting algorithm for two stacks.
1. Philosophers - Solution for *Dining Philosophers Problem*. Practiced in multithreaded and multi process programs with sync via mutexes and semaphores.

Actual work experience:

1. Project Manager in IT - 1.5 years
1. Cashier in Public Catering - 0.5 years
1. Tecnician in Advertising agency - 0.5 years

<br/>

---
### Education
* (now) **School 21** - C, Ruby on Rails, Bash
* (now) **Rolling Scopes School** - JS, HTML, CSS, Git
* **Udemy** - JS cource
* **College** - Telecommunications

<br/>

---
### English level --- intermediate
In 2018 I was in Sweden for month doing volunteer things. We'd working on Baltic Sea sustainability projects: 
* Biogas reactor
* Geodesic greenhouse
* Biogas filters
* Biogas carsharing

And there I had opportunity to practice my english skills.
