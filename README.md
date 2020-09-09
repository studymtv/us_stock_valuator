# us_stock_valuator
1. How to configure
  - Install Chrome
  - Install Chrome driver (https://chromedriver.chromium.org/home)
  - Install python3 (latest is better)
2. How to run
  - python3 us_run.py <ticker file> <itooza id> <itooza password>
  - ticker file
   . csv file
   . ticker, stock name --> ticker is important, stock name is just used for result
   . eg. see "ual.csv"
3. Using web scrapping from us.itooza.com
4. Add your naver address and password to send_email() if you want to receive the result automatically.
  https://github.com/gourri/us_stock_valuator/blob/master/us_run.py
  
===========
   
1. 설정
  - 크롬 브라우저 설치
  - 크롬 드라이버 설치 (https://chromedriver.chromium.org/home 또는 https://blog.naver.com/song_sec/221752226329)
  - 파이썬3 설치 (최신일수록 좋음)
2. 실행
  - python3 us_run.py <티커 파일> <itooza id> <itooza password>
  - 티커 파일
    . csv 파일 형태
    . 티커, 종목명 --> 티커는 정확해야 함. 종목명은 결과 출력용으로만 사용
    . 예제: "ual.csv" 파일 내용 참조
3. us.itooza.com 사이트의 정보를 사용함
4. 자동으로 결과를 이메일로 받고 싶다면, 아래 코드의 send_email 함수에 네이버 이메일 주소와 암호를 입력해 두면 됨
  https://github.com/gourri/us_stock_valuator/blob/master/us_run.py
