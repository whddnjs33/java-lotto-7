# java-lotto-precourse

1. 구매 금액 입력받기
- 구매 금액을 입력받아 금액만큼 로또를 생성
- 입력이 양수,1000배수가 아닐경우 예외 처리 후 다시 입력 받음

2. 로또 당첨 번호 입력 받기
- 당첨 번호를 입력 받음
- 정수가 아님,1-45 사이 숫자가 아님, 중복일 경우 예외 처리 후 다시 입력 받음
- 입력 받은 문자열을 구분자(,)를 기준으로 나누어줌
- 문자열리스트를 정수리스트로 변환

3. 보너스 번호 입력 받기
- 보너스 번호를 입력 받음
- 정수가 아님,1-45 사이 숫자가 아님, 당첨 번호와 중복일 경우 예외 처리 후 다시 입력 받음
- 문자열을 정수로 변환

4. 로또 번호 일치 갯수 
- 당첨 번호와 보너스 번호가 로또와 일치하는 갯수를 구함
- 일치하는 갯수만큼 등수를 정함

5. 수익률 계산
- 1등에서 5등사이의 로또 개수를 구하고 등수에 맞는 금액으로 모두 더함
- 더한값을 구매 금액으로 나누어 수익률 구함
