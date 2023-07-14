---
title: "블로그: 생성하기"
categories:
  - Blog
tags:
  - blog
  - github
---

## GitHub Pages를 사용하여 블로그 만들기

### 1. GitHub 계정 생성 및 로그인

먼저, [GitHub](https://github.com/)에 계정이 없다면 계정을 생성하고 로그인합니다.

### 2. 새로운 저장소 생성

GitHub에서 새로운 저장소를 생성합니다. 저장소 이름은 `<username>.github.io` 형식이어야 합니다. `<username>`은 여기서 당신의 GitHub 아이디를 나타냅니다.

### 3. Jekyll 테마 선택 및 포크

[Jekyll Themes](https://jekyllthemes.io/github-pages-themes)에서 마음에 드는 테마를 선택합니다. 선택한 테마의 GitHub 페이지로 이동하여 'Fork' 버튼을 클릭하여 테마의 저장소를 당신의 GitHub 계정으로 복사합니다.

### 4. 포크한 저장소의 이름 변경

포크한 저장소로 이동하여 'Settings'를 클릭하고, 저장소 이름을 `<username>.github.io`로 변경합니다.

### 5. _config.yml 파일 수정

포크한 저장소에서 _config.yml 파일을 찾아 수정합니다. 이 파일에는 사이트 제목, 설명, 아이콘, 주소 등을 설정할 수 있습니다. 이 파일의 설정은 사용하는 Jekyll 테마에 따라 다르므로, 테마의 문서를 참고하세요.

### 6. 포스트 작성

_posts 디렉토리에 새로운 Markdown 파일을 생성하여 포스트를 작성합니다. 파일 이름은 'YYYY-MM-DD-title.md' 형식이어야 합니다. 예를 들면, '2023-07-07-first-post.md'가 됩니다.

### 7. 변경 사항 커밋 및 푸시

변경 사항을 커밋하고 푸시합니다. 커밋 메시지는 변경 사항을 간결하게 설명해야 합니다.

### 8. 블로그 확인

웹 브라우저에서 `https://<username>.github.io` 주소로 접속하면, GitHub Pages를 통해 생성한 블로그를 확인할 수 있습니다.

이제 GitHub Pages를 사용하여 자신만의 블로그를 제작하는 방법에 대해 알게 되었습니다. 더욱 세부적인 설정을 위해서는 Jekyll과 Markdown에 대한 지식이 필요하므로, 필요하다면 이에 대해 추가로 학습하시는 것이 좋습니다.
