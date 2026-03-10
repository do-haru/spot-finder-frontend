# Spot Finder

## 서비스 소개

Spot Finder는 사용자가 **지역과 카테고리를 선택하여 지도 기반으로 장소 정보를 탐색할 수 있는 웹 서비스**입니다.

사용자는 지도 화면에 표시된 장소 마커를 통해 주변 장소 정보를 직관적으로 확인할 수 있으며, 목록 형태로도 장소 정보를 확인할 수 있습니다.

또한 사용자는 새로운 장소 정보를 직접 등록할 수 있으며, 등록 시 입력한 비밀번호를 통해 장소 정보를 수정하거나 삭제할 수 있도록 설계되었습니다.


## 주요 기능

### 지역 필터
사용자가 서울, 부산 등 원하는 지역을 선택하여 해당 지역의 장소 정보를 탐색할 수 있습니다.

### 카테고리 필터
맛집, 여행지 등의 카테고리를 선택하여 원하는 유형의 장소 정보를 탐색할 수 있습니다.

### 장소 노출 형태
사용자는 지도에 표시된 장소 정보를 지도 형태와 목록 형태로 확인할 수 있습니다.

### 장소 정보 확인
지도 마커 또는 목록에서 특정 장소를 클릭하면 장소 이름, 카테고리, 간단 설명 등의 정보를 확인할 수 있습니다.

### 장소 등록 및 관리
사용자는 새로운 장소 정보를 등록할 수 있으며, 등록 시 입력한 비밀번호를 통해 장소 정보를 수정하거나 삭제할 수 있습니다.

## 환경 요구사항
- Node.js 24.14.0
- npm
- React
- Vite

## 실행 방법

1. 저장소 클론

```bash
 git clone https://github.com/do-haru/spot-finder-frontend.git
 ```

2. 프로젝트 디렉토리 이동

```bash
cd spot-finder-frontend
```

3. 패키지 설치

```bash
npm install
```

4. 개발 서버 실행

```bash
npm run dev
```

5. 브라우저 접속

```http://localhost:5173```


## 디렉토리 구조
```
spot-finder-frontend
├─ public
│
├─ src
│  ├─ assets
│  ├─ App.css
│  ├─ App.jsx
│  ├─ index.css
│  └─ main.jsx
│
├─ .gitignore
├─ eslint.config.js
├─ index.html
├─ package.json
├─ package-lock.json
├─ vite.config.js
└─ README.md
```

디렉토리 설명

- public : 정적 파일을 저장하는 폴더
- src : React 애플리케이션의 소스 코드 폴더
- assets : 이미지 등 리소스 파일을 저장하는 폴더
- App.jsx : 애플리케이션의 루트 컴포넌트
- main.jsx : React 애플리케이션의 시작점 (React 앱을 DOM에 렌더링)