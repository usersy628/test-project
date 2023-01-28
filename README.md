# react.js로 게시판 만들어보기
https://goddino.tistory.com/63 문서를 참조해서 시작해보자

로컬서버 띄우기부터 애를 먹는다
 
package.json 에서 scripts 필드에 start 추가 후 npm start

안됀다


    npm install --global yarn
    yarn --version
    yarn add react-scripts


![image](https://user-images.githubusercontent.com/100139289/215260042-a81c119f-4953-4548-a848-6c7bb95d4fc8.png)

index.html 파일을 찾을 수 없다고 한다.

public 파일 경로를 찾는 것 같은데 public을 만들어야 하나?

2시간 검색 결과로도 해결되지 않아 프로젝트를 삭제 후 다른 문서를 참조하기로 결정.

https://artistjay.tistory.com/20

    C:\workspace\test-project>npx create-react-app simple-react-board
    
열심히 패치 후 npm start 명령어를 입력했으나 또 안됀다

no such file or directory, opne 'C:\workspace\test-project\package.json'

패키지 제이슨을 못찾겠다고 한다

패키지 제이슨의 경로는 C:\workspace\test-project\simple-react-board\package.json 이므로 경로 수정을 해준다

cd simple-react-board 로 경로 이동.

    npm start
성공!

#
