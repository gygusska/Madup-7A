<div align='center'>

# 원티드 프리온보딩 매드업 7A
  
### [배포주소](https://madup-7a.netlify.app/)

데이터 대시보드와 광고관리 페이지
  
</div>

<div align="center">

|페이지 이동|날짜 범위 선택|
|:-:|:-:|
|![페이지 이동](https://user-images.githubusercontent.com/78616893/170398051-198b3dd1-d5bc-4bd8-a70a-89cf4b50d64f.gif)|![ezgif com-gif-maker (11)](https://user-images.githubusercontent.com/78616893/170398206-720847d7-d2b4-4e85-9420-40fde00e2ea5.gif)|

|튤팁 제공|일간 주간 선택|
|:-:|:-:|
|![ezgif com-gif-maker (12)](https://user-images.githubusercontent.com/78616893/170398496-a12b0edc-0ffa-4c3e-8087-f45a13f1a424.gif)|![ezgif com-gif-maker (13)](https://user-images.githubusercontent.com/78616893/170398751-05625fcb-026c-4c1f-84ee-91f5ca772129.gif)|


</div>


## 👬 **팀원**

- 남효현, 양이진, 이득규, 한지선

<br>

## 📅 **개발 기간**

- 기간: 2022년 5월 23일 ~ 2022년 5월 25일

<br>

## 🔧 **기술스택**

- Typescript, React, Sass, Recoil

<br>

## **💻 설치 및 실행 방법**

1. yarn 설치

```
 npm i yarn
```

2. 레포지토리 클론

```
git clone https://github.com/wanted-pre-onboarding-7team/Madup-7A.git
```

3. dependencies 설치

```
yarn
```

4. 실행

```
yarn start
```

<br>

##  📝 **기능 구현 목록**

### Date Picker

- [x] 날짜 범위 선택 기능
- [x] 적용 버튼 클릭으로 시작과 끝 날짜 적용

<br>

### 통합 광고 현황

- [x] Data Card

  - [x] 날짜 범위 내 데이터 합산 값 표기

  - [x] 이전 데이터와 비교하여 증감분을 표기

    ex) 사용자가 날짜 범위 3일을 선택했다면, 이전 3일치 데이터와 비교하여 증감분을 나타냄

- [x] Data Dropdown

  - [x] ROAS, 광고비, 노출 수, 클릭 수, 전환 수, 매출 필터 적용

  - [x] 주간, 일 별 필터 적용

- [x] Data Chart

  - [x] Chart 생성, x, y axis tooltip custom
  - [x] 데이터 필터에 맞는 차트 적용

<br>

### 매체 현황

- [x] Data Table
  - [x] Array.reduce method와 Object.keys를 활용해 표 데이터 가공
  - [x] data 필터를 통해 기간 조회
  - [x] 기존 변수를 활용한 정확한 수식 적용

<br>

### 광고관리

- [x] Ads Filter 

  - [x] 드롭 다운 클릭 시 선택 창 노출 및 `전체(기본값)`, `진행 중`, `중단됨` 3가지 상태 값 제공 

  - [x] 상태 값 선택 시 해당하는 광고만 보이도록 필터 

  - [x] react-use의 `useClickAway`를 활용하여 드롭 다운 외부 클릭 시 함수 트리거 

- [x] Ad Card 
  - [x] 요구사항에 맞는 데이터 출력을 위한 데이터 전처리 함수 구현 

- [x] etc
  - [x] 중복 코드 최소화를 위한 Ad Card & Button 컴포넌트 분리 및 커스텀 스타일 구현



### Loading 

- [x] 리액트 내장 함수인 Lazy & Suspense를 활용한 지연 로딩 구현
