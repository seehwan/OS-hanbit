#### 📌 답 1️⃣  
기본 파이프 IPC는 프로세스가 IPC를 위해 개방한 파일 1개에 대해 읽기 또는 쓰기의 단방향 통신만을 지원한다. 2개의 프로세스 간에 하나의 파이프만 연결되었다면 한 프로세스는 정보를 무조건 주기만 하고 다른 한 쪽은 무조건 받기만 하는 단방향 시스템이 되고 만다. 이 때문에 양방향 의사소통이 되려면 2개의 파이프가 필요하다.

---

#### 📌 답 2️⃣  
시그널을 수신한 후 어떤 반응을 취할지 결정한다. 즉, 사용자가 시그널을 받은 경우, 실행하고 싶은 함수를 정의하도록 한다. 

---

#### 📌 답 3️⃣ 
프로세스들은 공유 메모리에 자신의 메모리처럼 접근할 수 있으므로 다른 프로세스로 인해 변화된 내용을 알 수 있다.

---

#### 📌 답 4️⃣  
메시지를 보내는 사람이 그 의미를 정의함으로써 유연성을 보장할 수 있기 때문이다.
