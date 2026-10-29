# 콩알뚜기 (0919 · Nymble) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5466246 · 2026-10-29T16:13:04.350Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 919 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 420 | `b3bb49de4888` | `콩알뚜기_light_glossy_promo_f.webp` |
| ② | heavy | ① 콩알뚜기_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `f06f6d9d69a2` | `콩알뚜기_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 콩알뚜기_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `5047fb2edab3` | `콩알뚜기_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 콩알뚜기_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `47ffbd5850e5` | `콩알뚜기_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 콩알뚜기_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `bbdae94405d6` | `콩알뚜기_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 콩알뚜기_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `8998a74c01c2` | `콩알뚜기_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 콩알뚜기_light_glossy_promo_f.webp | `casual1-prompt.txt` | 738 | `56bd14e024c7` | `콩알뚜기_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 콩알뚜기_light_glossy_promo_f.webp | `casual2-prompt.txt` | 673 | `844c20624c26` | `콩알뚜기_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 콩알뚜기_light_glossy_promo_f.webp | `casual3-prompt.txt` | 695 | `4a808d489da8` | `콩알뚜기_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 실내 암벽 · 운동 | an indoor climbing wall of coloured holds |
| 하는 일 | 물 마시며 숨 고르기 · 서기 | catching her breath with a water bottle |
| 의상 계열 | 운동복 | activewear made for the activity |
| 옷 | 자동 — 계열 안에서 장면에 맞게 |  |

옷 종류 crop_top + shorts · 드러내기 one-shoulder cut, cropped hem · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 · 나무열매·요리 | a village market stall piled with fresh berries |
| 하는 일 | 노점 음식 사기 · 서기 | buying a paper-wrapped snack at a stall |
| 의상 계열 | 평상복 | everyday clothes that suit the place and activity |
| 옷 | 멜빵바지 | fitted denim overalls over a cropped top |

옷 종류 crop_top + overalls · 드러내기 mini length, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 하맘 · 목욕·스파 | a domed marble hammam with warm stone slabs and brass bowls |
| 하는 일 | 차 따르기 · 앉기 | pouring herbal tea, relaxed and unhurried |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 수영복 위 유카타 | swimwear with a light yukata worn open over it |

옷 종류 traditional · 드러내기 high thigh slit, one-shoulder cut · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
