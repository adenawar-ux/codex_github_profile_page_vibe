# GitHub Pages Developer Portfolio

정적 HTML/CSS/JavaScript만 사용하는 개발자 포트폴리오 템플릿입니다. 빌드 단계 없이 GitHub Pages의 프로젝트 페이지로 배포할 수 있습니다.

## 파일 구조

```text
.
├── index.html
├── styles.css
├── script.js
└── assets/
    ├── portfolio-hero.png
    ├── project-analytics.png
    ├── project-automation.png
    └── project-design-system.png
```

## 수정할 내용

- `index.html`의 이름, 소개, 이메일, GitHub, LinkedIn 링크를 실제 정보로 교체합니다.
- 대표 프로젝트 3개의 제목, 문제/해결 설명, 기술 태그, Demo/Code 링크를 교체합니다.
- `assets/`의 이미지를 실제 프로필 또는 프로젝트 이미지로 바꿀 수 있습니다. 같은 파일명을 유지하면 HTML 수정 없이 교체됩니다.

## GitHub Pages 배포

1. 저장소에 파일을 커밋하고 GitHub에 푸시합니다.
2. GitHub 저장소의 `Settings` → `Pages`로 이동합니다.
3. `Build and deployment`에서 `Deploy from a branch`를 선택합니다.
4. Branch는 `main`, 폴더는 `/root`를 선택하고 저장합니다.
5. 잠시 후 `https://username.github.io/repository-name/`에서 확인합니다.
