# 자동차 경주

## 기능 구현 목록

- 자동차 이름 입력 받기
  - 자동차 이름 입력(쉼표로 구분, 5자리 이하)
  - 유효성 검증
    - 쉼표로 구분
    - 자리 이하
    - 예외 발생 시, 다시 입력


- 시도 횟수 입력 받기
  - 시도 횟수 입력
  - 유효성 검증
    - 1이상의 정수로 입력
    - 예외 발생 시, 다시 입력


- 자동차 전진 구현
  - 0-9 사이에서 랜덤 발생된 값이 4 이상일 경우 전진
  - 시도 횟수만큼 전진 후 우승자 선정
  - 공동 우승 가능


- 결과 출력
  - 실행 결과 출력
  - 자동차 이름과 전진 거리 출력
    - ex) pobi : ---
  - 최종 결과 출력
    - ex) 최종 우승자 : pobi, jun