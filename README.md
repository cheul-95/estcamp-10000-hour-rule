
# 📘 1만 시간의 법칙 계산기

> **"연습은 어제의 당신보다 당신을 더 낫게 만든다."**  
> 하루 훈련 시간을 입력하면 1만 시간을 채우기 위해 필요한 일수를 계산해주는 랜딩 페이지입니다.

---

## 🖥️ 데모

[👉 데모 페이지 보러가기](https://cheul-95.github.io/estcamp-10000-hour-rule/)  

---

## 🧩 기술 스택

- **HTML5**: 시맨틱 마크업 기반 구조 설계  
- **CSS3**: 모바일 퍼스트 반응형 디자인  
- **BEM**: 유지보수를 고려한 CSS 네이밍 컨벤션 적용  
- **미디어쿼리**: 다양한 해상도 대응을 위한 레이아웃 구현

---

## 📸 화면 구성 미리보기

<table align="center">
  <tr>
    <th align="center">💻 데스크탑 화면</th>
    <th align="center">📱 모바일 화면</th>
  </tr>
  <tr>
    <td align="center" valign="top">
      <img src="./img/1만시간-pc.png" alt="Desktop View" width="400">
    </td>
    <td align="center" valign="top">
      <img src="./img/1만시간-m.png" alt="Mobile View" width="250">
    </td>
  </tr>
</table>

---

## 📁 프로젝트 구조

```
estcamp-10000-hour-rule/
├── css/
│   ├── reset.css         # 브라우저 스타일 초기화
│   └── style.css         # 페이지 스타일 정의
├── font/                 # 폰트 리소스
├── img/                  # 이미지 리소스
├── index.html            # 메인 HTML 페이지
└── README.md             # 프로젝트 설명 문서
```

---

##  ✨ 주요 기능

- ⏰ 1만 시간 계산기 기능 (하루 훈련 시간 기반 일수 계산)
- 📱 반응형 웹 구현 (모바일 중심 설계)
- 🎯 모달 팝업 UI 구현
- ♿ 웹 접근성 요소 고려 (`aria-label`, 시맨틱 태그 사용 등)
- 🔍 SEO 최적화 (메타 태그, 시멘틱 구조)

---

## 📌 개발 중 어려웠던 점

✅ CSS 네이밍: BEM(Block Element Modifier) 방식 적용

처음으로 BEM(Block Element Modifier) 방식을 도입해 보았습니다.  
초반에는 어떤 네이밍이 적절할지 고민이 많았지만, 익숙해질수록 클래스 이름만 보고도 구조를 파악할 수 있어 가독성과 유지보수에 큰 도움이 되었습니다.

<<<<<<< HEAD
✅ 웹 접근성 고려
=======
✅ 반응형 디자인
  - Desktop: max-width: 1280px
  - Mobile: max-width: 720px
    
✅ 접근성 향상 요소
  - label, aria-label, alt 등을 적절히 활용
  
✅ 검색엔진 최적화(SEO)
  - meta 태그: description, keywords, author 설정
>>>>>>> 742e1e96a013d35e778c6cbf886baec0108663a7

웹 접근성 이론을 어느 정도 학습한 후 시작했지만, 실제 코드에 어떻게 반영해야 할지는 여전히 고민이 많았습니다.  
`aria-*`, `role`, 시맨틱 태그의 올바른 사용을 위해 [MDN 문서](https://developer.mozilla.org/ko/)와 AI의 도움을 함께 참고하였습니다.

---

## 📝 피드백 반영 사항

- `img` 태그의 `alt` 속성: 로고일 경우 `alt=""`로 처리하여 스크린리더에서 제외
- 장식용 이미지는 `background`나 `::before` 가상 요소로 처리
- `dialog` 요소의 `max-width`, 내부 여백 조정으로 모달 시각적 개선
- 입력창은 `type="number"` 속성을 통해 숫자만 입력 가능하도록 설정

---

## 🙋‍♀️ 제작자

- SC LEE  
- GitHub: [@cheul-95](https://github.com/cheul-95)
