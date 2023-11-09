# 데이터셋 생성 방법

## 1. 터미널에서 명령

```
git clone git@github.com:Mixed-CSE/data-generator.git
```

```
cd data-generator
```

```
npm i
```

## 2-1. 집중하는 표정 데이터 생성하기

```
npm run-script dev 3002
```

http://localhost:3002 접속 <br>
-> API Key 입력 <br>
-> 'Facial Expression' 클릭하고 집중하는 표정 짓기 <br>
-> 뒤로가기 누르면 자동으로 데이터 파일 다운로드

## 2-2. 집중하지 않는 표정 데이터 생성하기

```
npm run-script dev 3001
```

http://localhost:3001 접속 <br>
-> API Key 입력 <br>
-> 'Facial Expression' 클릭하고 집중하지 않는 표정 짓기 <br>
-> 뒤로가기 누르면 자동으로 데이터 파일 다운로드
