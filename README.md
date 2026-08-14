<!-- ====================================================== -->
<!--                 DEV1NIBORGES / README                  -->
<!-- ====================================================== -->

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:00E5FF,45:0077FF,100:0D1117&height=185&section=header&text=VINICIUS%20BORGES&fontSize=42&fontColor=FFFFFF&animation=fadeIn&fontAlignY=36&desc=FRONT-END%20DEVELOPER%20%2F%2F%20DEV1NIBORGES&descAlignY=57&descSize=14"/>

<br>

`DESIGNING INTERFACES` · `WRITING LOGIC` · `CONNECTING DATA` · `SHIPPING TO THE WEB`

<br><br>

<a href="https://dev1niborges.github.io/portfolio/">
  <img src="https://img.shields.io/badge/PORTFOLIO-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=0D1117"/>
</a>

<a href="https://github.com/deV1niborges">
  <img src="https://img.shields.io/badge/GITHUB-161B22?style=for-the-badge&logo=github&logoColor=FFFFFF"/>
</a>

<a href="https://www.linkedin.com/in/dev1niborges/">
  <img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=FFFFFF"/>
</a>

</div>

---

## `01 / BUILD`

```ts
interface Developer {
  name: string;
  handle: string;
  focus: string;
  approach: string[];
}

const dev: Developer = {
  name: "Vinicius Borges",
  handle: "@dev1niborges",

  focus: "Interactive Front-end Development",

  approach: [
    "build clear interfaces",
    "write maintainable logic",
    "connect real data",
    "create meaningful interactions"
  ]
};

export default dev;
```

Meu foco está no desenvolvimento de experiências web onde **interface e código trabalham juntos**.

Gosto de construir desde a estrutura da página até as interações, consumo de APIs, animações e publicação do projeto.

Não apenas fazer uma tela funcionar — mas entender **como cada parte se conecta**.

---

## `02 / TOOLKIT`

<table>
<tr>
<td width="33%" valign="top">

### `CORE`

<br>

<img src="https://skillicons.dev/icons?i=html,css,js,react&theme=dark"/>

<br><br>

`HTML5`  
`CSS3`  
`JavaScript`  
`React`

</td>

<td width="33%" valign="top">

### `WEB`

<br>

<img src="https://skillicons.dev/icons?i=nodejs,mongodb,threejs&theme=dark"/>

<br><br>

`REST APIs`  
`Node.js`  
`MongoDB`  
`Three.js`

</td>

<td width="33%" valign="top">

### `WORKFLOW`

<br>

<img src="https://skillicons.dev/icons?i=git,github,vscode,vercel,cloudflare&theme=dark"/>

<br><br>

`Git`  
`GitHub`  
`VS Code`  
`Vercel`  
`Cloudflare`

</td>
</tr>
</table>

<br>

<p>
<img src="https://img.shields.io/badge/GSAP-Animation-00E5FF?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/ScrollTrigger-Interaction-00E5FF?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/REST-API-00E5FF?style=flat-square&labelColor=161B22"/>
<img src="https://img.shields.io/badge/Responsive-Web-00E5FF?style=flat-square&labelColor=161B22"/>
</p>

---

## `03 / ENGINEERING`

<table>
<tr>

<td width="25%" align="center">

### `STRUCTURE`

Semantic HTML

Component organization

Clear hierarchy

Accessible markup

</td>

<td width="25%" align="center">

### `INTERACTION`

DOM events

Application state

Async JavaScript

Web animations

</td>

<td width="25%" align="center">

### `DATA`

Fetch API

REST endpoints

JSON

Client / Server flow

</td>

<td width="25%" align="center">

### `DELIVERY`

Git workflow

Responsive testing

Performance

Deploy

</td>

</tr>
</table>

<br>

```txt
01  STRUCTURE
        ↓
02  INTERFACE
        ↓
03  LOGIC
        ↓
04  DATA
        ↓
05  INTERACTION
        ↓
06  TEST
        ↓
07  SHIP
```

---

## `04 / PROJECTS`

<table>

<tr>
<td width="23%">
<strong>PORTFOLIO</strong>
<br>
<sub>Interactive Experience</sub>
</td>

<td width="45%">
Portfólio criado como uma experiência web interativa, combinando interface, animação, scroll e elementos 3D.
</td>

<td width="20%">
<code>JavaScript</code><br>
<code>Three.js</code><br>
<code>GSAP</code>
</td>

<td width="12%" align="center">
<a href="https://github.com/deV1niborges/portfolio">CODE</a>
<br><br>
<a href="https://dev1niborges.github.io/portfolio/">LIVE</a>
</td>
</tr>


<tr>
<td>
<strong>DISTRIBUIDORA EAB</strong>
<br>
<sub>Business Website</sub>
</td>

<td>
Interface comercial responsiva desenvolvida para apresentar produtos e facilitar a navegação e o contato com a empresa.
</td>

<td>
<code>HTML</code><br>
<code>CSS</code><br>
<code>JavaScript</code>
</td>

