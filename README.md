실행방법
1. git clone후 cd MOVIETALK으로 이동
2. git bash 열어서 터널링 진행하여 데이터베이스 연결
3. 터미널을 열어 파워셀을 두개 킨후 하나의 파워셀에 cd backend 폴더로 이동 후 ./gradlew bootRun 실행
4. 두번째 파워셀에서는 cd front로 이동후 npm install 진행하여 모듈 설치후 npm start로 진행
5. 챗봇 기능은 openai key를 지정 해야함 (backend-src-main-resources-application.properties파일에
맨 하단에 openaikey 작성) 
