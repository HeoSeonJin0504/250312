# 마크다운 실습
## 마크다운이란 무엇인가
1. 개요
    - 언제 생겼나?
      - 마크다운(Markdown)은 2004년 존 그루버(John Gruber)와 애론 스워츠(Aaron Swartz)가 함께 만든 경량 마크업 언어이이다.
      - 일반 텍스트 기반의 마크업 언어로, 쉽게 쓰고 읽을 수 있으며 HTML로 변환이 가능하다.
    - 누가 주로 사용하는가?
        - 개발자
          - 프로젝트 문서화, README 파일, 코드 문서 등을 작성할 때 사용한다.
          - GitHub, GitLab과 같은 코드 저장소에서 널리 사용된다.
        - 문서 작업자
          - 기술 문서, 블로그 포스트, 위키 페이지 등을 작성할 때 사용한다.
          - 복잡한 서식 없이 빠르게 문서를 작성할 수 있어 효율적이다.
        - 그 외에도 작가, 학생, 연구원 등도 사용한다.
2. 간단한 문법
    - 제목: `#` 기호를 사용하여 표시 (# 개수에 따라 h1~h6 태그로 변환)
    - 강조: `*이탤릭*`, `**굵게**`, `~~취소선~~`
    - 목록: `-`, `*`, `+` 기호로 순서 없는 목록, `1.`, `2.` 등으로 순서 있는 목록
    - 링크: `[링크텍스트](URL)`
    - 이미지: `![대체텍스트](이미지URL)`
    - 코드: `` `인라인 코드` ``, ` ```코드 블록``` `
    - 인용: `>` 기호로 인용문 표시
    - 표: `|` 와 `-`로 표 생성
3. 참고 사이트
    - Markdown 공식 사이트(John Gruber) - (https://daringfireball.net/projects/markdown/)
    - GitHub Markdown 가이드 - (https://docs.github.com/ko/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
    - CommonMark - (https://commonmark.org/) - 마크다운 표준화 프로젝트

## 깃허브에서는 README.md 파일을 왜 사용하는가?
- GitHub에서 README.md 파일은 저장소(repository)의 첫 페이지에 자동으로 표시되는 문서이다.
- 프로젝트의 소개, 설치 방법, 사용법, 기여 방법, 라이선스 등 중요한 정보를 제공한다.
- 방문자가 프로젝트를 이해하고 사용하는 데 필요한 첫 번째 문서 역할을 한다.
- 마크다운 형식으로 작성되어 텍스트 편집기에서 쉽게 편집할 수 있으면서도, GitHub에서 보기 좋게 렌더링된다.

- 참고 사이트
  - GitHub Docs - README 정보- (https://docs.github.com/ko/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-readmes)
  - GitHub Guides - Mastering Markdown - (https://guides.github.com/features/mastering-markdown/)

(과제: 조사하기, 커밋까지)
(git add .)
(git commit -m "마크다운 업데이트")