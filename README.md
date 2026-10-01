# HTML 태그 정리

웹프로그래밍에서 자주 사용하는 HTML 태그를 용도별로 정리한 문서입니다.

---

## 1. 기본 HTML 구조

| 태그 | 설명 | 예시 |
|---|---|---|
| `<html>` | HTML 문서 전체를 감쌈 | `<html>...</html>` |
| `<head>` | 문서의 정보, CSS, JS 등을 포함 | `<head>...</head>` |
| `<title>` | 브라우저 탭에 표시되는 제목 | `<title>홍준석 홈페이지</title>` |
| `<body>` | 실제 화면에 표시되는 내용 | `<body>내용</body>` |
| `<!DOCTYPE html>` | HTML5 문서임을 선언 | `<!DOCTYPE html>` |

---

## 2. 글자 / 문단 관련

| 태그 | 설명 | 예시 |
|---|---|---|
| `<h1>` ~ `<h6>` | 제목 | `<h1>제목</h1>` |
| `<p>` | 문단 | `<p>안녕하세요.</p>` |
| `<br>` | 줄바꿈 | `안녕<br>하세요` |
| `<hr>` | 수평선 | `<hr>` |
| `<strong>` | 중요한 내용, 굵게 표시 | `<strong>중요</strong>` |
| `<b>` | 굵은 글씨 | `<b>굵은 글씨</b>` |
| `<em>` | 강조, 보통 기울임 | `<em>강조</em>` |
| `<i>` | 기울임 글씨 | `<i>기울임</i>` |
| `<small>` | 작은 글씨 | `<small>참고사항</small>` |
| `<mark>` | 형광펜 효과 | `<mark>중요</mark>` |
| `<del>` | 삭제된 내용 | `<del>삭제</del>` |

---

## 3. 링크 / 이미지

| 태그 | 설명 | 예시 |
|---|---|---|
| `<a>` | 하이퍼링크 | `<a href="https://example.com">링크</a>` |
| `<img>` | 이미지 삽입 | `<img src="photo.jpg" alt="사진">` |
| `<figure>` | 이미지 등의 독립적인 콘텐츠 묶음 | `<figure>...</figure>` |
| `<figcaption>` | 이미지 설명 | `<figcaption>사진 설명</figcaption>` |

### 링크 예제

```html
<a href="https://www.google.com">구글 바로가기</a>
