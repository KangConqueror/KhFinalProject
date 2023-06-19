FORK된 해당 프로젝트는 국비지원 교육시 Final Project로 진행한 작업물 입니다. 😃 

&nbsp;

## 1. 어떤 프로젝트 인가? 
Final Project 진행 당시 해외 dreamboard.com 이라는 꿈을 기록하는 일기 같은 웹 페이지를 보았는데
다른 사람들과 꿈을 공유하고, 사고, 팔 수 있는 웹 페이지를 개발해보고 싶어
소설책 **달러구트 꿈백화점** 을 모티브로 만들었습니다.

&nbsp;
  <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/main.png" />
&nbsp;

## 2-1. 나의 작업은?
SemiProject 때 구현 하지 못한 채팅와 게시판
WebSocket을 사용한 실시간 채팅 기능을 구현 하고 싶어서 **채팅과 게시판** 을 담당하였습니다.

&nbsp;

## 2-2. 개발 환경 / 기술 스택은?
**개발환경**

- STS 
- Apache Tomcat 9.0
- jsp
- Mybatis
- maven
- Visual Studio Code
- SQL Developer

**기술 스택**

- Java(jdk 11)
- spring Framework / MVC 아키텍처 패턴
- Oracle DB
- javascript
- jQuery
- HTML5
- CSS

&nbsp;

## 2-3. 나의 작업 파일 경로
**spring**
1. 채팅게시판
- controller : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/chat/controller/ChatController.java
- service : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/chat/service/ChatService.java
- dao : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/chat/dao/ChatDao.java
- vo : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/chat/vo/ChatBoardVo.java
- mapper(mybatis) : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/resources/mybatis/mapper/chat-mapper.xml

2. 채팅
- server : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/socket/ChatSocketServer.java
- dao : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/chat/dao/ChatDao.java<br/>
( 51번 행 부터)
&nbsp;

- vo : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/java/com/dds/app/chat/vo/ChatVo.java
- mapper(mybatis) : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/resources/mybatis/mapper/chat-mapper.xml<br/>
( 78번 행 부터 ) 



**jsp**
- 채팅게시판 : https://github.com/KangConqueror/KhFinalProject/tree/main/workspace/FinalPrj/src/main/webapp/WEB-INF/views/chat

- 채팅 : https://github.com/KangConqueror/KhFinalProject/blob/main/workspace/FinalPrj/src/main/webapp/WEB-INF/views/chat/room.jsp

&nbsp;

## 2-4. 완성된 화면
<details>
  <summary>상품 목록 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/ProductList.png" />
  </div>
</details>
<details>
  <summary>상품 상세 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/ProductDetail1.png" />
  </div>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/ProductDetail2.png" />
  </div>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/ProductDetail3.png" />
  </div>
</details>
<details>
  <summary>결제 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/Pay.png" />
  </div>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/PayComplate.png" />
  </div>
</details>
<details>
  <summary>장바구니 화면</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/Cart.png" />
  </div>
</details>
<details>
  <summary>결제 목록</summary>
  <br />
  <div markdown="1">
    <image src="https://github.com/JongChanP/FinalProject/blob/main/FinalImage/PayList.png" />
  </div>
</details>
