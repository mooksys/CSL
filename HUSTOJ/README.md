#20.10.19   
#프로그래밍언어 기초100제 시리즈를 쉽고 빠르게 설치해서 운영할 수 있도록 하기 위한 스크립트 파일과 소스코드를 저장하고 배포하는 용도입니다.    
***

#Prerequisite  
#아래와 같은 방법으로 Ubuntu 20.04 LTS Desktop/Server(AWS) 운영체제에 HUSTOJ를 먼저 설치해야 합니다.   

<https://github.com/zhblue/hustoj>
<pre><code>
wget https://github.com/zhblue/hustoj/raw/master/trunk/install/install-ubuntu20.04.sh

sudo bash install-ubuntu20.04.sh
</code></pre>

***
#기초100제의 모든 내용들은 중고등학교 정보(컴퓨터) 선생님들에 의해서 만들어졌습니다.   
#각종 사교육 및 협의되지 않은 영리 목적의 사용을 금지합니다.   
#중고등학교 정보 선생님들은 정규수업, 방과후수업, 특별활동 등 학생들 교육을 위해 자유롭게 사용할 수 있습니다.   

#설치 스크립트 파일 다운로드 및 설치 명령어 실행
<pre><code>
wget https://raw.githubusercontent.com/melongist/CSL/master/HUSTOJ/csl100v00.sh

sudo bash csl100v00.sh
</code></pre>

------
#kindeditor 한글 설정
- /home/judge/src/web/admin/kindeditor.php

#빈칸 채우기형, 코드 제한형 문제 처리
- /home/judge/src/web/submit.php

#메시지 설정 추가
- /home/judge/src/web/admin/msg.txt

#아래쪽 2개 큐알 코드 삭제 및 CSL 링크 삽입
- /home/judge/src/web/template/bs3/js.php

#이미지 파일 복구
- /home/judge/src/web/upload

#채점데이터 폴더 복구
- /home/judge

#관리용 phpmyadmin 설치

#/home/judge/src/web/include/db_info.inc.php 설정 파일 수정
  - OJ 이름 변경
  - 한국어 환경 변경
  - 보안 VCODE 설정
  - 회원가입 불가 설정
  - 틀린 결과 확인 설정
  - 서버 한국 시간 설정
