# Stefano Gagliardi - Software Engeneering [@sitisrl](https://sitisrl.it)

<h2 align="center">About me</h2>

```typescript
import React from 'react';
import { NextFunctionComponent, NextContext } from 'next'
import { Skills } from './../interfaces/';

export type Bio = {
    [key: string]: string;
}
export interface Developer extends Skills {
    fullName: string;
    bio: Bio;
}

export const GithubProfile: NextFunctionComponent = (props: Developer): ReactElement => (
    <>
       <h1>So much code to print the bio, read it above :)</h1>
    </>
);

GithubProfile.getInitialProps = async ({ pathname }: NextContext) => {
  const bio: Bio = {
	"- ⚡ Quick bio:":                    "Class 95, audoditatta, lots of fiddling, lots of study and lots of nights. Mainly web development and research at sitisrl.it",
	"- 🔭 I’m currently working on":      "Software engineering in web agency. React, Next Js, PHP and more",
	"- 🌱 I’m currently learning":        "Reacy: go deep in NextJs with Typescript. Publish NPM Package. Python data analist pandas",
	"- 👯 I’m looking to collaborate on": "React, Typescript or Python. I dream to study AI e Deep Learning",
	"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
	"- 💬 Ask me about":                  "React, Typescript, scss, PHP, Wordpress, javascrip,",
	"- 📫 How to reach me:":              "stefano.gagliardi@sitisrl.it"
    };
    
    return { fullName: "Stefano Gagliardi", bio: bio };
}
export default GithubProfile;
```
### Hey there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">
<a href="https://discord.gg/XTW52Kt">
  <img align="left" alt="Abhishek's Discord" width="22px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/discord.svg" />
</a>
<a href="https://twitter.com/abhisheknaiidu">
  <img align="left" alt="Abhishek Naidu | Twitter" width="22px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/twitter.svg" />
</a>
<a href="https://www.linkedin.com/in/abhisheknaiidu/">
  <img align="left" alt="Abhishek's LinkedIN" width="22px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/linkedin.svg" />
</a>
<a href="https://open.spotify.com/user/e90fe4zsndbm6xoe2t7t8kogf?si=WaLKpwvWTle0btle2qPb6g">
  <img align="left" alt="Abhishek's Spotify" width="22px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/spotify.svg" />
</a>
<a href="https://www.reddit.com/user/geekyabhi/">
  <img align="left" alt="Abhishek's Reddit" width="22px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/reddit.svg" />
</a>

![](https://visitor-badge.glitch.me/badge?page_id=abhisheknaiidu.abhisheknaiidu)

<br />

Hi, I'm [Abhishek Naidu!](https://blog.abhisheknaidu.tech/), a passionate self-taught Full Stack Web Developer 🚀 from India.

  <img align="right" alt="GIF" src="https://github.com/abhisheknaiidu/abhisheknaiidu/blob/master/code.gif?raw=true" width="500" height="320" />
  
**Talking about Personal Stuffs:**

- 👨🏽‍💻 I’m currently working on something cool :wink:;
- 🌱 I’m currently learning Typescript; 
- 💬 Ask me about anything, I am happy to help;
- 📫 How to reach me: [@abhisheknaiidu](https://twitter.com/abhisheknaiidu);
- 📝[Resume](https://drive.google.com/file/d/1sZ5DFLoYLKvJmgoyJc6VZs-JYROl7A9o/view)

**Languages and Tools:**  

<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/vue/vue.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/react/react.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/5c058a388828bb5fde0bcafd4bc867b5bb3f26f3/topics/graphql/graphql.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/nodejs/nodejs.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/cpp/cpp.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/mysql/mysql.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/firebase/firebase.png"></code>
<code><img height="20" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>

📊 **This Week I Spent My Time On:**
<!--START_SECTION:waka-->
```text
JavaScript   6 hrs 33 mins   ███████████████████▒░░░░░   77.77 % 
C++          47 mins         ██▒░░░░░░░░░░░░░░░░░░░░░░   09.33 % 
CSS          21 mins         █░░░░░░░░░░░░░░░░░░░░░░░░   04.25 % 
JSON         15 mins         ▓░░░░░░░░░░░░░░░░░░░░░░░░   03.10 % 
TypeScript   7 mins          ▒░░░░░░░░░░░░░░░░░░░░░░░░   01.43 % 
```
<!--END_SECTION:waka-->

If you like what I do, maybe consider buying me a coffee/tea 🥺👉👈

<a href="https://www.buymeacoffee.com/abhisheknaiidu" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Buy Me A Coffee" width="150" ></a>

🚧 **My Todoist Stats:**
<!-- TODO-IST:START -->
🏆  6,886 Karma Points           
🌸  Completed 0 tasks today           
✅  Completed 524 tasks so far           
⏳  Longest streak is 10 days
<!-- TODO-IST:END -->


📈 My GitHub Stats

<p align="center"> <img src="https://github-readme-stats.vercel.app/api?username=abhisheknaiidu&show_icons=true&theme=gotham" alt="abhisheknaiidu" />

