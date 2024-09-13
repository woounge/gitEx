# SKN02-4th-1Team
[<img src="https://img.shields.io/badge/notion-00AA55?style=for-the-badge&logo=notion&logoColor=white"/>](https://www.notion.so/SKN02_4th_1Team-8b4ecbc4245343579f61a1eab2d301ad)

**1 팀**<br/>
팀장 : 강민호
팀원 :  박주희, 장준영, 정우영

#  프로젝트

👨‍🏫 **프로젝트 개요**


✅ **요구사항 분석**


🔨 **기술 스택**
<br/>

#### 웹페이지 구현에 사용된 기술
<img src="https://img.shields.io/badge/html-31A8FF?style=for-the-badge&logo=html&logoColor=white"><img src="https://img.shields.io/badge/css-F43059?style=for-the-badge&logo=css&logoColor=white"><img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white"><img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white"><br/>

#### 챗봇 모델 구현에 사용된 기술
<img src="https://img.shields.io/badge/django-092E20?style=for-the-badge&logo=django&logoColor=white"><img src="https://img.shields.io/badge/langchain-DDE072?style=for-the-badge&logo=langchain&logoColor=white"><img src="https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=white"><img src="https://img.shields.io/badge/chromadb-999999?style=for-the-badge&logo=chromadb&logoColor=white"><img src="https://img.shields.io/badge/duckduckgo-DE5833?style=for-the-badge&logo=duckduckgo&logoColor=white"><br/>
<img src="https://img.shields.io/badge/conditionalsearch-0B2C4A?style=for-the-badge&logo=conditionalsearch&logoColor=white"><img src="https://img.shields.io/badge/prompttemplate-EB508D?style=for-the-badge&logo=prompttemplate&logoColor=white"><img src="https://img.shields.io/badge/ragchain-609926?style=for-the-badge&logo=ragchain&logoColor=white"><img src="https://img.shields.io/badge/chatopenai-BBDDE5?style=for-the-badge&logo=chatopenai&logoColor=white">

#### 개발환경
<img src="https://img.shields.io/badge/visualstudiocode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"><img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"/><img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"><img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white"/><img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>

💻 **구조도**

📚 **수행결과 및 결과분석**
- 결과 화면:
(결과 화면 캡처 추가)
- 한계:
검색을 통해 정보를 얻기 때문에 응답을 생성하는 데 시간이 오래 걸린다.
기업의 정보나 기사에 대한 내용을 질문할 경우, 자신의 역할이 아니라고 답변하는 경우가 있다.
- 개선할 점:
검색을 통해 정보를 얻기 때문에 응답 속도가 느리다 → 사용자의 질문에 따라 검색한 내용을 모델이 필요한 내용들로 정리하여 문장을 만든다. 이 문장을 DB에 저장하여 관리하면, 유사한 질문이 있을 때 agent가 검색 대신 DB에서 정보를 빠르게 찾아 응답할 수 있어 속도가 개선될 것이다.
기업의 일부 정보나 기사에 대한 질문을 할 경우 자신의 역할이 아니라고 답변한다 → 관계 없는 질문이라고 판단하는 부분이 template에서 지정된 내용에만 의존하기 때문에 정확도가 낮은 것으로 보인다. 관계의 유무를 판단하는 단계를 좀 더 강화할 필요가 있다.
