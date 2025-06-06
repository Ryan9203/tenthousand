# 일만시간의법칙

---

반응형 일만시간의 법칙 페이지 제작

---

## 파일구조
```C
├─ main
│    ├─ index.html
│    ├─ main-phone-style.css
│    ├─ main-style.css
│    └─ img
├─ popup
│    ├─ popup.html
│    ├─ popup-style.css
│    ├─ popup-phone-style.css
│    └─ popup-img
├─ font.css
└─ reset.css
```
---

## 작업 사항

* 노션을 통해 공유된 요구사항 명세 및 Figma 디자인 적용

* 시멘틱 마크업을 최대한 작성하였으나. 노션 요구사항 명세를 잘못 이해하여 적응형, 1920px. 360px 화면을 제작
<img src="./main/img/readme/해상도대응.png" width="300"/>

* 시멘틱 마크업을 최대한 작성하여, 키보드 접근성이 용이함

* 모달창은 별도 html 파일에 제작하여 버튼 클릭>페이지 이동을 통해 임시로 모달 노출
<img src="./main/img/readme/pop.png" width="300"/>

## 구현 한계 및 학습 방향

* 배경 요소로서 사용되는 이미지에 대한 처리 방식
1. 배포시 이미지 분실
2. 배경으로서 위치 지정
3. 이미지 삽입 방식
<img src="./main/img/readme/이미지분실.png" width="300"/>

* Form 태그에 대한 학습과 이해가 필요
<img src="./main/img/readme/플레이스홀더.png" width="300"/>
