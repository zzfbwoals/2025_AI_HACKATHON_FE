<div align="center">
  
# [2025 캡스톤 디자인 및 AI 해커톤]  4팀 - ROUTY 👪

<img width="1246" height="699" alt="image" src="https://github.com/user-attachments/assets/3911e3c1-7d99-4e16-9964-4e7dd4d55609" />
<img width="1248" height="701" alt="image" src="https://github.com/user-attachments/assets/a51e7a33-5f6c-4618-8cb8-a22ceab4bfa7" />
<img width="1247" height="698" alt="image" src="https://github.com/user-attachments/assets/844fc584-7431-4334-ac90-5442d43dc793" />
<img width="1246" height="699" alt="image" src="https://github.com/user-attachments/assets/a2b53214-a723-4506-9550-15b366a531c4" />
<img width="1246" height="702" alt="image" src="https://github.com/user-attachments/assets/9dd1c952-dc8d-4dd8-8f4b-7b367b741bcf" />
<img width="1247" height="699" alt="image" src="https://github.com/user-attachments/assets/01609634-84ff-4669-9d1d-a5aad830104d" />
<img width="1245" height="700" alt="image" src="https://github.com/user-attachments/assets/5352bd8d-83e1-4d9d-a88e-ddbfaa64b31e" />
<img width="1246" height="698" alt="image" src="https://github.com/user-attachments/assets/49bad60f-b4b4-4a49-a194-ac6548958cba" />
<img width="1247" height="698" alt="image" src="https://github.com/user-attachments/assets/54a197c4-00c2-4b9e-af81-e02e0f7f7eb9" />
<img width="1246" height="698" alt="image" src="https://github.com/user-attachments/assets/c301cff4-7c6b-43c8-8ffd-93d15d7319ec" />
<img width="1152" height="642" alt="image" src="https://github.com/user-attachments/assets/a47b4d78-914d-4579-aab1-af55c4780364" />
<img width="1247" height="699" alt="image" src="https://github.com/user-attachments/assets/2bb6ddcd-56d3-4552-a604-e693614c4c8e" />
<img width="1248" height="699" alt="image" src="https://github.com/user-attachments/assets/d17bac17-b525-45e9-ad9b-affd18fe6c88" />
<img width="1245" height="696" alt="image" src="https://github.com/user-attachments/assets/1b2fc0fc-51e2-4293-bb45-1c32795fbe66" />
<img width="1245" height="699" alt="image" src="https://github.com/user-attachments/assets/c6651321-6356-45a5-997d-28487f0547de" />
<img width="1245" height="698" alt="image" src="https://github.com/user-attachments/assets/fff0cb89-e8ce-450d-b854-4df8c4469b29" />


</div>

---
## 프로젝트 시작하기

### 1. 환경 설정

#### 1.1 Python 패키지 설치
```bash
pip install flask flask-cors bcrypt mysql-connector-python openai
```

#### 1.2 데이터베이스 설정 (MySQL Workbench)

1. MySQL Workbench 실행 후 root 계정으로 로컬 연결
2. `DB/init.sql` 스크립트 실행:
   - `File` → `Open SQL Script` → `DB/init.sql` 선택
   - 전체 스크립트 실행 (⌘+⇧+Enter 또는 ⚡ 버튼)
   - 생성된 테이블 확인: `users`, `routine`, `characters` 등

3. **중요**: `app.py`의 DB 연결 정보 수정:
   ```python
   DB_CONFIG = {
       'host': '127.0.0.1',
       'user': 'root',  # 또는 본인이 사용하는 계정
       'password': 'YOUR_MYSQL_PASSWORD',  # 본인의 MySQL 비밀번호
       'database': 'myapp'
   }
   ```

#### 1.3 백엔드 서버 실행
```bash
cd 2025_AI_HACKATHON_BE-main
python3 app.py
```
서버가 `http://0.0.0.0:5001`에서 실행됩니다.

#### 1.4 환경 변수 설정 (선택사항)
```bash
export OPENAI_API_KEY="your-openai-api-key"
```

### 2. 프론트엔드 설정

#### 2.1 Flutter 앱 실행
```bash
cd flutter_hackathon_project
flutter run
```

#### 2.2 API 연결 확인
- `lib/constants/app_constants.dart`에서 `baseUrl`이 `http://localhost:5001`로 설정되어 있는지 확인

---
## 팀원 소개

<table>
<tr>
<td align="center">
<a href="https://github.com/fufckddl" target="_blank">
<img src="https://avatars.githubusercontent.com/fufckddl" width="60px;" alt="김태현"/><br />
<b>이창렬</b>
</a><br/>
팀장 / 프론트
</td>
<td align="center">
<a href="https://github.com/minjini-sys" target="_blank">
<img src="https://avatars.githubusercontent.com/minjini-sys" width="60px;" alt="최희우"/><br />
<b>김민진</b>
</a><br/>
백엔드
</td>
<td align="center">
<a href="https://github.com/rhehdud" target="_blank">
<img src="https://avatars.githubusercontent.com/rhehdud" width="60px;" alt="김사랑"/><br />
<b>고도영</b>
</a><br/>
백엔드
</td>
<td align="center">
<a href="https://github.com/ujieeemin" target="_blank">
<img src="https://avatars.githubusercontent.com/ujieeemin" width="60px;" alt="유한솔"/><br />
<b>유지민</b>
</a><br/>
기획 / 자료
</td>
<td align="center">
<a href="https://github.com/zzfbwoals" target="_blank">
<img src="https://avatars.githubusercontent.com/zzfbwoals" width="60px;" alt="류재민"/><br />
<b>류재민</b>
</a><br/>
기획 / 자료
</td>
</tr>
</table>

---

## 프로젝트 링크

- [Notion 기획서 (MVP)](https://www.notion.so/2025-AI-4-ROUTY-296087d76afe80128dcee38b384e2962)  
- [GitHub FE 리포지토리](https://github.com/zzfbwoals/2025_AI_HACKATHON_FE)  
- [GitHub BE 리포지토리](https://github.com/zzfbwoals/2025_AI_HACKATHON_BE)

---

© 2025 AI HACKATHON Team 4
