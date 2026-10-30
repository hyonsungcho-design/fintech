# 검색 대상 국내 언론사 50곳

이 목록의 언론사 기사만 페이지에 싣는다. 포털(네이버·다음·네이트)을 거친 기사는 원 언론사가 목록에 있으면 싣고, 이때 URL은 가능하면 원 언론사 주소로 바꾼다.

## 검색 차단 도메인 (8곳)

아래 도메인은 `WebSearch`가 접근을 막아 `allowed_domains`에 넣으면 쿼리 전체가 오류로 끝난다. **검색 그룹에 넣지 않는다.** 다른 경로(포털 재게재 등)로 이 언론사 기사를 찾았고 원 언론사가 확인되면 싣는다.

| 언론사 | 도메인 |
|---|---|
| 매일경제 | mk.co.kr |
| 조선일보 | chosun.com |
| 중앙일보 | joongang.co.kr |
| 동아일보 | donga.com |
| 한겨레 | hani.co.kr |
| KBS | kbs.co.kr |
| 연합뉴스 | yna.co.kr |
| 연합인포맥스 | einfomax.co.kr |

차단 여부는 2026-10-31에 확인했다. 오류 메시지에 새 도메인이 나오면 이 표로 옮긴다.

## 검색 그룹 (42곳)

`WebSearch`의 `allowed_domains`에는 아래 그룹 단위로 도메인을 넣는다.

### 그룹 AB — 종합일간지·통신·방송 (14)

| 언론사 | 도메인 |
|---|---|
| 경향신문 | khan.co.kr |
| 한국일보 | hankookilbo.com |
| 국민일보 | kmib.co.kr |
| 서울신문 | seoul.co.kr |
| 세계일보 | segye.com |
| 문화일보 | munhwa.com |
| 뉴시스 | newsis.com |
| 뉴스1 | news1.kr |
| MBC | imbc.com |
| SBS Biz | sbs.co.kr |
| YTN | ytn.co.kr |
| 한국경제TV | wowtv.co.kr |
| MTN 머니투데이방송 | mtn.co.kr |
| 메트로신문 | metroseoul.co.kr |

### 그룹 C — 경제지 (9)

| 언론사 | 도메인 |
|---|---|
| 한국경제 | hankyung.com |
| 서울경제 | sedaily.com |
| 머니투데이 | mt.co.kr |
| 파이낸셜뉴스 | fnnews.com |
| 헤럴드경제 | heraldcorp.com |
| 아시아경제 | asiae.co.kr |
| 이데일리 | edaily.co.kr |
| 아주경제 | ajunews.com |
| 이투데이 | etoday.co.kr |

### 그룹 D — 경제지·IT (10)

| 언론사 | 도메인 |
|---|---|
| 뉴스핌 | newspim.com |
| 데일리안 | dailian.co.kr |
| 글로벌이코노믹 | g-enews.com |
| 뉴데일리경제 | newdaily.co.kr |
| 전자신문 | etnews.com |
| 디지털타임스 | dt.co.kr |
| 지디넷코리아 | zdnet.co.kr |
| 아이뉴스24 | inews24.com |
| 블로터 | bloter.net |
| 비즈니스포스트 | businesspost.co.kr |

### 그룹 E — 금융 전문지 (9)

| 언론사 | 도메인 |
|---|---|
| 서울파이낸스 | seoulfn.com |
| 대한금융신문 | kbanker.co.kr |
| 한국금융신문 | fntimes.com |
| 더벨 | thebell.co.kr |
| 딜사이트 | dealsite.co.kr |
| 비즈니스워치 | bizwatch.co.kr |
| 파이낸셜포스트 | financialpost.co.kr |
| 더밸류뉴스 | thevaluenews.co.kr |
| CEO스코어데일리 | ceoscoredaily.com |

## 사용 규칙

- 페이지의 `outlet` 값에는 위 표의 **언론사 이름을 그대로** 쓴다(예: "헤럴드경제", "SBS Biz").
- 도메인이 목록에 없는 기사(블로그, 카드 비교 사이트, 이벤트 페이지, 목록 밖 매체)는 싣지 않는다.
- 하위 도메인 매체는 그 매체 이름으로 싣는다(예: sports.khan.co.kr → 스포츠경향은 목록 밖이므로 제외, marketin.edaily.co.kr → 이데일리).
- 목록을 바꾸고 싶으면 이 파일만 고친다.
