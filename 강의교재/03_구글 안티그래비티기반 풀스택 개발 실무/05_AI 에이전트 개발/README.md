### 05_AI 에이전트 개발

<br>

#### 에이전트 제작시 공통 프롬프트
```
c:\env\.env에서 API키를 불러온다

임베딩 모델은 반드시 gemini-embedding-001 모델을 사용해줘

LangChain의 최신 create_agent 방식으로 Gemini 모델 연결
  구형 스타일인 create_react_agent()함수를 쓰지 않도록해

gemini-2.0은 단종되었어 gemini-3.5-flash를 사용해줘

결과출력을 태그로 출력하지 말고 사용자 중심으로 출력하고
'extras' 부분은 출력하지않도록 수정해줘
```
