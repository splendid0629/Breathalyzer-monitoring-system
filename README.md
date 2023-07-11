# Breathalyzer-monitoring-system
음주측정기를 모니터링하기위한 웹
프레임워크 : django, DB : mySQL(사용자정보), firebase(음주측정 영상, 음주측정 데이터)
mySQL은 현재 로컬, firebase는 api key추가필요 

pip install django
pip install djangorestframework

mysql 설치
drunk_driving_management라는 DB 만들고 my_setting.py에 본인의 계정과 비밀번호로 변경

테이블 생성 마이그레이션
python manage.py migrate

메인 sample.html
사용자상세 페이지 detail.html
