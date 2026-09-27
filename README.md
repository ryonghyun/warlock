# warlock

## 우분투에 nvm으로 node.js 설치
### 1. 기존에 설치 된 node.js 삭제
### 2. nvm (node version manager) 설치
2-1. https://github.com/nvm-sh/nvm 가서 설치 스크립트 찾기

2-2. 설치 스크립트 다운로드 및 실행 (2026년 8월 31일 기준)
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.7/install.sh | bash
```
2-3. 현재 쉘에 적용 (Optional)
```
source ~/.bashrc
```

### 2. nvm으로 node.js 설치

2-1. lts 버전 설치 (v24.20.0 - 2026년 8월 31일 기준)
```
nvm install --lts
```

2-2. `which node`로 `~/.nvm` 폴더에 있는지 확인하기

2-3. node를 설치 하면 `npm`과 `npx`도 같이 설치 된다.

### 3. nvm으로 설치 된 노드 버전 선택하기
lts 버전 선택하기
```
nvm use --lts
```
