<table style="width: 100%">
    <tr style="position: relative">
        <th style="width: 50px">
        <a href="https://rs.school/"><img src="./rss-logo.svg" style="width: 50px; position: absolute; top: 0"></a></th>
        <th style="text-align: right; font-size: 30px; line-height: 0.9em; position: absolute; width: calc(100% - 260px); bottom: -0.6px">
          <span style="font-size: 20px; font-weight: 500">ZHDANKO</span><br />ALEKSANDR<br />
          <span style="font-size: 15px; font-weight: 200">Frontend Developer</span>
        </th>
        <th style="width: 150px">
        <img src="./images/avatar.jpg"></th>
    </tr>
</table>

![place icon](./images/icons/place-icon.svg) Tbilisi, Georgia &nbsp;&nbsp;
![phone icon](./images/icons/phone-icon.svg) +995558159233 &nbsp;&nbsp;
[![linkedin icon](./images/icons/linkedin-icon.svg) LinkedIn](https://linkedin.com/in/zhdko/) &nbsp;&nbsp;
[![github icon](./images/icons/github-icon.svg) GitHub](https://github.com/Zhdko) &nbsp;&nbsp; ![email icon](./images/icons/email-icon.svg) lex.zhdanko@gmail.com &nbsp;&nbsp; ![discord icon](./images/icons/discord-icon.svg) zhdko

# About me
Front-End Developer at the start of my career. I enjoy turning ideas into working interfaces and seeing the results of my work. I thrive in teamwork and have experience leading study projects as a team leader. My goal for the next year is to strengthen my knowledge of React, learn Python, and improve my algorithmic thinking to reach Junior+ level and launch my first application.

<br />

<table style="width: 100%">
  <tr>
    <th style="color: #299af7ff; font-weight: 900; font-size: 17px">SKILLS:</th>
    <th style="text-align: center">JS</th>
    <th style="text-align: center">CSS3</th>
    <th style="text-align: center">HTML5</th>
    <th style="text-align: center">React</th>
    <th style="text-align: center">GIT</th>
    <th style="text-align: center">Node.js</th>
    <th style="text-align: center">Mongo.DB</th>
  </tr>
</table>

<br />

# ![](./images/icons/codewar-icon.svg) Code example

 <details>
  <summary>Problem</summary>
  Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case). The next words should be always capitalized.
</details>

### Solution
```JS
function toCamelCase(str){
let arr = str.split(/[-, _]/);
  let fullString = arr[0];
  arr.shift();
  for (let i = 0; i < arr.length; i++) {
    let firstSymb = arr[i].split('')[0].toUpperCase();
    let secondSymb = arr[i].slice(1);
    let word = firstSymb + secondSymb;
    fullString = fullString + word;
  }
  return fullString;
}
```

# Work experience

###  Movie Explorer <sup>Movie search service</sup>

#### Functionality:

- User authorization / registration
-	Movie search by keyword
- Movie filtering by duration
- Profile editing
- Saving / removing movies to/from favorites
- Authorization using JWT token
- Saving movie list in local storage

[![github icon](./images/icons/github-icon.svg) Repository](https://github.com/Zhdko/movies-explorer-full?tab=readme-ov-file#%D1%81%D0%B0%D0%B9%D1%82)

***

### Mesto <sup>Photo sharing service</sup>
- User authorization / registration
- Create / delete / like photo cards
- JWT token-based authentication
- Edit user profile

[![github icon](./images/icons/github-icon.svg) Repository](https://github.com/Zhdko/movies-explorer-full?tab=readme-ov-file#%D1%81%D0%B0%D0%B9%D1%82)&nbsp;&nbsp;
[![web icon](./images/icons/web-icon.png) Demo](https://zhdko.github.io/mesto-react/)

# Education
- **Yandex Prakticum**, Frontend developer
- **HarvardX: CS50's Introduction to Computer Science course**

# Languages
- **Russian:** Native
- **English:** B1 
- **Japanese:** Beginner
- **Georgian:** Beginner