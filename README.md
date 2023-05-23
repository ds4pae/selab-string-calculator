# SE-LAB Calculator

### 1. 요구사항
> 추가적인 기능 구현 환영! 물론, 필수적인 구현은 무조건~
1. 덧셈, 뺄셈, 나눗셈, 곱셈이 가능한 계산기를 구현합니다.
2. 입력은 `30 + 20 / 2 * 4` 순으로 받으며, 연산자 우선순위 없이 앞에서 부터 계산을 진행합니다.=
3. 출력은 `100`으로 나옵니다.

---
###  2. 구현 소개
- GetInputValue : input값을 얻어내는 클래스
- CheckNumOperator : 연산자와 비연산자를 구분하는 클래스
- Calc : 구분한 연산자와 비연산자를 Operator클래스를 이용해 결과값을 도출해내는 클래스
- Operator : 연산자를 Enum으로 저장해 입력받은 연산자와 비교하여 계산하는 클래스
- PrintResult : 결과값을 출력하는 클래스
