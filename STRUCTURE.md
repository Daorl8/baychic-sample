# STRUCTURE · baychic-sample

```
baychic-sample/
├─ index.html              단일 파일 (CSS·JS 인라인)
├─ wrangler.toml           name = baychic-sample → baychic-sample.lgt3232.workers.dev
├─ .assetsignore           img/ · 문서 · index_*.html · _deploy · bc-cat.png 배포 제외
├─ bc-fraunces.woff2       영문 제목 (Fraunces 600–800, 라틴만)
├─ bc-jua.woff2            한글 표시 (Jua, 사용 글자만)
├─ bc-pretendard.woff2     본문 (Pretendard 400–700, 사용 글자만)
├─ bc-cat.webp             고양이 + Bay Chic 글씨 투명 (히어로 · 푸터 · og) · bc-cat.png 원본
├─ bc-cat-face.webp        고양이 얼굴만 (헤더 · 라인업)
├─ bc-hero.webp            히어로 무화과 샌드베이글
├─ bc-sb-*.webp            샌드베이글 6장
├─ bc-bagel / bc-brownie / bc-bag / bc-giftbag .webp
├─ favicon.png / og-baychic.jpg
├─ img/                    다올 제공 원본 89장 (배포 제외)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더 → 히어로 → `.band`(라인업 마키) → `#sandbagel` → `#dessert`(흰 면) → 포장 → `#lineup`(검정 면) → `#visit` → 푸터 + 모바일 `.quick`.

## 라인업 마키 수정
`#band` 안의 `<span>메뉴명</span><i>·</i>` 쌍을 추가 · 삭제. JS가 자동으로 두 번 이어 붙여 돌림.

## 영업시간 수정 (4곳)
히어로 `.hours` · Visit `.info` · 푸터 · head JSON-LD.

## 폰트 재생성
문구를 바꾸면 항상 빠진 글자 검사(LESSONS §26). Fraunces는 instancer로 wght 600–800 · opsz 72 · SOFT 100 · WONK 0 고정 후 서브셋.
