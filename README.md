# REVION ℞ — 약사가 처방하는 더마 코스메틱

피그마 디자인을 기반으로 제작한 정적 반응형 웹사이트.

## 페이지

| URL | 설명 |
|---|---|
| `index.html` | 메인 (히어로 슬라이드 / 제품 컬렉션 / 베스트셀러 / 인스타그램) |
| `about.html` | 브랜드 스토리 + 4가지 원칙 + 성분 사이언스 |
| `shop.html` | 상품 리스트 (필터 사이드바, 정렬) |
| `product.html` | 상품 상세 (갤러리 + 옵션 + 스티키 탭 + 리뷰/Q&A) |
| `pharmacy.html` | 약국찾기 (검색 + 칩 + 리스트 + 지도 핀) |
| `event.html` | 이벤트 (히어로 + 카드 그리드) |
| `community.html` | 커뮤니티 (리뷰 / Q&A / 미디어 탭) |
| `cart.html` | 장바구니 |
| `login.html` / `join.html` | 로그인 / 회원가입 |

## 기술 스택

- 정적 HTML / CSS / Vanilla JS
- 폰트: [Pretendard Variable](https://github.com/orioncactus/pretendard)
- 아이콘: 인라인 SVG (Lucide 스타일)
- `partials.js` — 헤더/푸터/마퀴/모달 공통 컴포넌트 주입
- `cart.js` — localStorage 기반 장바구니

## 로컬 실행

```bash
python3 -m http.server 4567
# http://localhost:4567
```
