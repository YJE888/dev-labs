# 개발 환경 설정 가이드

## 대상 환경

- macOS
- VS Code

## VS Code 확장 기능 설치

- Palenight Theme(Material Theme가 유료화됨에 따라 대안으로 설치)
  - VS Code 테마 설정
- Material Icon Theme
  - 파일의 아이콘을 가독성 있게 설정
- Prettier - code formatter
  - 코드의 포맷과 같은 들여쓰기 등을 자동으로 정렬

### VS Code 확장 기능 환경 설정

- cmd + shift + p
- setting.json 열어서 아래의 내용 추가
  ```json
  ...
      "editor.formatOnSave": true,
      "editor.showUnused": true,
      "editor.defaultFormatter": "esbenp.prettier-vscode"
  ```
