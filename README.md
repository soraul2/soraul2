<br>

## 🛠️ 주요 기능 (Key Features)

1. 멀칭 비닐 계산기 (Mulching Film Calculator)
- 밭의 면적(평)과 비닐 규격을 입력하면 **필요한 롤 개수**와 **예상 비용**을 계산해줍니다.
- 복잡한 `m²` 단위를 직관적인 `평` 단위로 자동 변환하여 보여줍니다.
- **애플 스타일(Apple Style)**의 깔끔한 모바일 UI 제공.

2. API 문서화 (Swagger/OpenAPI)
- `Springdoc`을 적용하여 실시간으로 API 명세를 확인할 수 있습니다.
- 접속 주소: `https://farm.wootae.com/swagger-ui/index.html'

3. 자동 배포 시스템
- `deploy.sh` 쉘 스크립트를 통해 원클릭 배포 및 무중단(재시작) 운영 관리.

<br>

스택 (Tech Stack)

| 분류 | 기술 | 비고 |
| :--- | :--- | :--- |
| **Backend** | Java 21, Spring Boot 3.4 | API 서버 및 비즈니스 로직 |
| **Frontend** | Thymeleaf, HTML5, CSS3 | Bootstrap 5 활용 |
| **Infra** | Raspberry Pi 5, Ubuntu | 홈 서버 구축 |
| **Database** | MariaDB (예정) | 데이터 영구 저장 |
| **Tool** | IntelliJ, Git, Swagger | 개발 및 협업 도구 |
