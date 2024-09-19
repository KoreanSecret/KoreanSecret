# Seunghoon's GitHub

![GitHub Profile Views](https://komarev.com/ghpvc/?username=yourusername&color=brightgreen)

## Hi there 👋

안녕하십니까 웹 개발자가 되기 위해 열정과 성실성을 갖고 노력중인 이승훈 입니다. 

## 🛠️ Tech Stack 🛠️

![Java](https://img.shields.io/badge/Java-007396?logo=java&logoColor=white&style=flat)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=flat)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=flat)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=flat)
![AWS](https://img.shields.io/badge/AWS-232F3E?logo=amazon-aws&logoColor=white&style=flat)

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white&style=flat)
![MyBatis](https://img.shields.io/badge/MyBatis-5C2D91?logoColor=white&style=flat)
![MediaPipe](https://img.shields.io/badge/MediaPipe-FF6F00?logoColor=white&style=flat)
![YOLO](https://img.shields.io/badge/YOLO-00FFFF?logoColor=white&style=flat)
![LSTM](https://img.shields.io/badge/LSTM-FF9E0F?logoColor=white&style=flat)

![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?logo=tensorflow&logoColor=white&style=flat)
![Eclipse](https://img.shields.io/badge/Eclipse-2C2255?logo=eclipse&logoColor=white&style=flat)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?logo=intellij-idea&logoColor=white&style=flat)

## 📈 My Baekjoon Stats 📈

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=asdf9392)](https://solved.ac/asdf9392)

## 프 로 젝 트 이 력

### 수어 탐지 웹 사이드 프로젝트
2024.07.15 ~ 2024.07.26 

사용한 기술 및 개발환경:
`Python`, `Java SpringBoot`, `Jupyter`, `Tensorflow` ,`Mediapipe`, `Yolo`, `LSTM`, `CNN` , `Eclipse` , `JDK17` 

- **GitHub Repository** :(준비중)
- **Youtube 시연영상** : (준비중)

  
- **세부기능**<br>
    -Mediapipe 를 활용한 손동작 추출 기술<br>
    -Yolo 을 이용한 이미지 분석<br>
    -LSTM 을 이용한 시간적 패턴 학습<br>
    -SpringBoot 를 이용한 웹 개발<br>
    
- **프로젝트 아키텍처**
  
클라이언트 (프론트엔드):
사용자는 브라우저에서 실시간 카메라 입력을 받아 웹 애플리케이션을 통해 수어 영상을 서버로 전달합니다. 

서버 (백엔드):
Spring Boot를 기반으로 클라이언트와 서버 간의 통신을 처리합니다. 서버는 클라이언트로부터 전달받은 영상 데이터를 AI 모델로 보내고, 인식된 결과를 받아 다시 클라이언트로 응답합니다. 프론트엔드와 백엔드는 REST API를 통해 데이터를 주고받습니다.

AI 모델:

YOLO: 객체 탐지 모델을 사용하여 영상에서 손을 인식하고 해당 손의 위치를 추적합니다.

MediaPipe: 손의 움직임을 실시간으로 추적하고, 각 특징점을 추출합니다.

TensorFlow + LSTM: MediaPipe에서 추출한 손의 특징점 데이터를 학습된 LSTM 모델에 입력하여, 수어를 텍스트로 변환합니다.

데이터 흐름:

1.사용자는 카메라로 수어 영상을 촬영합니다.

2.프론트엔드는 영상을 서버로 전송합니다.

3.서버는 YOLO 모델로 손을 탐지하고, MediaPipe를 사용해 손의 움직임을 추적합니다.

4.추적된 데이터를 LSTM 모델에 입력하여 수어를 인식하고, 텍스트 결과를 생성합니다.

5.인식된 텍스트 결과는 클라이언트로 반환되어 화면에 표시됩니다.

    


  (오류로 인한 사진 수정중)

<hr>

### 만남 웹 사이트 프로젝트
2024.06.18 ~ 2024.07.04

사용한 기술 및 개발환경:
`Java`, `JavaScript`, `Html`, `Css` `JS`, `My Batis`, `Eclipse`, `JDK 17`

- **GitHub Repository** :(https://github.com/KoreanSecret/Web-site)
- **Youtube 시연영상** : (준비중)

  
- **세부기능**<br>
    -MyBatis 사용한 데이터베이스 연동<br>
    -MVC 패턴 사용한 백엔드 로직,비즈니스 로직, 프론트엔드 연결<br>
   
    
- **프로젝트 아키텍처**
프론트엔드 (클라이언트)
**JSP (JavaServer Pages)**를 사용하여 사용자 인터페이스를 구성하였습니다.<br>

사용자는 브라우저에서 만남 일정을 관리할 수 있으며, HTML과 CSS로 직관적인 화면을 제공하고, JavaScript로 동적인 기능을 구현하였습니다.<br>
서버 (백엔드)

Java Servlet을 이용하여 클라이언트 요청을 처리하고, JSP와 통신합니다.<br>
서버는 사용자의 만남 일정 등록, 삭제, 조회 등의 요청을 처리하며, MyBatis를 통해 데이터베이스와 상호작용합니다.<br>

데이터베이스 (DB)
MariaDB를 사용하여 사용자 정보, 만남 일정, 장소 등의 데이터를 저장하고 관리합니다.<br>
MyBatis는 SQL 쿼리를 자바 객체와 매핑하여 데이터베이스 접근을 효율적으로 처리합니다.<br>

데이터 흐름

1.클라이언트 요청:
사용자가 브라우저에서 만남 일정을 등록하거나 조회하는 요청을 보냅니다.

2.서버 처리:
Java Servlet이 클라이언트의 요청을 받아 필요한 비즈니스 로직을 처리한 후, MyBatis를 통해 데이터베이스와 통신합니다.

3.데이터베이스 통신:
MyBatis는 요청에 따라 SQL 쿼리를 실행하여 필요한 데이터를 가져오거나 업데이트합니다.

4.응답 처리:
서버는 처리 결과를 JSP로 전달하여 사용자에게 화면을 렌더링합니다.

5.클라이언트 응답:
브라우저에서 사용자는 만남 일정을 확인하거나 업데이트된 정보를 확인할 수 있습니다.




  ![image](https://github.com/user-attachments/assets/72fdd2ec-2eb0-41bb-9fa8-b070ffe8edac)


<hr>

<hr>

### 만남,호텔,식당 통합 웹 사이트(팀)
2024.07.05 ~ 2024.07.12

- **인원**: 3명

사용한 기술 및 개발환경:
`Java`, `JavaScript`, `Html`, `Css` `JS`, `My Batis`, `Eclipse`, `JDK 17`

- **GitHub Repository** :(https://github.com/KoreanSecret/Web-site)
- **Youtube 시연영상** : (준비중)

  
- **세부기능**<br>
    -DB 링크를 통한 테이블 공유<br>
    -MVC 패턴 사용한 백엔드 로직,비즈니스 로직, 프론트엔드 연결<br>
   
    
- **프로젝트 아키텍처**
   - NOT YET
    


  (준비중)


<hr>

### 이메일 서비스 사이드 프로젝트
2024.04.15 ~ 2024.04.25

사용한 기술 및 개발환경:
`Java`, `Oracle`, `Eclipse`, `JDK 17`

- **GitHub Repository** :([https://github.com/KoreanSecret/Web-site](https://github.com/KoreanSecret/emailproject))
- **Youtube 시연영상** : (준비중)
- ** : 사용자 간의 이메일 송수신 기능 제공하는 프로젝트
  
- **세부기능**<br>
    -이메일 송수신 기능<br>
    -Java Scanner 클래스를 이용한 콘솔 입력<br>
   
    
- **프로젝트 아키텍처**
 
사용자 입력 처리:
사용자가 콘솔을 통해 수신자 이메일 주소, 제목, 본문 내용을 입력합니다. 입력된 정보는 Java의 표준 입력(System.in)으로 처리됩니다.

이메일 구성:
Java의 javax.mail 라이브러리를 사용해 이메일 객체를 생성하고, 사용자로부터 입력받은 정보를 기반으로 이메일 메시지를 구성합니다.


이메일 전송:
전송 클래스를 통해 SMTP 서버로 이메일을 전송합니다. 이때, 사용자 인증을 위해 발신자의 이메일 주소와 비밀번호가 필요하며, 인증된 후 이메일이 발송됩니다.

결과 처리:
이메일이 성공적으로 전송되면 성공 메시지를, 실패하면 오류 메시지를 콘솔에 출력합니다.
    
- **문제**
  
    처음 도전한 프로젝트라 기능 구현이 부족함
        
- **해결**

  꾸준한 공부를 통한 기능 추가 완료
    


  ![image](https://github.com/user-attachments/assets/f999cb3b-c900-4336-90cb-149cd63c2525)


<hr>

## 📫 Contact 📫

- **Email**: tmdgns9392@gmail.com
- **Baekjoon**: [Seunghoon's Baekjoon Profile](https://www.acmicpc.net/user/asdf9392)


