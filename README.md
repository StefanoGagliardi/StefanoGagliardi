<h1 align="center" style="border:none !important">Stefano Gagliardi - Software Engeneering @sitisrl
<h2 align="center"  style="border:none !important">About me</h2>
<h3 align="center"  style="border:none !important">Simple coding joke & Bio</h3>

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
       <h1>So much code to print the bio, read it below :)</h1>
    </>
);

GithubProfile.getInitialProps = async ({ pathname }: NextContext) => {
  const bio: Bio = {
	"- ⚡ Quick bio:":                    "Class 1995, self-taught, lots of fiddling, lots of study and lots of nights. Mainly web development and research at sitisrl.it",
	"- 🔭 I’m currently working on":      "Software engineering in web agency. React, Next Js, PHP and more",
	"- 🌱 I’m currently learning":        "React go deep in NextJs with Typescript. Publish NPM Package. Python data analist pandas",
	"- 👯 I’m looking to collaborate on": "React, Typescript or Python. I dream to study AI e Deep Learning",
	"- 🤔 I’m looking for help with":     "Anything related to what I am currently learning 😅",
	"- 💬 Ask me about":                  "React, Typescript, scss, PHP, Wordpress, javascript"
    };
    
    return { fullName: "Stefano Gagliardi", bio: bio };
}
export default GithubProfile;
```
### Hey there <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px">
<a href="https://twitter.com/spolakg">
  <img align="left" alt="Stefano Gagliardi's Twitter" width="22px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/twitter.svg" />
</a>
<a href="https://it.linkedin.com/in/stefano-gagliardi-2a6aa7133">
  <img align="left" alt="Stefano Gagliardi's LinkedIN" width="22px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/linkedin.svg" />
</a>
<a href="https://open.spotify.com/user/11157385591">
  <img align="left" alt="Stefano Gagliardi's Spotify" width="22px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/spotify.svg" />
</a>
<a href="https://www.reddit.com/user/geekyabhi/">
  <img align="left" alt="Abhishek's Reddit" width="22px" src="https://raw.githubusercontent.com/peterthehan/peterthehan/master/assets/reddit.svg" />
</a>

![](https://visitor-badge.glitch.me/badge?page_id=StefanoGagliardi)

<br />

Hi, I'm [Stefano Gagliardi!](https://gagliardistefano.i/), a passionate self-taught Full Stack Web Developer 🚀 from Italy.

  <img align="right" alt="GIF" src="https://github.com/abhisheknaiidu/abhisheknaiidu/blob/master/code.gif?raw=true" width="500" height="320" />
  
**Talking about Personal Stuffs:**

- 👨🏽‍💻 I’m currently working on something cool :wink: <br/>React & React-Native ultimate form generator oriented for developers;
- 🌱 I’m currently study source code in deep NextJs & React-hook-form;
- 💬 Ask me about anything, I am happy to help. I gladly participate in open source projects.
- 📫 How to reach me: [Stefano Gagliardi](mailto:stefano2.gagliardi@sitisrl.it);
- 📝[Resume](https://github.com/StefanoGagliardi/)

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

If you like what I do, maybe consider buying me a coffee/tea 🥺👉👈 <br/>
A coffee to increase the productivity of the many open source projects offered to the community!

<a href="https://www.buymeacoffee.com/stefanogagliardi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-red.png" alt="Buy Me A Coffee" width="150" ></a>

:heart: **My favorite front-end library:**
1. Bootstrap grid
2. Framer Motion
3. React & NextJs

:trophy: **My top three own repo:**
1. [react-magic-form]()
2. [next-redux-ts-boilerplate]()
3. [siti-address-plugin]()

:pencil2: **My Todoist in freetime:**
1. :a: Finire la bio: copiare icone svg social in questa repo + aggiungere Facebook e Instagram
2. :b: Aggiornare la lista e le icone dei linguaggi usati
3. :c: Capire il funzionamento e aggiornare il grafico del tempo speso per linguaggio

Meno prioritari:
3 Riorganizzare le repo e pubblicarle
4 Ultimare SITI-address-plugin & 


📈 My GitHub Stats: six coffe/day
