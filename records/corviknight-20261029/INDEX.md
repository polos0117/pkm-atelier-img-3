# 아머까오 (0823 · Corviknight) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 ea5e96b · 2026-10-29T12:39:30.103Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 823 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 401 | `1dcd62796051` | `아머까오_light_glossy_promo_f.webp` |
| ② | heavy | ① 아머까오_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `0d7434d59399` | `아머까오_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 아머까오_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `6143de35f5c4` | `아머까오_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 아머까오_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `1c14b2047dd4` | `아머까오_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 아머까오_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `8de657d125df` | `아머까오_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 아머까오_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `5e819f5a9b3b` | `아머까오_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 아머까오_light_glossy_promo_f.webp | `casual1-prompt.txt` | 874 | `336c36cfc892` | `아머까오_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 아머까오_light_glossy_promo_f.webp | `casual2-prompt.txt` | 739 | `b66d0284f6d9` | `아머까오_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 아머까오_light_glossy_promo_f.webp | `casual3-prompt.txt` | 684 | `4409a2935312` | `아머까오_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 화실·공방 · 화실·공방 | an art or pottery studio of easels, clay and paint-splattered tables |
| 하는 일 | 비즈 공예 · 앉기 | threading beads into a small charm with tidy craft tools |
| 의상 계열 | 홈웨어 | soft homewear or loungewear |
| 옷 | 오프숄더 니트 | an off-shoulder knit top slipping from one shoulder over shorts |

옷 종류 knit_top + shorts · 드러내기 cropped hem, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 옥상 파티 · 밤 문화 | a city rooftop party under string lights |
| 하는 일 | 춤추기 · 움직임 | dancing to the beat, one hand raised |
| 의상 계열 | 저녁 드레스 | an evening dress or night-out outfit |
| 옷 | 슬립 위 실크 로브 | a silk robe over an evening slip |

옷 종류 robe + slip · 드러내기 high thigh slit, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 거실 · 집 | her living room with a deep sofa, floor cushions and a low table |
| 하는 일 | 앉아 쉬기 · 앉기 | resting on a seat for a moment, catching her breath |
| 의상 계열 | 란제리풍 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 옷 | 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |

옷 종류 slip · 드러내기 strapless top, plunging neckline · 장면 칸 첫머리 light · 직접 입력 scene, outfit
