### 구현기능


1. 일정 생성 및 등록
2. 전체 일정 조회
3. 선택 일정 조회
4. 선택 일정 수정
5. 선택 일정 삭제



### API 명세서


|기능|Method|URL|Request|Responese|StatusCode|
|------|---|---|----|----|--------|
|일정 생성 및 등록	|POST|/api/schedules|요청 body|등록 정보	|200 : 정상등록|
|전체 일정 조회|GET|/api/schedules|요청 param|전체 응답 정보|200 : 정상등록|
|선택 일정 조회|GET|/api/schedules/{scheduleId}|요청 param	|선택 응답 정보|200 : 정상등록|
|선택 일정 수정|PUT|/api/schedules/{scheduleId}|요청 body	|선택 응답 정보|200 : 정상등록|
|선택 일정 삭제|DELETE|/api/schedules/{scheduleId}|요청 param	|-|200 : 정상등록|


### ERD

![image](https://github.com/user-attachments/assets/1a64187a-ad81-461b-bae0-12ac74741689)
