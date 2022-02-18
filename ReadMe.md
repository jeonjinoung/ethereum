#이더리움 수업 내용 정리정돈#
Cancel changes
1화 크팁토좀비 시즌1 및 ethereum 사이트 가스 내용 전달

2화 크립토좀비 시즌2

- 숙제 : 크립토좀비 1 각 이미지변경 숫자 변경시 내용변경확인

3화 크립토좀비 시즌2 복습 및 어려운점 재확인

4화 Ethereum Remix solidity 다운로드
크립토좀비 샘플코드 가져와서 저장하고
솔리티버전 문제생김
set compiler version 0.4.19로 바꿈(맞는 버전으로 바꿈)
compiler 누르면 컴파일 된다. = 컴파일이란 ? =>

npm install -g truffle해줘야된다 이때 !! - python이랑 node는 최신버전으로 깔려있어야된다.
npx truffle init을 하면 truffle이 생겨남

- ethereum brawoser에서 잠시 이전에 했던것을 desploy를 통하여 디테일을 debug로 확인할 수 있다.

Geth 맘춤 다운로드
- https:ethereum.github.io/downloads/

- cmd창 열기
- cd "geth 경로" => cd "C:\Program Files\Geth"
- geth --syncmode "light" (주위의 피어도 찾고 여러가지 일을 행함)

- cmd창 하나더 열기
- cd "geth 경로" => cd "C:\Program Files\Geth"
- dir 파일 확인 우분투 ll이랑 비슷함

- 대화용 콘솔창 열기 2가지방법
- geth console이라는것을 칠때는 cmd창이 동시에 실행되고있지않을때 
- geth attach ipc:\\.\pipe\geth.ipc  // 부가적으로 ctrl D를 누르면 나갈수있다고한다.
- 버전정보 표시 = web3.version
- web3.version.api = "0.20.1" 항목별로확인할수 있다.
- var apiVersion = web3.version.api => console.log(apiVersion) => 0.20.1
- net = 연결상태확인 = web3 net (web은 생략가능)
- admin.nodeInfo = 내노드에 대한정보를 가져오는 명령어
- admin.peers = 나랑연결되어있는 피어들에대한 정보
- eth.blockNumber = 최신블럭확인
- eth.getBlock(eth.blockNumber) = 마지막블록에대한 정보를 볼수 있다.
- eth.getTransactionFromBlock(eth.blockNumber, 0) 가장 첫번째의 트렌잭션의 블럭을 확인한다.
-    = 이더단위변환 웨이를 이더로 이더를 웨이로 웨이금액을 특정단위로 변환할 수 있습니다.
- var latestBlockNum = eth.blockNumber
- eth.getTransactionFromBlock(latestBlockNum, 0) = 제일 첫번째블록을 가져올수 있다.

5화 Ethereum Blog Check or resson

주말 공부 크립토좀비 예습 및 복습
22.02.13
오늘은 ethereum을 좀더 잘써보자

22.02.14
스마트 컨트렉트 배포하기
MetaMask(메타마스크)

22.02.15
크립토좀비 시즌3
예습복습하기

22.02.16
크립토좀비 시즌4
예습복습

22.02.17
크립토좀비 시즌4
예습복습 및 스마트컨트렉트 연결하기

22.02.18
크립토좀비 시즌5 혼자보기
투표권자 만들고 html연결
해보기
