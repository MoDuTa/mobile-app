# mobile-app

모두타 공공자전거 시민용 앱

공통 이슈·브랜치·커밋·PR 규칙은 [협업 가이드](https://github.com/MoDuTa/.github/blob/0cbbc8c62c5b1e0bfc2eb9024738cb1073a381f7/CONTRIBUTING.md)를 참고하세요.


---

## Expo 개발 환경

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **src/app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **example** directory and create a blank **src/app** directory where you can start developing.

### Other setup steps

- To set up ESLint for linting, run `npx expo lint`, or follow our guide on ["Using ESLint and Prettier"](https://docs.expo.dev/guides/using-eslint/)
- If you'd like to set up unit testing, follow our guide on ["Unit Testing with Jest"](https://docs.expo.dev/develop/unit-testing/)
- Learn more about the TypeScript setup in this template in our guide on ["Using TypeScript"](https://docs.expo.dev/guides/typescript/)

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.

## 협업과 검증

이 변경의 기준은 [공통 협업 규칙 개정본](https://github.com/MoDuTa/.github/blob/0cbbc8c62c5b1e0bfc2eb9024738cb1073a381f7/CONTRIBUTING.md)입니다

- 작업 브랜치 예시: `feat/rental`, `fix/12-return-status`. WBS 번호는 필수가 아닙니다
- PR 제목 예시: `feat: 대여 기능 추가`, `fix(auth): 만료 처리 수정`
- 작업 중 커밋 메시지는 강제 검사하지 않으며, Squash 최종 커밋에는 PR 제목을 사용합니다
- 이슈는 PR 본문에서 연결하고, WBS·Jira 링크는 필요한 경우 참고 정보로 적습니다

### 규칙 전환 순서

[공통 규칙 PR #1](https://github.com/MoDuTa/.github/pull/1)을 먼저 승인·머지한 다음 이 저장소의 전환 PR을 반영합니다

공통 문서가 아직 머지되지 않은 검토 단계에서도 위 개정본을 기준으로 합니다. 기존 공통 문서의 WBS 필수·대괄호 PR 제목·중간 커밋 형식 강제 안내 대신, 이 절의 새 규칙을 적용합니다. 전환 PR이 반영되지 않은 다른 브랜치의 검사는 자동으로 바뀌지 않습니다
