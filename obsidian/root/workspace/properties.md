---
tags:
  - TAG1
  - TAG2
  - TAG3
aliases:
  - ALIAS1
  - ALIAS2
plaintext: plaintext
list:
  - aaaa
  - bbbb
  - cccc
  - dddd
number: 12345
checkbox: false
date: 2024-12-19
date & time: 2024-12-20T12:00:00
---


1. 메타데이터 제공
2. 문서 관리 향상
3. 플러그인과의 상호작용


- **Text**: 기본적인 텍스트 형식의 메타데이터입니다.
- **List**: 여러 텍스트 항목을 추가할 수 있는 리스트 형식입니다.
- **Number**: 정수나 소수를 입력할 수 있는 숫자 형식입니다.
- **Checkbox**: true/false 옵션을 위한 체크박스 형식입니다.
- **Date**: 날짜를 입력할 수 있는 필드로, ISO 8601 형식(예: 2024-08-11)을 사용합니다.
- **DateTime**: 날짜와 시간을 모두 포함하는 필드로, 12시간 형식으로 표시됩니다.


1. tags
    문서를 주제별로 분류하고 검색하는 데 사용합니다. `tags: [태그1, 태그2]` 형식으로 작성합니다.
    자세한건 [태그](https://kaminik.tistory.com/entry/%EC%98%B5%EC%8B%9C%EB%94%94%EC%96%B8%EC%9D%98-%EA%B8%B0%EC%B4%88-10-%ED%83%9C%EA%B7%B8Tags)참조
2. aliases
    문서에 다양한 별칭을 부여하여, 다른 문서에서 쉽게 참조할 수 있습니다. 예: `aliases: ["별칭1", "별칭2"]`.
3. cssClasses
    특정 CSS 스타일을 문서에 적용하여, 시각적인 맞춤화를 가능하게 합니다. 예: `cssClasses: "CustomStyle"`.
4. publish
    문서의 출판 여부를 결정합니다. Obsidian Publish 기능과 연동되어 사용됩니다.


- **템플릿 사용**: Templater 플러그인을 사용하여 프로퍼티를 자동화할 수 있습니다.
- **Dataview 출력**: Dataview 플러그인을 사용하여 프로퍼티를 출력 및 가공할 수 있습니다.
- **맞춤형 메타데이터**: 사용자의 필요에 따라 특정 프로젝트, 연구 노트, 책 리뷰 등에 맞는 맞춤형 프로퍼티 를 생성할 수 있습니다.

