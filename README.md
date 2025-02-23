# 파워 내향인들을 위한 자기소개 프로젝트 : 뇌진구 

### 뇌진구에게 자기소개하고 다른 친구들과 나의 뇌를 공유하고 어색한 분위기를 빨리 벗어나 보아요

- 나의 뇌를 만들어 평소 관심사와 특징을 #로 표현을 해요
- 다른 사람들과의 공유를 통해 상대와의 공통점을 찾아요
- 다른 친구들과 뇌 공유 뿐만 아니라 뇌진구와 놀 수 있는 기회까지~

# 팀원 소개

|  | **김준협** | **장희주** |
| --- | --- | --- |
|   **학부** | KAIST 전기 및 전자공학부  | 숙명여자대학교 컴퓨터과학전공  |
|   **역할**  | 로그인 및 , 디자인 , 사용자 정보 수정,  | 뇌와 친구 마이페이지 프론트/백엔드 |

# 기술 스택

### Web

- FrontEnd : React
- BackEnd : Spring Boot
- IDE : Visual Studio, IntelliJ
- Database : MySQL
- Infra : AWS RDS, EC2

### ERD
![friends_diagram](https://github.com/user-attachments/assets/52619643-e3f7-4cde-84d4-a07dd72ca821)

### 역할 분담 및 협업 과정 
기능별로 나눠서 각자 프론트엔드/백엔드 동시에 작업을 함

# 웹 UI 및 화면 소개

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/066d74af-27ad-4b36-a623-baa172addfe3/image.png)

처음 접속했을때 화면 

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/b8337c32-970c-4e13-93e3-112084312b22/image.png)

회원가입 페이지

- 닉네임과 이메일은 개인마다 고유해야하며, 비밀번호 확인까지 맞아야 회원가입 가능

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/567f5b4c-f61b-4cd8-ab20-1489c1aff63d/image.png)

로그인 페이지 

- 가입한 닉네임과 비밀번호를 입력해서 로그인하기

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/3ea2b5b5-54a1-4a79-a53c-2d7f66e89230/image.png)

로그인하고 나서의 페이지 

- 자기의 뇌를 만들었다면, 네! 버튼   ⇒ Home으로 페이지 전환
- 만들지 않았다면 아니요… 버튼 누르기   ⇒ 뇌 만들기 페이지로 전환

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/c199fe34-7a20-4107-bbff-d3eff2a7115e/image.png)

뇌 만들기 페이지 초기 화면 

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/bac0dbe1-8d11-47ae-9a35-d79effd7ac19/image.png)

“+” 버튼을 눌러서 나의 관심사, 생각 입력 

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/4810b682-f2f7-4ecd-9ec0-e4ced6d8f35e/image.png)

저장 버튼 누르면 아래와 같이 보이고 데이터베이스에 저장

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/88f840c1-f869-4a8b-8233-180619953d36/image.png)

**<홈 화면>** 

: 처음 접속했을 때 화면, 보물함 속에 있는 아이템을 선택하면 해당 캐릭터가 랜덤으로 움직인다.  

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/20c70319-7aa9-43c7-8ffb-57d1540356d4/image.png)

**<메뉴 바>** : 햄버거 버튼 눌렀을 때 나온다. 

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/2c2bcc48-be03-4032-ada6-8dc730ccd64c/image.png)

**<친구 맺기 페이지>**

원하는 친구에게 Disconneced 버튼을 누르면 Connecting으로 변하고 친구가 수락을 하면 친구관계가 된다. 검색어에 닉네임을 입력해서 바로 가져올 수 있다. 

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/70bfb87a-776a-4d2c-9c4b-1cec7c52dbe3/image.png)

**<뇌 공유 페이지>** 

나와 친구인 친구들의 뇌민 보인다. 
해당 친구의 뇌 정보 보기 버튼을 누르면 그 친구의 관심사를 확인할 수 있다. 

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/c2e7b355-2fb8-474f-b60c-206c216ab1de/image.png)

**<마이페이지 전체 화면>**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/14cb68a3-a81d-46f6-9d57-73a0a641e494/image.png)

