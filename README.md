# Operating-System
OS 이론 및 실습 

### 📌 기본 양식

```markdown
📆 날짜: 2025년 00월 00일 (Week X - Day Y)

🧠 오늘의 목표
- (ex. xv6의 시스템콜 구조 파악 및 hello syscall 구현)

📘 학습한 이론
- (ex. syscall flow: syscall() → sys_foo() → trap → syscall.c)
- (ex. struct proc 내부 필드 변화 이해)

🛠 오늘의 실습
- (ex. hello syscall 커널에 추가, `user/hello.c` 작성)
- (ex. `syscall.c`, `usys.S`, `syscall.h` 수정)

✅ 결과 및 성공 여부
- [x] 목표 달성
- [ ] 부분 달성 (이유: ex. qemu 부팅 에러)
- [ ] 미달성 (사유 기록)

🐛 에러/이슈 로그
- (ex. syscall 등록 후 make qemu 시 unknown syscall number)
- (ex. user program이 `panic`으로 종료됨 – 원인 추적 중)

💡 깨달은 점 / 내일 할 일
- (ex. syscall은 `usys.S`에도 등록해줘야 하는 걸 놓침)
- (ex. 내일은 사용자 syscall로 파일에 문자열 쓰기 구현)

```

---
### 📒 주간 회고 포맷 (매주 일요일)

```markdown
📆 Week X 회고 (기간: 2025.00.00 ~ 00.00)

🎯 이번 주 목표 달성도
- [x] xv6 syscall 구조 완전 이해
- [x] 시스템콜 2개 추가 및 동작 테스트 완료

📘 이론 복습 요약
- 시스템콜 등록 순서, 커널 유저 영역 전환, trapframe 등

🛠 실습 요약
- hello, add syscall 구현
- `user` → `kernel` 흐름 완전 이해

🔧 문제 해결 경험
- Makefile 수정 실수 → 빌드 실패 → 의존성 캐시 삭제로 해결
- qemu 실행 시 unknown syscall → usys.S 누락 확인

📌 다음 주 목표
- xv6의 스케줄러 수정 (우선순위 기반으로 전환)
- `ps` 명령어 커스터마이징
```

---
### 📎 활용 방법

- **하루가 끝날 때마다 위 포맷으로 로그를 작성**
- github에 주차별로 정리하면 포트폴리오로도 활용 가능
- 오류나 깨달은 점은 꼭 적기
- 매주 일요일에는 전체 회고 추가
---
