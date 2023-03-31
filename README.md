
### Connect with me on <a href="https://www.linkedin.com/in/pablo-garcia-plaza/">
 <img align="center" alt="linkedn"  src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

```ts
import React, { useState } from 'react';

function About() {
  const [name, setName] = useState("Pablo");
  const [location, setLocation] = useState("Antwerp");
  const [driven, setDriven] = useState(true);
  const [Situation, setSituation] = useState("I completed a 7-month full-stack developer course and a 3-month internship.");
  const [goal, setGoal] = useState("I'm looking for a company that supports ongoing learning and growth.");
  const [focusing, setFocusing] = useState("Refining my full-stack expertise with React and Node.js.");
  const [languages, setLanguages] = useState(["HTML", "CSS", "JavaScript", "TypeScript", "C#", "PHP"]);
  const [developmentUtilities, setDevelopmentUtilities] = useState(["React", "Node.js", "Express", "Strapi"]);
  const [extraUtilities, setExtraUtilities] = useState(
  ["Git", 
   "Github", 
   "Jira", 
   "Bitbucket", 
   "mySQL", 
   "postgreSQL", 
   "MongoDB", 
   "Netlify", 
   "Heroku"]
   );

  return (
    <div>
      <h1>About Me</h1>
      <ul>
        <li>Name: {name}</li>
        <li>Location: {location}</li>
        <li>Driven: {driven.toString()}</li>
      </ul>
      <p><strong>Present Situation:</strong> {presentSituation}</p>
      <p><strong>Goal: </strong> {goal}</p>
      <p><strong>Focusing On:</strong> {focusing}</p>
      <p><strong>Languages:</strong></p>
      <ul>
        {languages.map((language) => <li key={language}>{language}</li>)}
      </ul>
      <p><strong>Development Utilities:</strong></p>
      <ul>
        {developmentUtilities.map((utility) => <li key={utility}>{utility}</li>)}
      </ul>
      <p><strong>Extra Utilities:</strong></p>
      <ul>
        {extraUtilities.map((utility) => <li key={utility}>{utility}</li>)}
      </ul>
    </div>
  );
}

export default About;
```

## Stats
![PabloGP18 GitHub stats](https://github-readme-stats.vercel.app/api?username=PabloGP18&theme=blue-green) <br>
![Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=PabloGP18&theme=blue-green)<br>
![Visitor Count](https://profile-counter.glitch.me/PabloGP18/count.svg)



<!--
**PabloGP18/PabloGP18** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
