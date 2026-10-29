# 곤율거니 (0560 · Scrafty) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5466246 · 2026-10-29T15:49:35.764Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 560 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 404 | `13f6f4505651` | `곤율거니_light_glossy_promo_f.webp` |
| ② | heavy | ① 곤율거니_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `4eb09e66a8f0` | `곤율거니_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 곤율거니_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `6aab8448a986` | `곤율거니_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 곤율거니_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `0fc94ae1e39f` | `곤율거니_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 곤율거니_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `f378852a35f3` | `곤율거니_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 곤율거니_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `920c449d4569` | `곤율거니_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 곤율거니_light_glossy_promo_f.webp | `casual1-prompt.txt` | 860 | `5ac96f2961a8` | `곤율거니_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 곤율거니_light_glossy_promo_f.webp | `casual2-prompt.txt` | 631 | `3f3100afaca2` | `곤율거니_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 곤율거니_light_glossy_promo_f.webp | `casual3-prompt.txt` | 639 | `aa669cf94f80` | `곤율거니_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 온천 · 포켓몬 세계 | an outdoor hot spring of a Pokémon-world mountain town, steam over smooth rocks |
| 하는 일 | 수영하기 · 움직임 | swimming breaststroke, her head and shoulders above the water |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 스포티 원피스 | a sporty one-piece swimsuit with a racerback and a high neckline |

옷 종류 swimsuit · 드러내기 high-cut leg, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 성 계단 · 환상 무대 | the grand staircase of an old castle |
| 하는 일 | 계단 오르기 · 걷기 | climbing a grand staircase, lifting her hem |
| 의상 계열 | 웨딩 | bridal wear |
| 옷 | 슬립 웨딩드레스 | a simple slip wedding dress with a long veil |

옷 종류 dress + slip · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 온천 마을 족욕 · 목욕·스파 | a hot-spring town footbath under a wooden roof |
| 하는 일 | 천천히 거닐기 · 걷기 | strolling through the place at an easy pace |
| 의상 계열 | 전통 의상 | a traditional dress that suits her, worn naturally — the traditional dress named in Outfit wins over her apparent ethnicity and the attached image's costume |
| 옷 | 사리 | a formal Indian sari — a long silk drape pleated at the waist with the pallu over one shoulder and a fitted choli |

옷 종류 traditional · 드러내기 one-shoulder cut, off-shoulder neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit
