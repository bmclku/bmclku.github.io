---
title: Wiki
date: 2024-12-31

type: landing

sections:
  - block: markdown
    content:
      title: Wiki
      text: |
        이 페이지는 고려대학교 뇌기계인지 연구실 구성원을 위한 내부 위키입니다. 
        연구실 활동에 필요한 주요 정보를 공유하기 위해 운영되며, 접근을 위해 비밀번호 입력이 필요합니다.

        <br>

        <div style="text-align: center;">
          <button onclick="checkWikiPassword()">Access Wiki</button>
        </div>

        <script>
        function checkWikiPassword() {
          const password = prompt("Please enter the password.");

          if (password === "BMCL617b!") {
            window.location.href = "https://alpine-cartwheel-1bd.notion.site/Brain-and-Machine-Cognition-Lab-2580543ef14f80a88278ce35e240cca9";
          } else {
            alert("Incorrect password. Access denied.");
          }
        }
        </script>

    design:
      columns: '1'
      background:
        color: "#FFFFFF"
      spacing:
        padding: ["2em", "0em", "2em", "0em"]
        margin: [0, 0, 0, 0]
      css_class: "wiki"
      
---
