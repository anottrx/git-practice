# Git 연습 및 공부하기

## 문법

### 할 일 체크하기

- [ ] 할 일
- [x] 할 일 완료

```markdown
- [ ] 할 일
- [x] 할 일 완료
```

## 기타 사항

### VSCode Extension 추천

- [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced)를 통해 마크다운 문서를 보다 깔끔하게 확인할 수 있다.
- [Git Graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)를 통해 어느 브랜치에 있는지, 누가 어디에서 진행하고 있는지 한눈에 파악하기 쉽다.

### .gitignore

1. .env 파일을 업로드해서 push한다.
2. .env 파일을 제거하고, 앞으로도 해당 파일을 무시하기 위해 .env가 입력된 .gitignore을 push한다.
3. .env 파일을 새로 작성해도 2번 시점부터 .gitignore가 적용되어 .env는 올라가지 않는다. 다만 앞서서 올렸다가 지웠던 .env 기록은 계속 남는다.
