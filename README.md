Title: MS.장민석의 국문 이력서
Author: 장민석 ( chaiosjang _at_ kaist.ac.kr )
Date: 2015-06-15

MS. 장민석
====
## 1. 기본 인적 사항

```
 Name   : 장민석 ( 張旻錫 )
          Min Seok Jang
 Mail   : chaiosjang _at_ kaist.ac.kr
 Phone  : +81 10 2630 7480
 GitHub : https://github.com/shuggiejang
```

## 2. 경력 사항

```
 L1 / L2 Connectivity      : Ethernet, WiFi(hostapd), RGMII
 L6 Connectivity           : OpenSSL, DTCP, WireShark
 L7 Connectivity / Service : DLNA, UPnP
 Multimedia Streaming      : GStreamer
 Multimedia Playback       : GStreamer, QTWebkit
 Web Front-End             : HTML5, AJAX, JQuery, OAuth, 
                             OpenGraph(FBGraph, Twitter Card), Bookmarklet
 Web Back-End              : PHP, MySQL, MS-SQL

 Simulation                : MATLAB, NS2, C++11 Stochastic Simulator
                             PON, TDM-PON
 
 SW Version Control        : Git, SVN
 Embedded Linux            : Experiences on a number of SoC platforms
 Language                  : C, C++, C#, Python, HTML5, Javascript, PHP
                             Markdown

 Interest                  : Energy Monitoring & Analysis,
                             IoT, Rasberry Pi, Arduino, Sensor,
                             DokuWiki, AD Block, Chrome Extension
```

* HUMAX ( 2013.08 ~ 현재 )
    - L1 / L2 Connectivity
        + Gbit Ethernet Switch 드라이버 포팅 및 응용프로그램 개발
        + WiFi 드라이버 포팅 및 hostapd 기반 응용프로그램 개발
        + L1 / L2 설정 Web UI 개발
    - L6 Connectivity
        + OpenSSL기반 TLS HandShake Extension 개발 
    - L7 Connectivity / Service
        + DLNA / UPnP 응용프로그램 개발
        + 패킷캡쳐 및 디버깅
    - 웹 / 멀티미디어 응용프로그램 개발
        + GStreamer 응용프로그램 개발
        + QTWebkit 웹브라우저 미디어 플러그인 개발
* KAIST 석사 ( 2011.02 ~ 2013.08 ), ```https://mnlab.kaist.ac.kr```
    - Energy-Saving Network
        + 에너지 절감형 TDM-PON 연구
            * C++11 기반 Stocastic Process 시뮬레이터 작성
        + 에너지 절감 협력통신 연구
        + 에너지 절감형 multi-homing 로드 분산 연구
        + 네트워크 장비 에너지 소비모델 제안 ( ITU-T SG13 Contribution 1112 )
    -  Web-based Content Aggregation
        + SNS상에서 접하는 미디어를 손쉽게 시청하는 웹서비스 개발
* (주) 에스에프이 ( 2013.07 ~ 2013.08 )
    - 반도체 패키징 장비 configuration 파일 생성 프로그램 작성; Javascript, HTML5
* (주) 카사테크 ( 2008.12 ~ 2009.02 )
    - DB 백업프로그램 작성; C#, MS-SQL
* (주) SNR ( 2008.06 ~ 2008.08 )
    - 차량감지센서, 인체감지센서 필터 개발
* (주) 엔투스 ( 2008.01 ~ 2008.03 )
    - 지능형 가로등 제어 특허조사 및 프로토콜 구현


## 3. 교육

| 연도               | 학교                | 전공        | 학위 |
| ----------------- | ------------------ | ---------- | --- |
| 2003.02 ~ 2006.02 | 광주고등학교          | -          | -   |
| 2007.02 ~ 2011.02 | 한국과학기술원 (KAIST) | 전기및전자공학 | 학사 |
| 2011.02 ~ 2013.08 | 한국과학기술원 (KAIST) | 전기및전자공학 | 석사 |


## 4. 성적

| 구분 | 이수학점 | 평점 |
| --- | --- | --- |
| 학부 | 142 | 3.42 ( 4.3 만점 ) |
| 석사 | 51  | 3.46 ( 4.3 만점 ) |


## 5. 논문

* **Delay Aware Synchronous Bidirectional Transmission Scheme for Energy-efficient TDM-PON ( 에너지 효율적 TDM-PON을 위한 지연 인지 양방향 동기 전송방식 )**
    - **```KAIST 석사학위논문, 2013.06.28, 지도교수: 최준균```**
    - 내용
        + 대부분의 에너지 절감형 TDM-PON연구는 다운링크만을 고려한다. ONU가 업링크 트래픽을 수신하면, 슬립에서 깨어나 업링크 트래픽을 전송한다. 이로 인한 잦은 상태 전환으로 추가적인 에너지를 소비한다. 또한 업/다운링크가 별개로 관리되어, 동시에 관리되었을 때와 대비해 추가적으로 컨트롤 메시지를 교환한다. 이를 해결하기 위해 업/다운링크 전송을 주기적으로 동기화하는 방식이 제안되었지만, 이 연구들은 트래픽 요구사항을 고려하지 않아 여전히 에너지를 절감할 여지가 있다. 이 논문에서는 TDM-PON 환경에서 ONU의 에너지를 절감함과 동시에 만족할만한 트래픽 성능 제공하는 지연을 인지한 양방향 동기 전송방식을 제안한다. 세부적으로는 업링크와 다운링크 트래픽 상태, 그리고 지연 요구사항을 모두 고려한 새로운 슬립 구간 결정 알고리즘을 제안하였다. 또한 업링크와 다운링크를 동시에 전송하여 에너지를 절감하도록 하였다. 시뮬레이션 결과 기존방식대비 15%의 에너지를 절감한다.

