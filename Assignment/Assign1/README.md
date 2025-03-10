# 분류별 운동을 하지 않는 이유 비율 조사

## 개요
1. Pandas 라이브러리를 활용하여 성별, 연령별, 학년별 운동하지 않는 이유에 대한 조사 데이터를 처리한다.
2. matplotlib의 Pie Chart를 이용하여 비율을 출력한다.

## 개발환경
+ **언어** : Python
+ **라이브러리** : Pandas, matplotlib.pyplot

## 구현내용
> **Category**
+ 운동을 할 충분한 시간이 없어서
+ 함께 운동을 할 사람이 없어서
+ 운동을 할 만한 장소가 없어서
+ 운동을 싫어해서
> **분류**
+ 성별 : 남/여 비율
+ 연령별 : 10대/20대/30대/40대/50대/60대 이상 비율
+ 학년별 : 중졸 이하, 고졸 이하, 대졸 이하, 대학원 이상 비율
> **알고리즘**
```
└─ read_csv()  //notExercise.csv
└─ DataFrame.columns()   //카테고리 분류
└─ DataFrame.loc[]       //성별, 연령별, 학년별 데이터 분류
└─ plt.subplot(2, 2)     //카테고리 수에 맞게 출력하기 위함
└─ plt.pie()             //분류별 비율을 확인하기 위해 파이 차트 사용
```

## 결과 예시
![파이](https://github.com/jwbastion/SeSAC/blob/main/MP/MP1/%EC%84%B1%EB%B3%84.png)
