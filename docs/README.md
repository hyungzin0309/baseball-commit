# 기능목록

* 랜덤숫자 생성
    * 1 ~ 9 중 서로 중복되지 않는 세 개의 수를 조합한 세 자리 수
* 사용자 입력
    * 세 자리 수 입력
    * 잘못된 입력 시 예외발생
        * 1 ~ 9 가 아닌 문자 입력
        * 세 자리가 아닌 수
        * 서로 중복되는 수 입력
* 숫자 검사
    * 랜덤숫자와 사용자 수를 비교하여 ball 과 strike 각각의 합 도출
        * 랜덤숫자에 포함되지만 자리수가 맞지 않는 수는 ball
        * 랜덤숫자에 포함되며 자리수가 일치하는 수는 strike
    * 결과를 사용자에게 출력
        * 출력 예시
            * ball = 1 && strike = 2
                * 1볼 2스트라이크
            * ball = 0 && strike = 1
                * 1스트라이크
            * ball = 2 && strike = 0
                * 2볼
            * ball = 0 && strike = 0
                * 낫싱
    * 3 strike 인 경우 사용자의 승리로 한 게임이 끝난다.
* 재시작
    * 사용자로부터 숫자를 입력받아 재시작, 혹은 종료
        * 1 입력시 재시작
        * 2 입력시 종료
    