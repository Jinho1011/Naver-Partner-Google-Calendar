# 네이버 예약 관리자 - 구글 캘린더 연동
````python
    naver_login_info = {
        "id": '',
        "pwd": ''
    }
````
네이버 계정 정보를 등록한 뒤, 일정을 등록하려는 구글 계정으로 로그인하여
credentials.json을 받아 naver.py가 위치한 폴더로 이동한다.

# Window Scheduler 등록
https://handyhelper.tistory.com/92
위 링크를 참고하여 naver.py를 시작프로그램에 등록하여 학원PC가 부팅되면 자동으로 실행되게끔 한다.