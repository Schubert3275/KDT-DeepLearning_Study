## 딥러닝

<details>
<summary>사용 교재</summary>

![](./images/파이토치%20딥러닝%20마스터.png)

</details>

### DAY01

---

<details>
<summary> 파이토치 소개 </summary>

> -   파이토치 가상환경 생성
> -   파이토치 버전 확인

</details>

---

| 파일명               | 내용                  |
| -------------------- | --------------------- |
| `DAY_01\check_pk.py` | 설치 패키지 버전 확인 |

### DAY02

---

<details>
<summary> 텐서 </summary>

> -   텐서 타입
> -   텐서 속성
> -   텐서 연산
> -   텐서 변환
> -   텐서 결합

</details>

---

| 파일명                      | 내용                |
| --------------------------- | ------------------- |
| `DAY_02\ex_tensor_01.ipynb` | 텐서 살펴보기       |
| `DAY_02\ex_tensor_02.ipynb` | 텐서 원소/요소 접근 |
| `DAY_02\ex_tensor_03.ipynb` | 행렬 곱셈           |
| `DAY_02\ex_tensor_04.ipynb` | 텐서 shape 변경     |
| `DAY_02\ex_tensor_05.ipynb` | 텐서 연결 & 결합    |

### DAY03

---

<details>
<summary> 인공신경망 </summary>

> -   퍼셉트론 원리
> -   퍼셉트론 증명

</details>
<details>
<summary> 다층 퍼셉트론 </summary>

> -   다층 퍼셉트론 소개
> -   다층 퍼셉트론 동작원리
> -   기울기 소실/폭주

</details>
<details>
<summary> 딥러닝 기초 </summary>

> -   선형회귀
> -   다중선형회귀
> -   로지스틱회귀
> -   다중분류

</details>

---

| 파일명                                    | 내용                    |
| ----------------------------------------- | ----------------------- |
| `DAY_03\ex_or_perceptron.ipynb`           | AND, OR, NAND, XOR 연산 |
| `DAY_03\ex_linearRegression.ipynb`        | 선형회귀 학습 예시      |
| `DAY_03\ex_load_data.ipynb`               | 이미지 처리             |
| `DAY_03\ex_wine.ipynb`                    | 와인 데이터 처리        |
| `DAY_03\ex_multi_linear_regression.ipynb` | 다중선형회귀 학습 예시  |
| `DAY_03\ex_logistic_reg.ipynb`            | 로지스틱회귀 학습 예시  |
| `DAY_03\ex_softmax_reg.ipynb`             | 다중분류 학습 예시      |

#### DAY03 실습과제

---

    1. wine 이진분류
    2. wine 회귀분석
    3. MNIST-Fashion 다중분류

### DAY04

---

<details>
<summary> 출력함수 </summary>

> -   sigmoid
> -   softmax

</details>
<summary> 이진분류 </summary>

> -   binary_cross_entropy
> -   OneHotEncoder

</details>
<summary> 다중분류 </summary>

> -   cross_entropy

</details>
<summary> 인공신경망 클래스 </summary>

> -   로지스틱회귀 모델 클래스

</details>

---

| 파일명                         | 내용                          |
| ------------------------------ | ----------------------------- |
| `DAY_04\ex_ac_function.ipynb`  | softmax(), sigmoid() 함수     |
| `DAY_04\ex_mini_test_01.ipynb` | 이미지 이진분류               |
| `DAY_04\ex_mini_test_02.ipynb` | 이미지 이진분류-OneHot        |
| `DAY_04\ex_nn.ipynb`           | 인공신경망 모델 클래스 만들기 |

#### DAY04 실습과제

---

    1. MNIST-Fashion 클래스 활용 다중분류

### DAY05

---

<details>
<summary> DATASET </summary>

> -   Dataset
> -   피쳐와 타겟(지도학습)의 묶음
> -   피쳐(비지도학습)의 묶음

</details>
<details>
<summary> LOADER </summary>

> -   DataLoader
> -   학습용
> -   검증용
> -   테스트용

</details>

---

| 파일명                               | 내용                 |
| ------------------------------------ | -------------------- |
| `DAY_05\ex_custom_dataset.ipynb`     | Dataset & DataLoader |
| `DAY_05\ex_iris_dataset_model.ipynb` | Dataset & DataLoader |

#### DAY05 실습과제

---

    1. MNIST-Fashion 클래스 활용 다중분류
