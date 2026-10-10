# URLog 암호화 업데이트

URLog 앱의 자동 업데이트 전용 저장소입니다. 현재 시험 배포는 **Windows x64 0.9.5**입니다.

기존 앱은 서명된 `update.json`을 확인하고 `.urupdate`를 내려받아 검증·복호화한 뒤 앱 종료 후 적용합니다. 이용자는 GitHub 로그인이나 키 입력이 필요하지 않습니다.

- 이 저장소의 `.urupdate`는 직접 실행하는 설치 파일이 아닙니다.
- 최초 실행 파일은 구매한 배포처에서 받으세요.
- 앱 소스코드, 원본 EXE·AppImage·DMG, 복호화 키와 서명 개인키는 공개하지 않습니다.
- 0.9.x는 업데이트 시험용 사전 릴리스이며, 1.0.0 정식 발매는 별도로 진행합니다.
- Linux와 macOS의 새 업데이트 파일은 해당 운영체제에서 빌드·검증한 뒤 게시합니다.

## Encrypted updates

Existing URLog installations verify, decrypt and apply these updates without user registration or GitHub credentials. This repository does not distribute the application's source code or original executables. Obtain the initial application from its authorized distribution channel.
