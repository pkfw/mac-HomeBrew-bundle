# mac-HomeBrew-bundle

## GitHub Repository 목적
---
- Mac OS에 Homebrew formula(패키지)를 번들로 관리하기 위함

## Homebrew 설치
---
- terminal 에서 실행
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```
- 정상 설치 여부 확인
```
brew doctor
```
  - 문제가 없다면 'Your system is ready to brew' 메시지가 출력된다.

## Cask 설치
---
- terminal 에서 실행
```
brew install cask
```

## Mas 설치
---
- Mas 는 애플 앱스토어의 어플리케이션을 Homebrew 에서 설치할 수 있게 해준다.
```
brew install mas
```

## Brewfile 한 번에 설치하기
```
brew bundle
```

## 패키지 관리
---
- 버전 업된 패키지 확인
```
brew outdated
```
- 수동 업데이트
```
brew upgrade <formula>
```
- 이전 버전 패키지 삭제
```
brew cleanup <formula>
```
