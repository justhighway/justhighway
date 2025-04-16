
<svg
  width="854"
  height="300"
  viewBox="0 0 854 300"
  xmlns="http://www.w3.org/2000/svg"
  style="z-index:1; position:relative"
>
  <style>
    .text {
      font-size: 70px;
      font-weight: 700;
      font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
      animation: fadeIn 1.2s ease-in-out forwards;
    }
    .desc {
      font-size: 23px;
      font-weight: 500;
      font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Helvetica, Arial, sans-serif, Apple Color Emoji, Segoe UI Emoji;
      animation: fadeIn 1.2s ease-in-out forwards;
    }
    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }
  </style>

  <defs>
    <linearGradient id="linear" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#1D976C" />
      <stop offset="100%" stop-color="#93F9B9" />
    </linearGradient>
    <filter id="blurFilter">
      <feGaussianBlur stdDeviation="12" />
    </filter>
  </defs>

  <!-- Animated Circles -->
  <circle
    cx="50%" cy="50%" r="75"
    fill="url(#linear)" opacity="0.2"
    filter="url(#blurFilter)"
    transform="scale(-1, 1)" transform-origin="center"
  >
    <animate attributeName="cx" values="50%;50%;50%;50%;50%" dur="10s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1" />
    <animate attributeName="cy" values="50%;50%;50%;50%;50%" dur="12s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1" />
  </circle>

  <circle
    cx="45%" cy="50%" r="90"
    fill="url(#linear)" opacity="0.3"
    filter="url(#blurFilter)"
    transform="scale(-1, 1)" transform-origin="center"
  >
    <animate attributeName="cx" values="45%;50%;55%;50%;45%" dur="30s" begin="1s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1" />
    <animate attributeName="cy" values="50%;50%;50%;50%;50%" dur="36s" begin="1s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1" />
  </circle>

  <circle
    cx="60%" cy="50%" r="84"
    fill="url(#linear)" opacity="0.15"
    filter="url(#blurFilter)"
    transform="scale(-1, 1)" transform-origin="center"
  >
    <animate attributeName="cx" values="60%;50%;40%;50%;60%" dur="15s" begin="2s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1" />
    <animate attributeName="cy" values="50%;50%;50%;50%;50%" dur="18s" begin="2s" repeatCount="indefinite" calcMode="spline" keySplines="0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1;0.4 0 0.6 1" />
  </circle>

  <!-- Embedded Image (use image tag instead of a tag) -->
  <image
    href="https://camo.githubusercontent.com/c485c9a13a6f41629171d509e81c2f09f0332a97af2bbb81afddff784dae6a35/68747470733a2f2f76656c6f672e76656c63646e2e636f6d2f696d616765732f6a757374686967687761792f706f73742f66666131366538352d306631612d343739392d386235312d3562393433623865366632612f696d6167652e706e67"
    x="50%" y="40%" width="100" height="100"
    transform="translate(-50, -50)"
    style="animation: fadeIn 1.2s ease-in-out forwards;"
  />

  <!-- Welcome Text -->
  <text
    text-anchor="middle"
    alignment-baseline="middle"
    x="50%" y="66%"
    class="desc"
    fill="#f7f5f5"
  >
    환영합니다
  </text>
</svg>
<div align="center">

<a>
  <img align="center" src="https://velog.velcdn.com/images/justhighway/post/ffa16e85-0f1a-4799-8b51-5b943b8e6f2a/image.png" style="width: 40%"/>
</a>



---

<a>
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=justhighway&count_private=true&show_icons=true&hide=stars"/>
</a>

---

<a>
  <img src="https://img.shields.io/badge/html5-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/css3-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/javascript-%23F7DF1E.svg?&style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/typescript-%233178C6.svg?&style=for-the-badge&logo=typescript&logoColor=white" />
</a>

<br/>

<a>
  <img src="https://img.shields.io/badge/react-%2361DAFB.svg?&style=for-the-badge&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/next.js-%23000000.svg?&style=for-the-badge&logo=next.js&logoColor=white" />
  <img src="https://img.shields.io/badge/react%20router-%23CA4245.svg?&style=for-the-badge&logo=react%20router&logoColor=white" />
  <img src="https://img.shields.io/badge/tailwind%20css-%2338B2AC.svg?&style=for-the-badge&logo=tailwind%20css&logoColor=white" />
</a>

</div>
<!--
**justhighway/justhighway** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
