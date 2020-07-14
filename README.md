# 재르시의 기본 파일
### 린트룰 번역 오류 컨트리뷰션 환영합니다.!!
git rm -r --cached .

# SwiftInit
# swiftlint
```
if which swiftlint >/dev/null; 
  then swiftlint autocorrect --no-cache
  else
  echo \"warning: SwiftLint not installed, download from https://github.com/realm/SwiftLint\"
fi
```

```
if which swiftlint >/dev/null; 
  then swiftlint --no-cache --strict
  else
  echo \"warning: SwiftLint not installed, download from https://github.com/realm/SwiftLint\"
fi
```