<td align="center">
<a href="https://github.com/deV1niborges/projeto-distribuidora-eab">CODE</a>
</td>
</tr>


<tr>
<td>
<strong>SPOTIFY</strong>
<br>
<sub>Full-stack Study</sub>
</td>

<td>
Aplicação inspirada no Spotify utilizada para explorar integração entre interface, lógica de aplicação e conceitos full-stack.
</td>

<td>
<code>React</code><br>
<code>Node.js</code><br>
<code>API</code>
</td>

<td align="center">
<a href="https://github.com/deV1niborges/projeto-spotify">CODE</a>
</td>
</tr>


<tr>
<td>
<strong>QUIZ</strong>
<br>
<sub>JavaScript Application</sub>
</td>

<td>
Aplicação interativa construída para trabalhar manipulação do DOM, eventos, controle de estado e feedback ao usuário.
</td>

<td>
<code>JavaScript</code><br>
<code>DOM</code><br>
<code>Events</code>
</td>

<td align="center">
<a href="https://github.com/deV1niborges/projeto-quiz">CODE</a>
</td>
</tr>

</table>

---

## `05 / UNDER_THE_HOOD`

```javascript
const interfacePipeline = async (idea) => {

  const structure = buildSemanticHTML(idea);

  const interface = createResponsiveUI(structure);

  const behavior = addInteractions(interface);

  const data = await connectAPI(behavior);

  const experience = enhance({
    app: data,
    motion: ["GSAP", "ScrollTrigger", "Three.js"]
  });

  return deploy(experience);
};
```

```txt
INPUT
  └─ idea

PROCESS
  ├─ semantic structure
  ├─ responsive interface
  ├─ application logic
  ├─ asynchronous data
  ├─ interaction
  └─ motion

OUTPUT
  └─ web experience
```

---

## `06 / LAB`

Aqui ficam as áreas que estou explorando com mais profundidade nos meus projetos.

<table>
<tr>

<td width="33%" valign="top">

### `REACT`

Component architecture

State management

Hooks

Reusable UI

</td>

<td width="33%" valign="top">

### `JAVASCRIPT`

Application structure

Async / Await

Modules

API integration

</td>

<td width="33%" valign="top">

### `MOTION`

Three.js

GSAP

ScrollTrigger

Interactive UI

</td>

</tr>
</table>

```bash
dev1niborges@web:~$ npm run build

> structuring interface...
> connecting application logic...
> loading interactions...
> optimizing experience...
> deploying...

✓ build completed
```

---

## `07 / REPOSITORY_SIGNAL`

<div align="center">

<img src="https://img.shields.io/github/followers/deV1niborges?style=for-the-badge&logo=github&label=FOLLOWERS&labelColor=0D1117&color=00E5FF"/>

<img src="https://img.shields.io/github/last-commit/deV1niborges/portfolio?style=for-the-badge&logo=git&label=LAST%20PORTFOLIO%20COMMIT&labelColor=0D1117&color=00E5FF"/>

<br><br>

<img src="https://img.shields.io/github/languages/top/deV1niborges/portfolio?style=flat-square&label=PORTFOLIO%20LANGUAGE&labelColor=161B22&color=00E5FF"/>

<img src="https://img.shields.io/github/repo-size/deV1niborges/portfolio?style=flat-square&label=REPOSITORY%20SIZE&labelColor=161B22&color=00E5FF"/>

<img src="https://img.shields.io/github/license/deV1niborges/portfolio?style=flat-square&label=LICENSE&labelColor=161B22&color=00E5FF"/>

</div>

---

## `08 / PRINCIPLES`

```txt
01. Make it work.
02. Make it clear.
03. Make it responsive.
04. Make it reusable.
05. Make interaction feel intentional.
06. Ship it.
```

---

## `09 / CONNECT`

<div align="center">

```txt
┌──────────────────────────────────────────────┐
│                                              │
│             DEV1NIBORGES                     │
│                                              │
│        FRONT-END / WEB / INTERACTION         │
│                                              │
└──────────────────────────────────────────────┘
```

<br>

<a href="https://dev1niborges.github.io/portfolio/">
  <img src="https://img.shields.io/badge/EXPLORE_PORTFOLIO-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=0D1117"/>
</a>

<a href="https://github.com/deV1niborges">
  <img src="https://img.shields.io/badge/EXPLORE_CODE-161B22?style=for-the-badge&logo=github&logoColor=FFFFFF"/>
</a>

<a href="https://www.linkedin.com/in/dev1niborges/">
  <img src="https://img.shields.io/badge/CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=FFFFFF"/>
</a>

<a href="mailto:vinicius.borges2@icloud.com">
  <img src="https://img.shields.io/badge/SEND_EMAIL-161B22?style=for-the-badge&logo=icloud&logoColor=00E5FF"/>
</a>

<br><br><br>

<sub>
CODE WITH PURPOSE · INTERFACE WITH PERSONALITY · BUILT FOR THE WEB
</sub>

<br>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0D1117,45:0077FF,100:00E5FF&height=105&section=footer"/>

</div>
