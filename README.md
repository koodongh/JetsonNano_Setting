# JetsonNano_Setting
젯슨나노초기설정


1. 환경설정
초기셋팅 :랜선을 먼저 찾기

초기셋팅변경
랜카드를 꼽았을때, 바로 셋팅이 되게 해야지 편하게 셋팅가능
모델 변경 :ipTIME N3U




전주출장 : 해당셋팅은 집에서 해야하나?
전화기ip랑은 상관없음
ip연결관련 어떻게 진행할지 셋팅다시생각해보기

간단하게 할수있는방법이 없을까?

Network Setting관련해 해당
1. 무선셋팅
일단은 유선을 먼저셋팅해야한다
pip install 환경설정이 따로 필요하기 때문이다.
보통 iptime driver에서 기기에 따른 드라이버를 설치하면 된다.
하지만, 젯슨나노 현재 리눅스 커널 버전 :4.9이기 때문에, 설치시오류가 난다
그래서 해당 블로그를 참고하여 설치하면 된다.
A1000mini같은 경우는 안된다. 처음 드라이버를 넣게 될때는?
바로 꼽았을때 연결되는 경우

iptime A2000U
https://blog.naver.com/yand2english/221194401281

sudo apt-get update
sudo apt-get upgrade
sudo apt-get install build-essential
sudo apt-get install git
git clone https://sanrath@mediatek_mt7610u_sta_driver_linux-64bit.git


블로그 참고 
https://blog.naver.com/yand2english/221194401281
ㅇ
ㅇ
LAN: 내부망연결-ip설정

랜추가 - 
랜정
VSCODE:


2. 카메라설정
초기셋팅: 노출설정-노출값높이기 

3. 코드추가

4. 초음파센서/IO셋팅
사용하는 방법 GPIO 설치하고
입력ㅇ
