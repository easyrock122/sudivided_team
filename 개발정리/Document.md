# 소분팀's Document
## ver200827

---------------------------
:mouse: 

찾기 쉽게 하기 위해서 변수, 함수, Model, CSS 로 구분함.

자신이 하는 부분의 각 파일 만들어 둔 다음 복사 붙여넣기 하는 것을 추천 드립니다👍

---------------------------

### 큰 틀
- #은 자신이 맡은 부분
  - ex) # 취향소개
- ####은 작성 일자, 즉 버전 정보
  - ex) #### 200823
- 변수, 함수, Model, CSS로 구분(##로 구분)
  - ex) ## 변수

### 변수
- 소분류 위치(####)
  - ex) #### settings.py
- 본내용은 아래와 같이 작성
```
- 변수명
  - 변수에 들어가는 값
```

### 함수
- 소분류 위치(####)
  - ex) #### settings.py
- 만약 Class 안에 있는 경우
  - ex) #### views.py - Class명
- 본내용은 아래와 같이 작성
```
- 함수명(인자) 
  - 무엇을 위한 건지 
  - 짧게 작성 여러줄 가능
```

### MODEL
```
- Model 이름
  - 필드이름.필드종류
  - 필드 길이
  - 그 밖의 필드 조건들을 쓰면됨
```

### CSS
- 소분류 위치(####)
  - ex) #### settings.py
- .이름, #이름, 이름
- : 무엇에 관한 건지 
```
- .navbar
  - 상단에 navbar
```

### 종합
```
# 취향소개
#### 200823


## 변수
#### settings.py
- 변수명
  - 내용
```