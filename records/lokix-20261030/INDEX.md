# 엑스레그 (0920 · Lokix) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 4d29eca · 2026-10-29T21:38:08.209Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 920 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 435 | `5dfb567be755` | `엑스레그_light_glossy_promo_f.webp` |
| ② | heavy | ① 엑스레그_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `832451161eff` | `엑스레그_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 엑스레그_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `3b7728d1cf41` | `엑스레그_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 엑스레그_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `282e8b9c43e9` | `엑스레그_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 엑스레그_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `ce6eb6971c87` | `엑스레그_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 엑스레그_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `7185f8097e6f` | `엑스레그_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 엑스레그_light_glossy_promo_f.webp | `casual1-prompt.txt` | 733 | `7889cd1662f8` | `엑스레그_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 엑스레그_light_glossy_promo_f.webp | `casual2-prompt.txt` | 692 | `e4c76afd4f27` | `엑스레그_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 엑스레그_light_glossy_promo_f.webp | `casual3-prompt.txt` | 709 | `eb059ed08747` | `엑스레그_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 그늘진 잔디밭 · 동료 포켓몬과 함께 | a shaded lawn with a picnic blanket under a broad tree |
| 하는 일 | 간식 건네기 · 무릎·쪼그림 | offering a small berry treat to her Pokémon companion beside a feeding bowl |
| 의상 계열 | 홈웨어 | soft homewear or loungewear |
| 옷 | 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |

옷 종류 shirt · 드러내기 bare midriff, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 배틀 연습장 · 포켓몬 직업 현장 | an outdoor battle practice field marked with cones and chalk lines |
| 하는 일 | 도구 정리 · 서기 | tidying her tools and supplies at the end of a shift |
| 의상 계열 | 직업복 | practical clothing for her Pokémon-world job, readable through its tools — her own original workwear — never a copy of an existing trainer, Gym Leader or Pokémon Center uniform |
| 옷 | 사육 작업복 | work overalls over a fitted tank top and rubber boots |

옷 종류 overalls + tank · 드러내기 cropped hem, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 코스프레 행사 · 무대·행사 | a convention photo zone under ring lights |
| 하는 일 | 행사장에서 손님 맞기 · 서기 | greeting guests at the venue with a bright smile |
| 의상 계열 | 역할극·직업 의상 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 옷 | 유니폼풍 | a stylised uniform-inspired costume with crisp lapels and decorative epaulettes, no real insignia |

옷 종류 uniform · 드러내기 off-shoulder neckline, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit
