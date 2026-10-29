# 레돔벌레 (0825 · Dottler) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 9bb0604 · 2026-10-29T15:09:56.540Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 825 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 409 | `ddfe76cd688c` | `레돔벌레_light_glossy_promo_f.webp` |
| ② | heavy | ① 레돔벌레_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `7df94f34862d` | `레돔벌레_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 레돔벌레_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `cda7fad4813c` | `레돔벌레_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 레돔벌레_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `3022e147a216` | `레돔벌레_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 레돔벌레_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `bd0da40ab984` | `레돔벌레_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 레돔벌레_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `968af2064e73` | `레돔벌레_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 레돔벌레_light_glossy_promo_f.webp | `casual1-prompt.txt` | 813 | `767b29968f26` | `레돔벌레_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 레돔벌레_light_glossy_promo_f.webp | `casual2-prompt.txt` | 764 | `d280ec3a4985` | `레돔벌레_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 레돔벌레_light_glossy_promo_f.webp | `casual3-prompt.txt` | 757 | `cdc169f286cb` | `레돔벌레_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 여행 물품점 · 포켓몬 직업 현장 | a wooden travel-supply shop counter with route maps and feed pouches |
| 하는 일 | 일 사이 숨 돌리기 · 서기 | pausing between tasks with a warm mug, her tools set down beside her |
| 의상 계열 | 직업복 | practical clothing for her Pokémon-world job, readable through its tools — her own original workwear — never a copy of an existing trainer, Gym Leader or Pokémon Center uniform |
| 옷 | 학예사 카디건 | a neat cardigan over slim trousers with white cotton gloves |

옷 종류 cardigan + trousers · 드러내기 mini length, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 대회 무대 · 무대·행사 | a contest or tournament stage under spotlights |
| 하는 일 | 무대 오르기 전 준비 · 서기 | adjusting her headset or costume just before going on |
| 의상 계열 | 역할극·직업 의상 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 옷 | 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |

옷 종류 apron · 드러내기 bare midriff, cropped hem · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 수영장 · 물가 | an outdoor pool with lounge chairs and clear blue water |
| 하는 일 | 젖은 머리 쓸어넘기기 · 서기 | pushing her wet hair back with both hands |
| 의상 계열 | 레트로 | a period look from a past decade |
| 옷 | 70년대 롤러 디스코 | 1970s satin hot pants and a tube top |

옷 종류 trousers · 드러내기 off-shoulder neckline, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit
