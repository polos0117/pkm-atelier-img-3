# 깨봉이 (0568 · Trubbish) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 148397d · 2026-10-30T10:12:18.603Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 568 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 457 | `5ea33792d517` | `깨봉이_light_glossy_promo_f.webp` |
| ② | heavy | ① 깨봉이_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `031e7e1d1abb` | `깨봉이_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 깨봉이_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `0994b1ceb980` | `깨봉이_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 깨봉이_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 246 | `c1559cd80d4d` | `깨봉이_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 깨봉이_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 252 | `c7d949881e91` | `깨봉이_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 깨봉이_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 245 | `71acfe77d115` | `깨봉이_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 깨봉이_light_glossy_promo_f.webp | `casual1-prompt.txt` | 733 | `fa56f7fe1e97` | `깨봉이_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 깨봉이_light_glossy_promo_f.webp | `casual2-prompt.txt` | 701 | `c9f086fb2cb8` | `깨봉이_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 깨봉이_light_glossy_promo_f.webp | `casual3-prompt.txt` | 757 | `8d6c14bd6027` | `깨봉이_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 재즈바 | a dim jazz bar with a grand piano |
| 역할 | — |  |
| 의상 | 레트로 · 90년대 미니멀 슬립 | a 1990s minimal satin slip dress under a small cropped cardigan |
| 몸 자세 · 구도 | 벽에 기대 서기 · chest_up · 3/4 정면 | standing, leaning back against a wall |
| 손 · 소품 동작 | arms_crossed · arms_crossed |  |

옷 종류 cardigan + dress + slip · 드러내기 side cutouts, high thigh slit · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 별빛 무대 | a stage under a painted night sky of crystal stars |
| 역할 | — |  |
| 의상 | 란제리풍 · 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |
| 몸 자세 · 구도 | 바닥에 앉기 · three_quarter · 3/4 정면 | sitting on the ground |
| 손 · 소품 동작 | chin_knee · floor_brace |  |

옷 종류 slip · 드러내기 one-shoulder cut, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 야외 공연장 | an outdoor theatre of tiered seats facing a stage |
| 역할 | — |  |
| 의상 | 전통 의상 · 모로코 카프탄 | a Moroccan evening caftan — a long embroidered robe with a decorated belt |
| 몸 자세 · 구도 | 서기 · face_close · 옆모습 | standing |
| 손 · 소품 동작 | hair_tuck · out |  |

옷 종류 robe · 드러내기 halter neck, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit
