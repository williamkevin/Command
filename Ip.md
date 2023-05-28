# Ip

- Packet INternet Groper(ping): 컴퓨터 네트워크 상태를 점검, 진단하는 명령어 : ping [ip address]
- Request timeout -> 패킷이 목적지에 도착하지 못했음
- ICMP(internet control message protocol)는 호스트서버와 인터넷 게이트웨이 사이에서 메세지를 제어하고 오류를 알려주는 프로토콜인데 ping 이 이를 사용합니다. ping은 주소사이를 오가는 ICMP 패킷을 잡아서 확인합니다.
- 핑 전송에 성공하면 데이터의 크기와, IP주소, 패킷이 전송되는데 걸리는 시간을 보여준다. 중간중간 핑 응답에 실패하면 Request timeout이 뜬다. Request timeout이 뜨는 이유는 패킷이 목적지에 도착하지 못했음을 의미한다. ICMP 패킷은 UDP 처럼 무조건 목적지에 도착하지 않기 때문에 이 같은 실패가 나타난다.
- ping 명령은 초당 하나의 데이터그램을 전송하며, 수신된 모든 응답에 대해 하나의 출력 행을 인쇄합니다. ping 명령은 왕복 시간과 패킷 유실 통계를 계산하며, 완료 시에 간략한 요약을 표시합니다. ping 명령은 프로그램의 제한시간이 초과되거나 SIGINT 신호를 수신하면 완료됩니다. Host 매개변수는 유효한 호스트 이름 또는 인터넷 주소입니다.
