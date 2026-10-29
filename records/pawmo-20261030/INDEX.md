# 빠모트 (0922 · Pawmo) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 093fec5 · 2026-10-29T22:31:21.021Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 922 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 404 | `001b5cef7d50` | `빠모트_light_glossy_promo_f.webp` |
| ② | heavy | ① 빠모트_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `f8e1870dc6f0` | `빠모트_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 빠모트_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `ab90e2133ac4` | `빠모트_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 빠모트_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `e64e8de84099` | `빠모트_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 빠모트_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `947f1eb4190d` | `빠모트_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 빠모트_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `494f50889d9a` | `빠모트_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 빠모트_light_glossy_promo_f.webp | `casual1-prompt.txt` | 792 | `a849644af6f7` | `빠모트_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 빠모트_light_glossy_promo_f.webp | `casual2-prompt.txt` | 705 | `ff6c7dba9228` | `빠모트_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 빠모트_light_glossy_promo_f.webp | `casual3-prompt.txt` | 622 | `9e978be6cb0c` | `빠모트_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 페리 갑판 · 여행지 | the rail of a harbour ferry deck in the wind |
| 하는 일 | 창밖·풍경 바라보기 · 서기 | looking out at the view, one hand resting on the nearest ledge |
| 의상 계열 | 전통 의상 | a traditional dress that suits her, worn naturally — the traditional dress named in Outfit wins over her apparent ethnicity and the attached image's costume |
| 옷 | 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |

옷 종류 blouse · 드러내기 bare midriff, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 거실 · 집 | her living room with a deep sofa, floor cushions and a low table |
| 하는 일 | 사진 고르기 · 앉기 | sorting printed photographs beside a camera and a scrapbook |
| 의상 계열 | 란제리풍 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 옷 | 백스트랩 | a lingerie set with a decorative strap arrangement across the upper back |

옷 종류 lingerie_set · 드러내기 high-cut leg, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 화실·공방 · 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 하는 일 | 스케치하기 · 앉기 | sketching the scenery in a small notebook |
| 의상 계열 | 홈웨어 | soft homewear or loungewear |
| 옷 | 오프숄더 니트 | an off-shoulder knit top slipping from one shoulder over shorts |

옷 종류 knit_top + shorts · 드러내기 mini length, off-shoulder neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
