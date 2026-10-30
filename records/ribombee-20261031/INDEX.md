# 에리본 (0743 · Ribombee) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 76f624d · 2026-10-30T16:49:52.830Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 743 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 413 | `b2fa3aa5cccf` | `에리본_light_glossy_promo_f.webp` |
| ② | heavy | ① 에리본_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `218c8cd70cbd` | `에리본_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 에리본_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `02c6604bd053` | `에리본_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 에리본_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `8f7a1a265fff` | `에리본_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 에리본_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `ca595460b853` | `에리본_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 에리본_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `1743394ea368` | `에리본_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 에리본_light_glossy_promo_f.webp | `casual1-prompt.txt` | 791 | `62c338ee58f5` | `에리본_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 에리본_light_glossy_promo_f.webp | `casual2-prompt.txt` | 766 | `ca25d9f55425` | `에리본_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 에리본_light_glossy_promo_f.webp | `casual3-prompt.txt` | 682 | `0c443326837e` | `에리본_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그루밍 매트 있는 방 | a sunny room with a grooming mat, a towel and a small brush basket |
| 역할 | — |  |
| 의상 | 무대·판타지 의상 · 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |
| 몸 자세 · 구도 | 기대 눕기 · environmental · 3/4 정면 | reclining on her back |
| 손 · 소품 동작 | behind_head · prop · 책 · 책을 안는다 | holds a book closed against her chest |

옷 종류 dress + robe · 드러내기 open back, mini length · 장면 칸 첫머리 — · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 촛불 예배당 | an old stone chapel lit by candles |
| 역할 | — |  |
| 의상 | 역할극·직업 의상 · 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |
| 몸 자세 · 구도 | 서기 · chest_up · 3/4 정면 | standing |
| 손 · 소품 동작 | prop · out · 꽃다발 · 꽃향기를 맡는다 | brings a small bouquet up to her face to smell the flowers |

옷 종류 jacket + shorts + uniform · 드러내기 open back, cropped hem · 장면 칸 첫머리 — · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 기차 침대칸 | a night-train sleeper compartment with a narrow berth, a fold-down table and a small window |
| 역할 | — |  |
| 의상 | 전통 의상 · 모로코 카프탄 | a Moroccan evening caftan — a long embroidered robe with a decorated belt |
| 몸 자세 · 구도 | 엎드리기 · full_body · 정면 | lying on her front |
| 손 · 소품 동작 | chin_both · chin_both |  |

옷 종류 robe · 드러내기 open back, mini length · 장면 칸 첫머리 place · 직접 입력 scene, outfit
