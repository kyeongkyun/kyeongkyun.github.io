### 커밋 확인
아직 푸시되지 않고 로컬 브랜치에만 있는 커밋 표시시
```bash
git log origin/main..HEAD
git log origin/main..HEAD --oneline //한줄로 표시
git log origin/main..HEAD --oneline --graph //그래프 처리
```

### 도움말
switch에 대한 도움말
```bash
git switch --help
```

### Rebase
현재부터 3개의 커밋을 가져와 -i(interective) 하게 표시해준다.
```bash
git rebase -i HEAD~3
```