- 나의 정보 : 나의 정보를 수정할 수 있는 페이지
- 나의 뇌 : 내가 만든 뇌를 조회하고, 관심사를 수정하고, 삭제하고 추가할 수 있는 페이지
- 친구 신청 관리 : 나에게 친구 신청 온 친구들의 수락을 받고, 친구인 사람 리스트 확인 및 끊을 수 있는 페이지

**<나의 정보 화면>**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/762c4d4f-6b35-47e5-ae92-357f7c98ab88/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/92abc805-632e-4707-a3fc-23cbf09f6aca/image.png)

사용자 이름, 이메일, 비밀번호를 수정할 수 있다. 

**<나의 뇌 페이지>**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/6df73c4f-d505-40ec-b22f-a5e2bf515626/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/23be08ad-a519-43f6-af95-147334343804/image.png)

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/d71e15c0-1503-4d4c-9b74-9689a29e39c9/image.png)

나의 뇌에 추가하고 싶은 관심사 및 삭제하고 싶은 관심사 편집 

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/8f91998f-99b2-4023-90f0-19b35a2e1bca/image.png)

편집하고 싶은 관심사를 클릭해서 입력 후 enter 치면 수정됨 

**<친구 신청 관리 페이지>**

![image.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/9cbc29a2-0f6f-44c7-a521-50f8adb2b296/image.png)

# 핵심 기능 소개 및 영상 시연

### 오프닝 및 회원가입/로그인

![opening scene.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/e14d5e70-3d5e-472a-b077-769e33af5005/opening_scene.gif)

[계정 만들기+로그.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/00d4e503-0e2a-4f23-89df-307c2f5ca03d/%EA%B3%84%EC%A0%95_%EB%A7%8C%EB%93%A4%EA%B8%B0%EB%A1%9C%EA%B7%B8.mp4)

### 사용자 뇌 추가하기

- 새로운 계정을 만들 때 사용자를 표현하는 단어들을 입히기

[뇌를 만들기.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/0c0dbfac-0546-4da1-a276-db54a657d11f/%EB%87%8C%EB%A5%BC_%EB%A7%8C%EB%93%A4%EA%B8%B0.mp4)

### 친구 관계 맺기 (신청, 수락, 끊기)

- 신청 : 친구 맺기 화면에서 원하는 친구에게 신청하기

[친구추가요청& 친구 검색.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/76bc375b-59c9-4b52-ad63-bce13a7ba0c0/%EC%B9%9C%EA%B5%AC%EC%B6%94%EA%B0%80%EC%9A%94%EC%B2%AD_%EC%B9%9C%EA%B5%AC_%EA%B2%80%EC%83%89.mp4)

- 수락 : 마이페이지에서 요청 온 친구의 신청 받기

![Untitled video.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/b76435dd-06ad-4042-adb9-fae8c187da03/Untitled_video.gif)

- 거절 : 마이페이지에서 친구 상태인 Friend 버튼을 다시 눌러서 친구 관계 끊기

![delete friend.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/4de47abf-51fb-46e8-adef-d6013a71a4ed/delete_friend.gif)

### 친구들과 뇌 공유하기 (뇌 공유 페이지)

![Untitled video.gif](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/d750fa09-e862-4a79-81df-ac3a09b6c63c/Untitled_video.gif)

### 사용자 마이페이지에서 뇌 편집하기

[개인 뇌 정보수정.mp4](https://prod-files-secure.s3.us-west-2.amazonaws.com/f6cb388f-3934-47d6-9928-26d2e10eb0fc/43cbea77-c4d7-4447-b1c3-1f778be1ffe0/%EA%B0%9C%EC%9D%B8_%EB%87%8C_%EC%A0%95%EB%B3%B4%EC%88%98%EC%A0%95.mp4)

### 사용자 정보 수정(닉네임, 이메일, 비밀번호)

- 닉네임: 사용자 계정의 닉네임을 수정하기

- 이메일: 사용자 계정에 등록된 이메일 주소를 수정하기

- 비밀번호: 기존 비밀번호 확인 후 사용자 계정에 로그인 할 때 사용되는 비밀번호를 수정하기
- 

## 나중에 더 보완하고 디벨럽할 예정 

## 보완한 점, 기록예정 
