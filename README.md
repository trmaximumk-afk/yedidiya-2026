# 여디디야 2026 통합사역 기획(안)

**두 개의 시간, 하나의 공동체** — 모바일 최적화 단일 페이지.

| 파일 | 설명 |
|---|---|
| `index.html` | 기획안 웹페이지 (이 파일 하나로 완결) |
| `og.png` | 링크 공유 시 뜨는 미리보기 카드 (1200×630) |
| `README.md` | 이 문서 |

---

## 🚀 GitHub Pages로 발행하기 (웹 화면, 5분)

> 컴퓨터 명령어 없이, github.com 웹사이트에서 클릭만으로 됩니다.

**1. 저장소(repository) 만들기**
- github.com 로그인 → 우측 상단 **＋ → New repository**
- Repository name: 예) `yedidiya-2026`  *(이 이름이 주소에 들어갑니다)*
- **Public** 선택 → **Create repository**

**2. 파일 올리기**
- 저장소 화면에서 **Add file → Upload files**
- `index.html`, `og.png`, `README.md`를 끌어다 놓기 → **Commit changes**

**3. Pages 켜기**
- 저장소 상단 **Settings → 왼쪽 메뉴 Pages**
- Source: **Deploy from a branch** → Branch: **main** / **/(root)** → **Save**

**4. 주소 확인 (1~2분 후)**
- 같은 Pages 화면 상단에 주소가 뜹니다:
  `https://<내아이디>.github.io/yedidiya-2026/`

---

## 🔗 공유 미리보기(OG) 마무리 — 중요

발행 주소가 정해지면, `index.html` 상단의 두 줄에서 `USERNAME`·`REPO`를 실제 값으로 바꿔주세요.

```html
<meta property="og:url"   content="https://USERNAME.github.io/REPO/">
<meta property="og:image" content="https://USERNAME.github.io/REPO/og.png">
```

예) 아이디가 `bumsoo`, 저장소가 `yedidiya-2026`이면
```html
<meta property="og:url"   content="https://bumsoo.github.io/yedidiya-2026/">
<meta property="og:image" content="https://bumsoo.github.io/yedidiya-2026/og.png">
```

수정 후 다시 **Commit**하면 카카오톡·SNS 공유 시 `og.png` 카드가 표시됩니다.

> 💡 카카오톡은 미리보기를 캐시합니다. 안 바뀌면 주소 끝에 `?v=2`를 붙여 공유하거나, [카카오 디버거](https://developers.kakao.com/tool/clear/og)·[페이스북 디버거](https://developers.facebook.com/tools/debug/)로 캐시를 갱신하세요.

---

## (선택) 짧고 예쁜 주소
- **커스텀 도메인**: Settings → Pages → Custom domain 에 보유 도메인 입력.
- **저장소명 = 아이디.github.io** 로 만들면 주소가 `https://<아이디>.github.io/` 로 더 짧아집니다.

---

*여디디야 청년부 · 총무 김범수 · 2026 · 검토용 초안*
