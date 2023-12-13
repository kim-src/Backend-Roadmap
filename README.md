<!-- 작성일자 -->
<!-- 제목 -->
<!-- 내용 -->

<!-- 작성일자 -->
#### Date : December 12, 2023

<!-- 제목 -->
✅ How does the internet work? (작성중)
===
<br/>

<!-- 내용 -->
### 🔔 Introduction
> 인터넷을 작동시키기 위해서는 PC 전원을 켜고 LAN 포트에 랜선을 연결하면 됩니다.  
> PC와 연결된 랜선의 다른 끝부분은 벽면의 랜포트 또는 와이파이 라우터로 연결됩니다.  
> 그렇다면 벽면 또는 와이파이 라우터의 랜포트의 종착 지점은 어디일까요?  
> 이번 글에서는 인터넷의 원초적인 의미는 무엇이고 어떻게 작동되는지 알아보겠습니다.

<br/>

### 📌 인터넷이란
> 인터넷이 어떻게 작동되는지 이해하려면 먼저 인터넷이 무엇인지를 인지해야 됩니다.  
> Internet이란 Inter + Network의 합성어이며 네트워크가 연결된 상태를 의미합니다.  
> 그리고 Network란 Net + Work의 합성어이며 작업 공간이 얽혀져있는 것을 뜻합니다.  
> 그러므로 작업 공간이 이어진 상태를 네트워크 및 인터넷이라고 표현할 수 있겠습니다.
>
> <br/>
>
> 이 네트워크 개념은 몇 가지 분류에 따라 구분됩니다.  
> 1. 규모에 따른 네트워크 분류 → PAN, LAN, MAN, WAN 등  
> 2. 무선(wireless) 상태의 네트워크 분류 → SAN, VPN 등  
> 3. 데이터 전송 방식에 따른 네트워크 분류 → 패킷 교환 방식, 셀 릴레이 방식 등  
> 4. 노드(node) 연결 형태에 따른 네트워크 분류 → 버스형, 스타형, 링형 등  
> (노드(node) = 컴퓨터, 스마트폰 등 IP 주소를 보유한 모든 전자기기)
> 
> <br/>
>
> 이번 글에서는 규모에 따른 네트워크 분류만을 다뤄보겠습니다.
> 
> <br/>
> 
> 작업 공간을 PC로 가정했을 경우 작업을 하려면 컴퓨터의 전원이 켜진 상태여야 됩니다.  
> 전원이 켜진 상태의 컴퓨터 한 대는 작업을 할 수 있는 환경입니다.
> 
> <br/>
> 
> 하지만 다른 컴퓨터로 데이터를 송신하거나 타 컴퓨터의 데이터를 수신할 수 있는 환경은 아닙니다.  
> 따라서 전원이 켜진 "컴퓨터-1" 한 대에서만의 작업은 인터넷이 작동된다고 할 수 없겠습니다.  
> 왜냐하면 다른 컴퓨터(ex "컴퓨터-2", "컴퓨터-3" 등)들의 작업 공간과 연결되어 있지 않기 때문입니다.  

<br/>

### <p align = "center">그렇다면 인터넷은 어떻게 작동되는 것일까요?</p>

<br/>

### 📌 Case 1. 컴퓨터끼리의 연결
> 서로 다른 컴퓨터끼리 연결시킬 수 있는 가장 간단한 방법은  
> 데이터 전송이 가능한 케이블로 서로를 연결하는 것입니다.  
> 이는 인터넷 환경의 초창기 형태이며 한 공간에 존재하는 컴퓨터들과의 데이터 전송이 가능했습니다.  
> 그러므로 작은 규모의 인터넷이 작동했던 것입니다.
>
> <br/>
> 
> 하지만 수많은 컴퓨터가 연결된 네트워크 환경을 구축하기 위해서는  
> 무수히 많은 케이블과 공간이 필요하다는 단점이 있었습니다.  
>
> <br/>
> 
> 컴퓨터들끼리 케이블을 연결한 모식도는 아래와 같습니다. (출처: Mozilla)  
> <p align = "center"><img src = "https://github.com/Kim-src/Backend/assets/150884526/7cf0adc4-3e1f-4f1f-b986-2968a3c2f4c2" width = "500px"></p>

<br/>

