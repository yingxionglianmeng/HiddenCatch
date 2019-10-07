# HiddenCatch

-------------
## 1. 목차
```
.틀린 그림 찾기
├── 1.목차
├── 2.개요
├── 3.특징
├── 4.사용법
|   ├── 4.1.개발 환경 & 개발 툴
|   └── 4.2.실행 방법
|       ├── 4.2.1 실행 환경 세팅
|       └── 4.2.2 실행
└── 5.스크린샷
    ├── 5.1.로그인 화면
    ├── 5.2.메인 화면
    ├── 5.3.랭킹 화면
    ├── 5.4.게임 화면
    └── 5.5.결과 화면
```



## 2. 개요
 - **JAVA**로 구현한 **틀린 그림 찾기**입니다. 
 - 자바 스윙을 이용해 gui의 마우스 클릭 좌표 값을 입력 받아 결과를 출력하도록 구현하였습니다.


 
## 3. 특징
- 로그인을 완료해야 메인 화면을 띄우도록 하였습니다.
- 입력된 아이디와 패스워드를 HashMap에 저장되어 있는 아이디와 비밀번호와 비교하여 동일하면 로그인이 되도록 처리하였습니다.
- 각 버튼에는 마우스 오버 효과를 넣었으며 게임시작, 랭킹, 나가기 기능을 구현했습니다.
- 두 가지의 그림을 출력하여 서로 다른 부분을 클릭 시 빨간색 동그라미가 나타나면서 맞춘 문제 카운트가 올라가며 틀리면 목숨(하트)이 깎이도록 했습니다.
- 스레드를 이용해 설정해놓은 시간을 1초씩 감소하는 타이머로 0초가 되면 게임이 종료되고 맞춘 문제가 기록되도록 하였고 Swing JProgressBar를 이용해 타이머에 맞춰 오른쪽에서 왼쪽으로 서서히 줄어들도록 하였습니다.
- 몇 문제를 맞췄는지 알려주고 랭킹에 등록된 최고 점수와 비교하여 최고 점수일 때 랭킹 스코어에 등록되도록 하였습니다.
- 시간 안에 모든 문제를 맞추지 못해 나오는 화면, 하트가 모두 감소하여 실패한 화면, 모든 문제를 맞춰 나오는 화면 3가지로 구성하도록 했습니다.



## 4. 사용법
### 4.1. 개발 환경 & 개발 툴
- Programing Language :　Java 8 (Swing, Thread 활용) 
- OS : Windows 10
-----------------------------------------------------------------------------
- Tool : Eclipse 
- Graphic Tool : Adobe Photoshop CC


### 4.2. 실행 방법
#### 4.2.1 실행환경 세팅
```
# 1. Eclipse에 해당 프로젝트를 import 합니다.
# 2. src/Game 폴더에서 GameLogin.java 파일을 확인하시기 바랍니다. 
- 회원정보가 HashMap에 저장되어있기 때문에 Join메소드를 확인하시고 수정하시면 됩니다.
# 3. 이렇게 하면 세팅은 완료됩니다.
```
#### 4.2.2 실행
```
# 1. 설정이 완료되면 GameLogin.java가 열려있는 상태에서 RUN 하시면 됩니다.
# 2. 로그인 후 메인화면이 나오면 게임시작 버튼을 눌러 게임을 즐기시면 됩니다.
```


## 5. 스크린샷

### 5.1.로그인 화면
 ![로그인](./screenshot/hc1.PNG)
 -------------

### 5.2. 메인 화면
 ![메인](./screenshot/hc3.PNG)
 -------------
 
 ### 5.3. 랭킹 화면
 ![랭킹](./screenshot/hc4.PNG)
 -------------
  
 ### 5.4. 게임 화면
 ![게임](./screenshot/hc5.PNG)
 -------------
  
 ### 5.5. 결과 화면
 ![결과](./screenshot/hc8.PNG)
 -------------

-----------------------------------------------------------------------------
# 감사합니다!
