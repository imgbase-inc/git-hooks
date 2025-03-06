# git-hooks

## 필수 사항

아래 명령어를 실행하여 git global 환경설정에 hooks 경로를 변경한다.
```
git config --global core.hooksPath [git-hooks 로컬 경로]
```

## pre-commit

- 커밋 전에 [swift-format](https://github.com/swiftlang/swift-format)을 실행하여 Swift 파일의 코드 스타일을 자동으로 포맷팅합니다.
