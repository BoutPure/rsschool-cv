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
<!-- Краткая информация о себе (ваша цель и приоритеты, подчеркните свои сильные стороны, расскажите о своём опыте работы, если опыта работы нет, расскажите о своём стремлении учиться и узнавать новое) -->
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
<!-- Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете) -->
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
to fill
<!-- Опыт работы. Junior Dev может перечислить учебные проекты с указанием использованных навыков и ссылками на исходный код. -->
<br/>

---
### Education
* now - School 21 - C, Ruby on Rails, Bash
* now - Rolling Scopes School - JS, HTML, CSS, Git
* Udemy - JS cource
* College - Telecommunications
<!-- Образование (включая пройденные курсы и тренинги) -->
<br/>

---
### English level --- intermediate
In 2018 I was in Sweden for month doing volunteer things. We'd working on Baltic Sea sustainability projects: 
* Biogas reactor
* Geodesic greenhouse
* Biogas filters
* Biogas carsharing

And there I had opportunity to practice my english skills.
<!-- Английский язык (уровень английского языка, если была языковая практика, расскажите о ней) -->