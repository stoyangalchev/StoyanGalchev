[![MasterHead](![<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=, initial-scale=">
  <title>Clock</title>
  <style>
      body {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Lato", sans-serif;
    }
    #clock {
      height: 100vh;
      width: 100%;
      background-color: #14080e;
      color: #e9eb9e;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 50px;
    }
  </style>
</head>

<body>
  <div id="clock">
  </div>
  <script>
      function clock() {
      let date = new Date();
      let hrs = date.getHours();
      let mins = date.getMinutes();
      let secs = date.getSeconds();
      let period = "AM";
    
      if (hrs == 0) hrs = 12;
      if (hrs > 12) {
        hrs = hrs - 12;
        period = "PM";
      }
    
      hrs = hrs < 10 ? `0${hrs}` : hrs;
      mins = mins < 10 ? `0${mins}` : mins;
      secs = secs < 10 ? `0${secs}` : secs;
    
      let time = `${hrs}:${mins}:${secs} ${period}`;
      setInterval(clock, 1000);
      document.getElementById("clock").innerText = time;
    }
    
    clock();

  </script>
</body>

</html>]
<h1 align="center">Hi 👋, I'm Stoyan Galchev</h1>
<h3 align="center">A passionate student developer from Bulgaria.</h3>


<p align="left"> <img src="https://komarev.com/ghpvc/?username=stoyangalchev&label=Profile%20views&color=0e75b6&style=flat" alt="stoyangalchev" /> </p>

![Capture](https://user-images.githubusercontent.com/119026878/223441249-53758f25-85c5-4eb1-bf3f-dc5aa6e6a4ea.PNG)


- 🌱 I’m currently learning **JS-Path Of SoftUni(Software University)**

- 📫 How to reach me **galchev98@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://instagram.com/stoyangalchev_" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="stoyangalchev_" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> </p>

## ⚡GitHub Stats
<a href="https://github.com/stoyangalchev">
  <img height="180em" alt="My GitHub Stats" src="https://github-readme-stats.vercel.app/api?username=stoyangalchev&show_icons=true&bg_color=00000000&hide_border=true&text_color=3498db&count_private=true&include_all_commits=true" />



