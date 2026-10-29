# 프로토가 (0564 · Tirtouga) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 f10d507 · 2026-10-29T23:40:06.231Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 564 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 418 | `f56c6ec5a17f` | `프로토가_light_glossy_promo_f.webp` |
| ② | heavy | ① 프로토가_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `ea20ca1f32db` | `프로토가_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 프로토가_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `e3af3ee194d4` | `프로토가_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 프로토가_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 250 | `22e419ada55f` | `프로토가_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 프로토가_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 256 | `f4a52ee7e284` | `프로토가_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 프로토가_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 249 | `3495f66be21a` | `프로토가_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 프로토가_light_glossy_promo_f.webp | `casual1-prompt.txt` | 720 | `d87fcf0fffa0` | `프로토가_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 프로토가_light_glossy_promo_f.webp | `casual2-prompt.txt` | 792 | `7c05a884cd88` | `프로토가_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 프로토가_light_glossy_promo_f.webp | `casual3-prompt.txt` | 724 | `0e5e24b48f43` | `프로토가_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 여행 열차 객실 · 포켓몬 직업 현장 | a carriage of a Pokémon travel train with luggage racks and resting cushions |
| 하는 일 | 일 사이 숨 돌리기 · 서기 | pausing between tasks with a warm mug, her tools set down beside her |
| 의상 계열 | 직업복 | practical clothing for her Pokémon-world job, readable through its tools — her own original workwear — never a copy of an existing trainer, Gym Leader or Pokémon Center uniform |
| 옷 | 사육 작업복 | work overalls over a fitted tank top and rubber boots |

옷 종류 overalls + tank · 드러내기 strapless top, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 오락실 · 오락실·사진 부스 | an arcade hall of upright cabinets whose screens show only coloured glow |
| 하는 일 | 앉아 쉬기 · 앉기 | resting on a seat for a moment, catching her breath |
| 의상 계열 | 역할극·직업 의상 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 옷 | 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |

옷 종류 uniform · 드러내기 side cutouts, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 해변 · 물가 | a sunny beach with wet sand and shallow surf |
| 하는 일 | 물 마시며 숨 고르기 · 서기 | catching her breath with a water bottle |
| 의상 계열 | 레트로 | a period look from a past decade |
| 옷 | 50년대 핀업 란제리 | a 1950s pin-up lingerie set with a structured bra and high-waisted bottoms |

옷 종류 lingerie_set · 드러내기 high-cut leg, plunging neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit
