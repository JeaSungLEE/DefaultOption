
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