----
* Energy Efficient Scalable Video Coding Based Cooperative Multicast Scheme with Selective Layer Forwarding
    - IEEE Communications Letters (4저자), 2013.05.13
    - 내용
        + SVC(Scalable Video Coding)와 협력통신을 통해 무선 멀티캐스트의 에너지 효율을 증가시키는 방법. SVC로 인코딩되어 여러 계층을 가진 영상을 계층별로 다른 채널코딩방식을 사용하여 전송하면 기지국과 단말 사이의 거리에 따라 차등화된 서비스를 제공하게 된다. 이 때, 낮은 계층만을 받은 단말은 주변단말로부터 높은 계층까지 수신한 단말을 검색하며, 단말이 있는 경우 협력통신방식을 통해 릴레이 받는다. 이 때, 계층별로 채널코딩 방식과 전송전력을 조정하여 영상의 품질을 일정기준 이상으로 유지하면서 기지국 커버리지 내 무선단말의 에너지 소비를 최소화한다.

----
* Implementation of continuous HTTP live streaming using playback position request mechanism in heterogeneous networks
    - ICACT, 2013.01.27
        + iOS와 Andriod의 모바일 웹 브라우저는 HLS(HTTP Live Streaming)를 재생할 수 있다. 하지만 이종망간(예, WiFi에서 3G로) 핸드오버를 할 때, 지연이 크기 때문에 세션이 닫히고 스트림이 끊긴다. 핸드오버 된 이후에는 다시 처음부터 재생을 시작한다. 이를 방지하기 위해 순수 웹기술을 바탕으로 서비스를 구현하여, 무선링크가 끊기면 재생위치를 기억하고, 링크가 복구되면 링크의 상태를 바탕으로 적절한 대역폭의 세그먼트를 재생하도록 하였다. 

<br />

## 6. 수행 프로젝트 

* 에너지 소비 자율제어가 가능한 유·무선 네트워크 핵심 기술 연구
    - 기간 : 2011.05 ~ 2012.02
    - 지원기관 : 지식경제부
    - 시행처 : KAIST
    - 내용
        + (1) ITU-T 표준화 활동(기고서 작성 및 국내회의 참여) : 네트워크 장비 에너지 소비 모델 제안 (ITU-T Study Group 13 Contribution 1112) 
        (2) 에너지 절감 협력통신 연구

----
* BcN엔지니어링기술연구
    - 기간 : 2012.01 ~ 2012.12
    - 지원기관 : 지식경제부
    - 시행처 : KAIST
    - 내용
        + 광대역 네트워크 관련 연구, 에너지 절감형 TDM-PON 연구

----
* 서비스 가용성을 위한 이동성 관리 기술연구
    - 기간 : 2011.03~2013.02
    - 지원기관 : 방송통신위원회
    - 시행처 : KAIST
    - 내용
        + 이종망에서 에너지 절감형 multi-homing 로드 분산 연구

----
* 뉴 미디어 환경을 위한 Web of Objects(WoO) 기술 개발
    - 기간 : 2011.12 ~ 2013.08
    - 지원기관 : 지식경제부
    - 시행처 : KAIST
    - 내용
        + 웹 기반 센서 조사 및 응용서비스 시나리오 수립

----
* N-Screen 기반의 맞춤형 Learning Eco-System 연구개발
    - 2011.07 ~ 2011.10
    - 지원기관 : (주)유비온
    - 시행처 : KAIST
    - 내용  
        + HTML5 웹소켓 기반 어플이케이션 구현.
        강사-학습자간 HTML객체 전달(Canvas객체에 필기한 메모 전달) 구현

----
* 웹 기반 Open IPTV 기술 연구
    - 기간 : 2010.06 ~ 2011.02
    - 지원기관 : ETRI
    - 시행처 : KAIST
    - 내용
        + 미디어 어그리게이션 서비스 제작(KT에 프로토타입 전달) 
        (1) 개요 : SNS상에서 접하는 미디어(드라마, 영화, Youtube 등)을 손쉽게(클릭 2~3번 이내) 보고싶은 미디어 목록에 추가, 셋탑에서 목록을 시청. 
        (2) 관련 기술 : HTML5, AJAX, PHP, Twitter/Facebook API, 북마클릿(bookmarklet).


```
최종 수정일: 2015-06-15
```