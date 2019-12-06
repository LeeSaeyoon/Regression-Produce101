# [회귀 분석] 프로듀스 101 연습생들의 최종 점수 및 데뷔 예측
: main cause of debut of produce 101 trainee

프로듀스 101에서 연습생들의 데뷔 요인을 알아보고 최종 데뷔하게 될 연습생들이 누구일지 예측해보기
![title](./image/title.PNG)

## 목적
회귀 분석을 통해서 35인에서 20인으로 생존과 방출이 일어나는 과정(3차 순위 발표식)에서 과연 어떠한 요인이 20인의 등수(득표수)에 영향을 주는지, 또한 득표수와 어떻게 관련이 있는지 회귀 모형을 만들어 본다. 이를 통하여 최종 11인이 누가 될 것인지 20인을 모형에 적용하여 예측 해 보는 것을 목표로 한다.

## 데이터
- I(지시변수): 리더 및 센터 경험 유무(有:1, 無:0)
- X1(등급): 연습생들의 실력을 나타내는 척도 (A:5, B:4, C:3, D:2, F:1)
- X2(중간 누적 득표수): 1차, 2차 순위 발표식에서 받은 득표수
- X3(동영상 조회수): 네이버 TV 캐스트의 공식 홈페이지에 올라오는 동영상 조회수
- X4(동영상 하트수): 네이버 TV 캐스트의 공식 홈페이지에 올라오는 동영상 하트수
- X5(분량): 프로그램 내에서 얼굴이 비춰진 시간 (단위: 초)
- X6(매출액): 각 연습생들의 소속사의 매출액 (단위: 백만 원)
- Y(반응변수): 3차 순위 발표식에서 받은 득표수

(데이터 기준) 동영상 조회수 및 하트수: 2017년 11월 9일 17:35 기준, 매출액: 2016년 1~4분기 총 매출액
(출처) 매출액: dart(전자공시시스템)

## 자료 설명
매출액 자료의 경우에는 기획사들 가운데에서도 매출이 공개되어있는 곳도 있지만 아닌 곳도 있었다. 그러나 기획사의 규모를 나타내는 매출도 35인의 득표수에 중요한 영향을 줄 것이라고 예상하였기 때문에, 자료를 두 개로 나누었다. 하나는 설명변수 6개(x1, x2, x3, x4, x5, I)이며 자료의 개수를 총 35개로 설정하였고, 나머지 하나는 설명변수 7개(x1, x2, x3, x4, x5, x6, I)이며 자료의 개수는 기획사 매출액 자료가 존재하는 24개로 설정한다. 이 때, 전자의 자료를 자료 1, 후자의 자료를 자료 2라고 한다.

## 분석 과정
### 1. 단순 회귀 분석

### 2. 다중 회귀 분석

### 3. 모형 진단 -> 변수 변환 -> 다중 공선성 확인 -> 변수 선택 (반복)

### 4. 이상점 검정

### 5. 최종 모형

## 결과 및 결론
