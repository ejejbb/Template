# 통계학 4주차 정규과제

📌통계학 정규과제는 매주 정해진 분량의 『*데이터 분석가가 반드시 알아야 할 모든 것*』 을 읽고 학습하는 것입니다. 이번 주는 아래의 **Statistics_4th_TIL**에 나열된 분량을 읽고 `학습 목표`에 맞게 공부하시면 됩니다.

아래의 문제를 풀어보며 학습 내용을 점검하세요. 문제를 해결하는 과정에서 개념을 스스로 정리하고, 필요한 경우 추가자료와 교재를 다시 참고하여 보완하는 것이 좋습니다.

4주차는 `2부-11.데이터 전처리와 파생변수 생성`를 읽고 새롭게 배운 내용을 정리해주시면 됩니다.

[실습코드](https://github.com/c-karl/DA_DS_Book001)를 참고하여 학습해주세요.


## Statistics_4th_TIL

### 2부. 데이터 분석 준비하기
### 11.데이터 전처리와 파생변수 생성



## Study Schedule

|주차 | 공부 범위     | 완료 여부 |
|----|--------------|----------|
|1주차| 1부 ~p.79    | ✅      |
|2주차| 2부 ~p.120   | ✅      | 
|3주차| 2부 ~p.202   | ✅      | 
|4주차| 2부 ~p.299   | ✅      | 
|5주차| 3부 ~p.356   | 🍽️      | 
|6주차| 3부 ~p.437   | 🍽️      | 
|7주차| 3부 ~p.542   | 🍽️      | 
|8주차| 3부 ~p.615   | 🍽️      | 
|9주차|데이터 분석 실습| 🍽️      |

<!-- 여기까진 그대로 둬 주세요-->

# 11.데이터 전처리와 파생변수 생성

```
✅ 학습 목표 :
* 데이터 전처리 방법을 이해하고 적용할 수 있다.
* 데이터 변환과 가공 기법을 학습하고 활용할 수 있다.
* 모델 성능을 향상시키는 데이터 가공 기법을 이해하고 적용할 수 있다.
* 데이터의 유사도를 측정하는 다양한 거리 측정 방법을 이해하고 활용할 수 있다.
```
<!-- 새롭게 배운 내용을 자유롭게 정리해주세요.-->



<br>
<br>

# 확인 문제

## 문제 1. 데이터 전처리

> **🧚 한 금융회사의 대출 데이터에서 `소득` 변수에 결측치가 포함되어 있다. 다음 중 가장 적절한 결측치 처리 방법은 무엇인가?   
1️⃣ 결측값이 포함된 행을 모두 제거한다.  
2️⃣ 결측값을 `소득` 변수의 평균값으로 대체한다.  
3️⃣ `연령`과 `직업군`을 독립변수로 사용하여 회귀 모델을 만들어 `소득` 값을 예측한다.  
4️⃣ 결측값을 보간법을 이용해 채운다.**

> **[데이터 특징]**     
    - `소득` 변수는 연속형 변수이다.  
    - 소득과 `연령`, `직업군` 간에 강한 상관관계가 있다.  
    - 데이터셋에서 `소득` 변수의 결측 비율은 15%이다.

<!--결측값이 무작위로 발생한 경우인지(MCAR, MAR, NMAR) 판단하고, 변수 간 관계를 고려해보세요.-->

```
여기에 답을 작성해주세요!
```

## 문제 2. 이상치 처리

> **🧚 한 부동산 데이터에서 `주택 가격` 변수의 분포를 살펴본 결과, 대부분의 가격이 2억~5억 원 사이에 분포하지만, 100억 원 이상인 데이터가 일부 존재했다.**

> **🔍 Q1. 이러한 `주택 가격` 데이터를 이상치로 판단할 수 있는 방법을 한 가지 이상 서술하세요.**

```
여기에 답을 작성해주세요!
```

> **🔍 Q2. 이상치를 처리하는 방법에 대해 고민해보고 어떤 방법이 가장 적절할지 서술해주세요.**

<!-- 정해진 답은 없습니다. 자유롭게 작성해주세요-->

```
여기에 답을 작성해주세요!
```

## 문제 3. 데이터 스케일링

> **🧚 머신러닝 모델을 학습하는 과정에서, `연봉(단위: 억 원)`과 `근속연수(단위: 개월)`을 동시에 독립변수로 사용해야 합니다. 연봉과 근속연수를 같은 스케일로 맞추기 위해 어떤 스케일링 기법을 적용하는 것이 더 적절한가요?**

<!--표준화와 정규화의 차이점에 대해 고민해보세요.-->

```
여기에 답을 작성해주세요!
```

## 문제 4. 파생변수 생성

> **🧚 한 온라인 쇼핑몰에서는 고객의 구매 패턴을 분석하기 위해 기존 데이터에 파생변수를 추가하려고 한다.**

> 원본 데이터의 컬럼명: `총구매금액`, `방문횟수`, `최근 방문일`, `회원가입일`

> **🔍 Q1. 원본 데이터의 변수를 참고하여 의미 있는 파생 변수의 예시를 하나 이상 들어주세요.**

<!-- 정해진 답은 없습니다. 자유롭게 작성해주세요-->

```
여기에 답을 작성해주세요!
```

> **🔍 Q2. 파생변수를 만들 때 주의해야 할 점을 설명하세요.**

```
여기에 답을 작성해주세요!
```


## 문제 5. 클래스 불균형 해결

> **🧚 한 보험사에서 고객의 `사기 보험 청구 여부(0/1)`를 예측하는 분류 모델을 만들었다. 하지만 사기 청구 비율은 전체 데이터의 2%에 불과하다.**

> **🔍 Q1. 데이터 불균형 문제가 발생하면 모델 성능에 어떤 영향을 미칠 수 있나요?**

<!--사기 탐지 모델에서 발생할 데이터 불균형으로 인한 모델 성능에의 영향에 대해 구체적으로 고민해주세요.-->

```
여기에 답을 작성해주세요!
```

> **🔍 Q2. 이 문제에서 적절한 해결 방법을 고민하여 서술해주세요.**

<!-- 정해진 답은 없습니다. 자유롭게 작성해주세요-->

```
여기에 답을 작성해주세요!
```

## 문제 6. 데이터 거리 측정

> **🧚 한 추천 시스템에서 고객 간 유사도를 측정하려고 합니다. 고객의 `구매 내역`을 벡터로 변환한 후, 두 고객이 얼마나 유사한지를 측정하려면 유클리드 거리와 코사인 거리 중 어떤 거리 측정 방법이 더 적절한가요?**

<!--유클리드 거리는 벡터의 크기(절대적 차이)를 고려하고, 코사인 유사도는 방향(패턴)을 고려합니다.-->

```
여기에 답을 작성해주세요!
```


### 🎉 수고하셨습니다.