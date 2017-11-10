# IoT Home 만들기 강의차시 계획서

# 아두이노로 IoT Home 서비스 만들기

## 교육자
* 최찬환
* 유건희
* 박성민

## 예상 난이도
★★★☆☆ (중)

## 교육 대상
임베디드 코딩과 IoT에 관심이 있는 중학교 2학년 ~ 고등학교 3학년

## 수업 방식
쉽고 재미있는 활동을 하면서 이론을 공부하자

## 강의 일정
* 소요시간 : 3시간
* 교육장소 : 서울창조경제혁신센터

### 1차시
`“IoT를 적용시킬 전등을 만들어 보자”`

C언어를 이용한 아두이노 LED를 스위치로 점등

#### 수업 최종 목표
C언어의 작동 방식, 아두이노의 setup()함수를 이해하고 아두이노 기본 회로, 디지털 및 아날로그 아웃풋에 대한 이해를 한다. 

### 2차시
`"전등 밝기를 바꿔보자"`

C언어 변수와 연산자, loop함수를 활용한 아두이노 LED밝기 조절
밝기 조절을 하며 그 값을 변수를 이용해 저장하고 연산자를 이용해 그 값을 바꿔본다.
이 부분에 변수를 상자에 비유를 하고 차후에 쓸 다양한 센서들에 필요함을 강조할 방침이다.

#### 수업 최종 목표
C언어의 변수를 이해하고 loop()함수를 활용하여 아두이노 아날로그 output을 조절할 수 있다.

### 3차시
`"멋진 전등을 만들어 보자"`

스위치를 통해(조건문 이용) 점등 여부를 수정하고, 반복문을 통해 켜지는 LED의 개수를 제어할 수 있는 전등을 만들 수 있다.

#### 수업 최종 목표
스위치 및 가변저항을 통해 디지털 인풋과 아날로그 아웃풋을 배우고, 조건문 & 반복문을 통해 led를 제어할 수 있다.

### 4차시
`"도둑 경보를 만들어 보자"`

1, 2, 3 차시 때 배웠던 변수, 반복문, 조건문을 사용하여 적외선 센서 읽어 가까이 오면 LED점등, 피에조 부저 울리기 

#### 수업 최종 목표
C언어의 기본문법들을 복습하고 다양한 센서, 모듈을 이용한다.

### 5차시
`"진짜 전등을 조절해보자"`

아두이노 조도센서값을 읽어 서보모터를 작동시키고 그를 이용해 형광등을 조절해 보기

#### 수업 최종 목표
C언어 기본문법 복습하고 다양한 센서, 모듈들을 이용한다.

### 6차시
`"네트워크에 연결해 보자"`

아두이노 Wi-Fi를 이용하여 대표적인 사이트에 접속해보자 

#### 수업 최종 목표
HTTP 기본 개념이해 Wi-Fi 모듈 작성 방식 이해한다.

### 7차시
`“API서버와 네트워크를 연결해 보자”`

아두이노 Wi-Fi를 이용하여 설리번이 제작한 API 서버에 값 전송과 데이터 읽기를 해보자


#### 수업 최종 목표
API서버 개념 이해(간단히 GET, POST의 차이 까지) API서버와 네트워크 연결

### 8차시
`“IoT Home을 만들어 보자”`

아두이노를 이용하여 직접 필요하다고 느끼는 IoT 서비스를 계획하고 직접 틀을 짠다.

#### 산출물을 지정하는 방도
실제 가전제품의 전원을 직접 릴레이로 조절하는 것은 위험할 수 있기 때문에
가능하면 배제하고 피치 못할 경우 설리번의 각별한 주의가 필요할 것으로 보인다.
기타 고려사항은 이와 같다
1. 아두이노와 API서버 두가지 만을 활용하는 범위
2. 아두이노에서 제공하는 5V보다 높은 전압은 될 수 있으면 피하는 범위
3. 제공하는 부품 및 센서 내에서 처리할 수 있는 범위



#### 수업 최종 목표
IoT Home 서비스를 계획 설계할 수 있고 기본적인 구현을 시작한다

### 9차시
`“IoT Home을 만들어 보자”`

IoT서비스에 필요한 센서, 모듈을 추가적으로 배운다.


#### 수업 최종 목표
IoT Home 서비스에 필요한 다양한 센서를 배운다.

### 10차시
`“IoT Home을 만들어 보자”`

IoT 서비스 본격적인 개발을 시작한다.

#### 수업 최종 목표
Home 서비스를 거의 완성 시킨다.

### 11차시
`“IoT Home을 만들어 보자”`

아두이노와 API 서버를 연결한다

#### 수업 최종 목표
IoT 에서 API 서버와의 연결이 어떻게 진행되는지에 대해 안다. 

### 8 ~ 11차시에 대한 멘토링 방식
강의를 수강하는 인원의 1/3에 대해 멘토 한 명씩 붙어서 프로젝트를 진행한다.
해당 인원 1/3은 같은 프로젝트를 진행하며 필요한 장비와 라이브러리에 대한 교육 그리고 API서버에 대한 작업을
9차시 때 부터 차근차근 진행한다.