### 📌 Case 2. 라우터(Router)끼리의 연결
> Case 1에서의 단점을 보완해주기 위해 개발된 것이 라우터입니다.  
> 라우터는 여러 컴퓨터들의 연결을 돕는 중계 장치 역할을 합니다.  
> 라우터와 연결되는 선은 컴퓨터 한 대 당 한 줄이며 라우터에 연결된 각 컴퓨터는 서로 연결됩니다.
> 
> <br/>
> 
> 그러므로 라우터를 활용하면 근처 컴퓨터들끼리의 연결 효율이 더 좋아집니다.  
> 게다가 이 라우터들끼리 연결하면 일정 지역에 존재하는 컴퓨터들끼리의 네트워크 망이 구축될 것입니다.  
>
> <br/>
> 
> 라우터의 외관은 아래 이미지와 같습니다. (출처: Wikipedia)
> 
> <p align = "center"><img src = "https://github.com/Kim-src/Backend/assets/150884526/15922c12-323b-4df3-8cc9-d22a3d0e3817" width = "500px"></p>
> <br/>
> 
> 최근 와이파이(Wi-Fi) 라우터 장치가 보급되면서 라우터라는 단어가 보다 익숙해지셨을 수 있습니다.  
> 하지만 이번 글에서 말씀드리는 라우터는 위의 carrier class 라우터 혹은 아래의 소형 라우터를 뜻합니다. (출처: Wikipedia)  
> 
> <p align = "center"><img src = "https://github.com/Kim-src/Backend/assets/150884526/57d4cff7-e129-485f-afea-1dcbd3503ad7" width = "500px"></p>
> <br/>
> 
> 라우터에 연결된 컴퓨터들끼리의 네트워크 개념도는 아래와 같습니다. (출처: Mozilla)  
> 참고로 와이파이 라우터 등 무선 연결과 관련된 내용은 추후 작성해보겠습니다.  
> <p aling = "center"<img src = "https://github.com/Kim-src/Backend/assets/150884526/48359b74-d306-4199-b486-7b7aa92a3fe7" width = "500px"></p>

<br/>

### 📌 Case 3. 모뎀(Modem)과 라우터의 연결
> 네트워크의 규모에 따라 네트워크는 크게 네 가지로 구분됩니다.  
> 1. PAN: "Personal Area Network"의 축약어로 가장 작은 규모의 네트워크를 의미합니다.  
> 2. LAN: "Local Area Network"의 축약어로 집, 학교, 회사 정도 규모의 네트워크를 의미합니다.  
> 3. MAN: "Metropolitan Area Network"의 축약어로 도시, 대학교 캠퍼스 정도 규모의 네트워크를 의미합니다.  
> 4. WAN: "Wide Area Network"의 축약어로 대륙과 대륙, 국가와 국가 규모의 네트워크를 의미합니다.  
>
> <br/>
>
> 따라서 근래의 인터넷이란 WAN 네트워크를 의미한다고 표현하는 것이 적절하겠습니다.  
> 데이터의 교환이 대륙이나 국가와 같은 물리적인 공간을 관통하기 때문입니다.  
>
> <br/>
> 
> 그런데 네트워크의 규모가 컴퓨터와 라우터의 연결만으로는 도시나 국가 규모로 확장되기는 어려웠을 것입니다.  
> 거대한 근래 네트워크 규모로 확장할 수 있었던 방법은 전화 통신 인프라를 이용한 것입니다.  
> 
> <br/>
> 
> 전화 통신 인프라(telecommunications infrastructure)는 네트워크 망 확장 이전에 이미 구축되어 있었습니다.  
> 따라서 네트워크를 전화 통신 인프라에 연결하기 위해서 라우터를 모뎀과 연결하였습니다.
>
> <br/>
> 
> 이 모뎀의 역할은 네트워크 정보를 전화 통신 인프라에서 관리할 수 있는 정보로 변환해주는 것입니다.  
> 컴퓨터, 라우터, 모뎀의 연결 모식도는 아래와 같습니다. (출처: Mozilla)
> <p align = "center"><img src = "https://github.com/Kim-src/Backend/assets/150884526/ddce0e00-fb08-40e0-bcda-7d4cd984ea8f" width = "500px"></p>

<br/>

### 📌 Case 4. ISP와 모뎀의 연결
> ㅇㅇ



>
> <p align = "center"><img src = "https://github.com/Kim-src/Backend/assets/150884526/2b8fa099-4759-438c-a7b0-5c47f9a36642" width = "500px"></p>
> <br/>
> dd  


### 🎁 References
> 1. [Developer.Mozilla](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work)  
> 2. [Youtube.Lesics](https://www.youtube.com/watch?v=x3c1ih2NJEg&t=3s)  
> 3. [Youtube.BLASTERTECHNOLOGY](https://www.youtube.com/watch?v=Sfzo4xm5eX8)  
> 4. [CCTV 뉴스.최형주 기자님](https://www.cctvnews.co.kr/news/articleView.html?idxno=210852)  

***

<br/>
<br/>
<br/>

<!-- 작성일자 -->
#### Date : December 8, 2023

<!-- 제목 -->
✅ 백엔드 개발자 로드맵
===
<br/>

<!-- 내용 -->
### 🔔 2022년 12월 23일,
> 구글의 개발자 Kamran Ahmed가 설립한 roadmap.sh의 백엔드 로드맵이 업로드 되었습니다.  
> 해당 로드맵은 2023년 버전으로 [https://roadmap.sh/backend](https://roadmap.sh/backend)에 업로드 된 내용입니다.  
> 
> <p align = "center"><img src = "https://github.com/Kim-src/Kimsrc/assets/150884526/950b4ac0-eb19-4ce5-9a22-47e978254f94" width = "500px"></p>
> <br/>
> 
> 상기 로드맵의 내용을 참고하여 차근차근 백엔드 개발자로 되어 보려고 합니다.  
> 이제 Internet이 어떻게 작동하는지부터 알아보겠습니다.  

<br/>

### 🎁 Reference
> [Roadmap.sh](https://roadmap.sh/)  

***

<br/>
<br/>
<br/>
