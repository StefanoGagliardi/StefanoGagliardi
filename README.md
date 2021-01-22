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

<h2 align="center">You can reach me at :alien:</h2>

<p align="center">
  <a href="https://dev.to/anhello">
    <img src="https://d2fltix0v2e0sb.cloudfront.net/dev-badge.svg" alt="Angel Santiago Jaime Zavala's DEV Profile" height="30" width="30">
  </a>

  <a href="https://www.linkedin.com/in/angel-santiago-jaime-zavala-601813199/">
    <img src="https://www.vectorlogo.zone/logos/linkedin/linkedin-icon.svg" alt="Angel Santiago Jaime Zavala's LinkedIn Profile" height="30" width="30">
  </a>

  <a href="https://stackoverflow.com/users/2946413/angel-santiago-jaime-zavala?tab=profile">
    <img src="https://www.vectorlogo.zone/logos/stackoverflow/stackoverflow-icon.svg" alt="Angel Santiago Jaime Zavala's Stack Overflow Profile" height="30" width="30">
  </a>

  <a href="https://stackexchange.com/users/3525056/angel-santiago-jaime-zavala">
    <img src="https://www.vectorlogo.zone/logos/stackexchange/stackexchange-icon.svg" alt="Angel Santiago Jaime Zavala's Stack Exchange Profile" height="30" width="30">
  </a>

  <a href="https://stackshare.io/anhello">
    <img src="https://cdn.worldvectorlogo.com/logos/stackshare.svg" alt="Angel Santiago Jaime Zavala's StackShare Profile" height="30" width="30">
  </a>
  
  <a href="https://gitlab.com/AnhellO">
    <img src="https://www.vectorlogo.zone/logos/gitlab/gitlab-icon.svg" alt="Angel Santiago Jaime Zavala's GitLab Profile" height="30" width="30">
  </a>
  
  <a href="https://medium.com/@ajzavala">
    <img src="https://www.vectorlogo.zone/logos/medium/medium-tile.svg" alt="Angel Santiago Jaime Zavala's Medium Profile" height="30" width="30">
  </a>
  
  <a href="https://www.youtube.com/channel/UCPUwB4x7_6Dbvwsnfbe1yiQ">
    <img src="https://www.vectorlogo.zone/logos/youtube/youtube-icon.svg" alt="Angel Santiago Jaime Zavala's YouTube Channel" height="30" width="30">
  </a>
</p>

<h2 align="center">My stack :man_technologist:</h2>

<p align="center">Tools that I use on a daily basis, or that I've used or worked (either much or a bit) with on the past</p>
<p align="center">
  <a href="https://stackshare.io/anhello/my-personal-stack">
    <img src="http://img.shields.io/badge/tech-stack-0690fa.svg?style=flat" alt="AnhellO :: StackShare" />
  </a>
</p>

<h2 align="center">Github stats :bar_chart:</h2>

<h4 align="center">Visitor's count :eyes:</h4>

<p align="center"><img src="https://profile-counter.glitch.me/{AnhellO}/count.svg" alt="AnhellO :: Visitor's Count" /></p>

<h4 align="center">Top langs :tongue:</h4>

<p align="center"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AnhellO&langs_count=10&theme=tokyonight&layout=compact" alt="AnhellO :: Top Langs" /></p>

<h4 align="center">Profile stats :musical_keyboard:</h4>

<p align="center"><img src="https://github-readme-stats.vercel.app/api?username=AnhellO&show_icons=true&theme=synthwave" alt="AnhellO :: Profile Stats" /></p>

<p align="center"><img src="https://thumbs.gfycat.com/GoodnaturedFondGaur-size_restricted.gif" alt="Synthwave" height="300" width="500"></p>


---

⭐️ From [@AnhellO](https://github.com/AnhellO)
