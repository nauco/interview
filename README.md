# interview

프로토콜이란?

프로토콜은 컴퓨터 같은 전자 장치들 간에 데이터를 전송하기 위해 정의한 일련의 규칙(set of rules)이나 절차(procedures), 표준이다.   
Protocol is a set of rules or procedures for transmitting data between electronic devices, such as computers.

컴퓨터가 정보를 교환하기 위해서는 정보의 구조화 방식과 각 측이 정보를 주고받는 방식에 대한 미리 정의 된 합의가 있어야 한다.   
In order for computers to exchange information, there must be a preexisting agreement as to how the information will be structured and how each side will send and receive it.

프로토콜이 없다면 송신 컴퓨터는 데이터를 8비트 패킷으로 전송하고, 수신 컴퓨터는 16비트 패킷으로 전송하는 경우를 들 수 있다.   
Without a protocol, for example, a tansmitting computer could be sending its data in 8-bit packets while the receiving computer might expect th data in 16-bit packets.

아마도 가장 중요한 컴퓨터 프로토콜은 컴퓨터 간의 네트워킹 통신을 구현하기 위한 일련의 지침인 OSI(Open Systems Interconnect)일 것이다.   
Perhaps the most important computer protocol is OSI, a set of guidelines for implementing networking communications between computers.

대표적인 인터넷 프로토콜로는 TCP/IP, HTTPS, SMTP, DNS 등이 있다.   
Among the most important sets of Internet protocols are TCP/IP, HTTPS, SMTP and DNS

#프로토콜의 구성요소
 - 구문(syntax): 데이터를 어떻게 구성할 지
 - 의미(semantic): 데이터를 어떻게 제어할 지
 - 타이밍(timing): 데이터를 주고 받을 속도와 동시에 통신하는 경우 순서 관리
 
 
#프로토콜의 종류

TCP/IP, SMTP, HTTP, HTTPS, FTP, SOAP, TLS

(https://media.vlpt.us/post-images/devzunky/0f3adac0-11f0-11ea-8ab2-230db3666a7c/simple-osi-model-7-layers.png)

#프로토콜의 기능
- 캡슐화(encapsulation)
- 흐름제어(flow control)
- 연결제어(connection control)
- 오류제어(error control)
- 주소설정(addressing)
- 순서설정(sequence)
- 동기화(synchronization)
- 분할과 재조립(fragmentation and reassembly)
- 다중화(multiplexing)
