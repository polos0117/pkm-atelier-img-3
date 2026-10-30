# 늑골라 (0565 · Carracosta) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 f10d507 · 2026-10-29T23:40:06.361Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 565 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 431 | `b92e4be8874a` | `늑골라_light_glossy_promo_f.webp` |
| ② | heavy | ① 늑골라_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `2de0e797d003` | `늑골라_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 늑골라_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `9c6c9108bc5b` | `늑골라_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 늑골라_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `9e0675e569ab` | `늑골라_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 늑골라_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `4053a2e0fa62` | `늑골라_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 늑골라_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `e97a5c0ecbbf` | `늑골라_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 늑골라_light_glossy_promo_f.webp | `casual1-prompt.txt` | 745 | `54ef39c1c772` | `늑골라_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 늑골라_light_glossy_promo_f.webp | `casual2-prompt.txt` | 785 | `0d8aea9e8bf6` | `늑골라_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 늑골라_light_glossy_promo_f.webp | `casual3-prompt.txt` | 774 | `e9843471962d` | `늑골라_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 조용한 정원 · 동료 포켓몬과 함께 | a quiet garden with a feeding bowl set on the grass |
| 하는 일 | 장난감 놀이 · 무릎·쪼그림 | rolling a soft toy ball toward her playful Pokémon companion |
| 의상 계열 | 평상복 | everyday clothes that suit the place and activity |
| 옷 | 니트 + 레깅스 | a chunky knit sweater and leggings |

옷 종류 leggings + sweater · 드러내기 cropped hem, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 연습실 · 운동 | a mirrored dance, yoga or Pilates studio with a wooden floor |
| 하는 일 | 몸풀기 · 움직임 | warming up in a forward lunge stretch, both hands resting on her front knee |
| 의상 계열 | 운동복 | activewear made for the activity |
| 옷 | 스포츠 브라 + 레깅스 | a sports bra and high-waisted leggings |

옷 종류 crop_top + leggings · 드러내기 one-shoulder cut, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 항구 마을 지붕 테라스 · 포켓몬 세계 | a rooftop terrace above a Pokémon-world harbor town |
| 하는 일 | 창밖·풍경 바라보기 · 서기 | looking out at the view, one hand resting on the nearest ledge |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 홀터 비키니 | a halter bikini with a neck tie and an underbust band |

옷 종류 bikini · 드러내기 high-cut leg, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit
