# TCP/IP

## TCP/IP 개념
- 인터넷 프로토콜 스위트(영어: Internet Protocol Suite)는 인터넷에서 컴퓨터들이 서로 정보를 주고받는 데 쓰이는 통신규약(프로토콜)의 모음이다. 인터넷 프로토콜 슈트 중 TCP와 IP가 가장 많이 쓰이기 때문에 TCP/IP 프로토콜 슈트라고도 불린다.
- TCP/IP는 패킷 통신 방식의 인터넷 프로토콜인 IP (인터넷 프로토콜)와 전송 조절 프로토콜인 TCP (전송 제어 프로토콜)로 이루어져 있다. 
- IP는 패킷 전달 여부를 보증하지 않고, 패킷을 보낸 순서와 받는 순서가 다를 수 있다.(unreliable datagram service) TCP는 IP 위에서 동작하는 프로토콜로, 데이터의 전달을 보증하고 보낸 순서대로 받게 해준다. 
  - IP는 복잡한 네트워크 망에서 효율적으로 데이터를 보낸다. 즉, 데이터를 작은 조각으로 빨리 보내는 것이 중요
  - TCP는 IP가 작게 잘라 보낸 데이터의 순서와 누락된 데이터를 점검하여 다시 요청한다.
- HTTP, FTP, SMTP 등 TCP를 기반으로 한 많은 수의 애플리케이션 프로토콜들이 IP 위에서 동작하기 때문에, 묶어서 TCP/IP로 부르기도 한다.
    - HTTP, FTP, SMTP 등은 웹이나 여러 데이터를 주고 받기 위한 프로토콜이다.

<br/>

## 흐름제어

#### 1. Stop and Wait

#### 2. 슬라이딩 윈도우(Go Back N APQ)

<br/>

## 혼잡제어

#### 1. AIMD (Additive Increase / Multiplicative Decrease)

#### 2. Slow Start

#### 3. Fast Retransmit

<br/>

## 👍 참조사이트
- https://brunch.co.kr/@wangho/6
- https://aws-hyoh.tistory.com/entry/TCPIP-%EC%89%BD%EA%B2%8C-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0
- https://gyoogle.dev/blog/computer-science/network/%ED%9D%90%EB%A6%84%EC%A0%9C%EC%96%B4%20&%20%ED%98%BC%EC%9E%A1%EC%A0%9C%EC%96%B4.html
- https://ko.wikipedia.org/wiki/%EC%9D%B8%ED%84%B0%EB%84%B7_%ED%94%84%EB%A1%9C%ED%86%A0%EC%BD%9C_%EC%8A%A4%EC%9C%84%ED%8A%B8