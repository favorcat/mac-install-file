# Install
1. Clone github file
```
git clone https://github.com/favorcat/mac-install-file.git
```
2. Add authorization
```
chmod +x ./install.sh
```
3. Run `install.sh` file
```
./install.sh
```

## homebrew로 설치한 리스트 bundle 생성
```
brew bundle dump
```

## iTerm2 설정
1. oh-my-zsh 설치
```
sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```
2. iTerm preferences 이동
    1. color presets -> import -> `Snazzy.itermcolors`
    2. font -> [D2coding](https://github.com/naver/d2codingfont)
3. `~/.zshrc` 파일 덮어쓰기
4. `~/.oh-my-zsh/themes/`에서 `agnoster.zsh-theme` 파일 덮어쓰기

## 원화기호(₩) -> 백쿼트(`) 변경
1. `KeyBindings`폴더 `Library`폴더로 이동 후 재부팅

## 한글 자음모음 분리현상 해결
1. `hangul-patch`폴더 스크립트 파일 실행
2. `설정` - `확장 프로그램` - `Finder`와 `Touch Bar`에 자음모음 분리 해결 스크립트 활성화

## [VSCode C/C++ 컴파일러 설정](https://github.com/favorcat/mac-cpp-compiler)

## 추가 설치 프로그램
- [f.lux](https://justgetflux.com/)
- [FileZilla](https://filezilla-project.org/)
- [Leawo Blu-ray Player](https://www.leawo.com/downloads/blu-ray-player-mac.html)
