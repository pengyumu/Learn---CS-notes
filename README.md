# Learn---CS-notes
QUIC 协议 继承了 HTTP/2 多路复用和流量控制， TCP 的拥塞控制和流量控制，也整合了 TLS 的加密， 催生了 HTTP/3
由于操作系统暂时没有 QUIC 这个协议， QUIC 需要依托在旧的传输层协议上，因此选择了UDP,不按顺序传输。
尽可能的细分是Quic的一个特点，每一个包都有自己独立的号码， 所以可以解决TCP队头阻塞问题。
Quic比起TCP，会少2-RTT,简历连接之后甚至为0-RTT
Quic被广泛应用于音视频领域。

<img width="903" height="305" alt="image" src="https://github.com/user-attachments/assets/3a372038-b2e5-4b67-b6d9-3ebfab02472a" />


<img width="685" height="608" alt="image" src="https://github.com/user-attachments/assets/83af6851-0d50-4ffb-8989-b8bd7bbf1fd4" />


<img width="595" height="630" alt="image" src="https://github.com/user-attachments/assets/81ee1b0a-f731-4b4a-bc09-62de3b833598" />


