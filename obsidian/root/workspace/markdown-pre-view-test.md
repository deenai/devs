예시 문장

This document describes software safety requirements derived from the “Technical safety concept” of DAU that ISO26262 is required. ASIL A is allocated to UP and BACKWARD/FORWARD function. It is prepared in order to demonstrate that the technical safety concept for software is implemented and allocated to the appropriate unit.

이 문서에서는 ISO26262가 요구되는 DAU의 "기술적 안전 개념"에서 파생된 소프트웨어 안전 요구사항을 설명합니다. ASIL A는 UP 및 BACKWARD/FORWARD 기능에 할당됩니다. 소프트웨어에 대한 기술적 안전 개념이 구현되고 적절한 단위에 할당되었음을 입증하기 위해 준비되었습니다.


---
※ 마크다운에서 약속된 기호를 출력하기 위해서는 `\` 기호와 감께 작성하는 이스케이프(Escape) 처리가 필요합니다.


---
▶ 헤더 (Header)

# 제목1 (Heading1)
## 제목2 (Heading2)
### 제목3 (Heading3)
#### 제목4 (Heading4)
##### 제목5 (Heading5)
###### 제목6 (Heading6)


---
▶ 폰트 (Font)

이텔릭체는 *별 기호(Asterrisks)* 또는 _언더바 기호(Underscore)_ 를 사용하세요
볼드체는 **별 기호(asterisks)** 또는 __언더바 기호(underscore)__ 를 두 번씩 사용하세요
__*이텔릭체*와 볼드체__ 를 혼용할 수도 있습니다
하이라이트는 ==같음 기호(=)== 를 두 번씩 사용하세요

취소선은 ~~물결 기호(tilde)~~ 를 사용하세요
<u>밑줄</u>은 마크다운에서 지원하지 않으므로 직접 `<u></u>` 태그를 사용하세요


---
▶ 목록 (List)

`-` 로 시작하는 순서가 없는 목록으로 구분합니다.
1. 순서가 있는 항목
2. 순서가 있는 항목
	1. 순서가 있는 항목
	2. 순서가 있는 항목
3. 순서가 있는 항목
4. 순서가 있는 항목

- 순서가 없는 항목
- 순서가 없는 항목
	- 순서가 없는 항목
	- 순서가 없는 항목
- 순서가 없는 항목
- 순서가 없는 항목


---
▶ 인용문 (Quote)

> 인용문 - 남의 말이나 글에서 직접 또는 간접으로 따온 문장
> _(네이버 국어 사전)_

BREAK!

> 인용문을 작성하세요
>> 중첩된 인용문(nested blockquote)을 만들 수 있습니다
>>> 중중첩 인용문 1
>>> 중중첩 인용문 1
>>> 중중첩 인용문 1

> [!NOTE]
> 나는 생각한다 고로 나는 존재한다 - ChatGPT


---
▶ 코드블록 (Code) / 인라인 (Inline)

\` 를 3번 이상 입력하고 언어(코드) 이름을 명시하여 코드 블록을 표현합니다

```javascript
function add(a, b = 1) {
	console.log(a, b)
	return a + b
}
```

```bash
$ npm run dev
```

```python
s = "Python syntax highlighting"
print s
```

```plaintext
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

강조할 코드를 \` 기호로 감싸 인라인 코드를 표현합니다
`background` 또는 `background-image` 속성으로 요소에 배경 이미지를 삽입 할 수 있습니다.


---
▶ 수평선 (Horizontal)

\---
\***
\___


---
▶ 문단

(줄 바꿈을 두 번 하면 된다)

첫째 문단입니다, 문장이 두 개죠

둘째 문단입니다, 저도
문장이 두 개 입니다.

---
▶ 링크 (Links)

[GOOGLE](https://google.com)
[NAVER](https://naver.com "링크설명(title)을 작성하세요")
[상대적참조](devs/NOTICE)

[Dribbble][Dribbble Link]
[Github][1]

문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.
다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.

구글 홈페이지: https://google.com
네이버 홈페이지: <https://naver.com>

[Dribbble Link]: https://dribbble.com
[1]: https://github.com


---
▶ 이미지 (Images)

`![대체텍스트](이미지주소)`
`![대체텍스트](이미지주소 "설명")`
`![대체텍스트][참조]`

`[참조]: 이미지주소`
`[참조]: 이미지주소 "설명"`

![local image](lets_enhance.jpg)

이미지에 링크 추가 : 마크다운 이미지 문법 코드를 링크 문법 코드로 감싸줍니다
`[![HEROPY.DEV](/favicon.png)](https://heropy.dev/)`


---
▶ 표 (Table)

| 값        | 의미                        | 기본값      |
| :------- | :------------------------ | :------- |
| static   | 유형(기준) 없음 / 배치 불가능        | `static` |
| relative | ==요소 자신==을 기준으로 배치        |          |
| absolute | 위치상 **부모(조상)요소**를 기준으로 배치 |          |
| fixed    | 브라우저 창을 기준으로 배치           |          |
| sticky   | *스크롤 영역* 기준으로 배치          |          |


---
▶ 체크박스 (Checkbox)

- [ ] 체크박스 1
- [x] 체크박스 2
- [ ] 체크박스 3
- [x] 체크박스 4


---
▶ 주석 (Comment)

-- 시작 --
<!-- 안녕하세요 -->
[//]: # (안녕하세요)
[//]: # "안녕하세요"
[//]: # '안녕하세요'
-- 종료 --
