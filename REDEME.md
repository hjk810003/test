### 서버(리모트) -> 로컬 받아오기
```
   $ git pull
   $ git pull origin ${리모트 브랜치}
```

### 로컬 -> 스테이징
```
   $ git add ${파일경로}
   $ git add . (. 을 사용하면 전체 add)
```

### 스테이징 -> 커밋
```
   $ git commit -m '커밋 메세지'
```

### 커밋 -> 서버(리모트)
```
   $ git push 
   $ git push origin ${리모트 브랜치}
```