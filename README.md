<html>
  <head>
    <style>
      .animated-text {
        display: inline-block;
        animation: translateText 5s infinite;
      }

      @keyframes translateText {
        0% {
          transform: translateX(0);
        }
        33% {
          transform: translateX(-100%);
        }
        66% {
          transform: translateX(-200%);
        }
        100% {
          transform: translateX(0);
        }
      }
    </style>
  </head>
  <body>
    <div id="greeting" class="animated-text"># Hi there, I'm Bete Goshme 👋</div>

    <script>
      const greetings = {
        spanish: "¡Hola, soy Bete Goshme! 👋",
        french: "Salut, je suis Bete Goshme! 👋",
        german: "Hallo, ich bin Bete Goshme! 👋",
      };

      const greetingElement = document.getElementById("greeting");

      function animateGreetings() {
        let currentIndex = 0;
        const languages = Object.keys(greetings);

        setInterval(() => {
          currentIndex = (currentIndex + 1) % languages.length;
          const currentLanguage = languages[currentIndex];
          greetingElement.textContent = greetings[currentLanguage];
        }, 2000);
      }

      animateGreetings();
    </script>
  </body>
</html>



...

## GitHub Activity

- Stars: ![GitHub Stars](https://img.shields.io/github/stars/bete7512?style=social)
- Followers: ![GitHub Followers](https://img.shields.io/github/followers/bete7512?style=social)



Here are the programming languages I frequently use in my GitHub repositories, along with their respective rankings based on GitHub's language statistics:

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=bete7512&layout=compact)

## Languages and Tools

<div style="display: inline-block">
  <img src="https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black&style=flat-square" alt="JavaScript">
  <img src="https://img.shields.io/badge/-HTML5-E34F26?logo=html5&logoColor=white&style=flat-square" alt="HTML5">
  <img src="https://img.shields.io/badge/-CSS3-1572B6?logo=css3&logoColor=white&style=flat-square" alt="CSS3">
  <img src="https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white&style=flat-square" alt="Git">
  <img src="https://img.shields.io/badge/-GitHub-181717?logo=github&logoColor=white&style=flat-square" alt="GitHub">
  <img src="https://img.shields.io/badge/-VS_Code-007ACC?logo=visual-studio-code&logoColor=white&style=flat-square" alt="VS Code">
  <img src="https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white&style=flat-square" alt="Docker">
  <img src="https://img.shields.io/badge/-GraphQL-E10098?logo=graphql&logoColor=white&style=flat-square" alt="GraphQL">
  <img src="https://img.shields.io/badge/-NGINX-009639?logo=nginx&logoColor=white&style=flat-square" alt="NGINX">
  <img src="https://img.shields.io/badge/-AWS_Amplify-FF9900?logo=amazon-aws&logoColor=white&style=flat-square" alt="AWS Amplify">
  <img src="https://img.shields.io/badge/-AWS_EC2-232F3E?logo=amazon-aws&logoColor=white&style=flat-square" alt="AWS EC2">
  <img src="https://img.shields.io/badge/-AWS_Lambda-FF9900?logo=amazon-aws&logoColor=white&style=flat-square" alt="AWS Lambda">
  <img src="https://img.shields.io/badge/-Hasura-FF00FF?logo=hasura&logoColor=white&style=flat-square" alt="Hasura">
</div>

Feel free to explore my repositories and reach out to me if you have any questions or ideas for collaboration. Happy coding! 🚀
