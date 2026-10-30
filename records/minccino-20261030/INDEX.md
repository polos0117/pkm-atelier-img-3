# 치라미 (0572 · Minccino) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 ed4c162 · 2026-10-30T12:00:43.083Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 572 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 414 | `1275cbefbc94` | `치라미_light_glossy_promo_f.webp` |
| ② | heavy | ① 치라미_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `0c1d9152585b` | `치라미_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 치라미_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `31ef387d1af5` | `치라미_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 치라미_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 244 | `2dcba54a1e8a` | `치라미_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 치라미_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 250 | `724d9d493a6e` | `치라미_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 치라미_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 243 | `48df1b4ae53e` | `치라미_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 치라미_light_glossy_promo_f.webp | `casual1-prompt.txt` | 745 | `4d70f68729ca` | `치라미_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 치라미_light_glossy_promo_f.webp | `casual2-prompt.txt` | 784 | `5b9b68fc38ce` | `치라미_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 치라미_light_glossy_promo_f.webp | `casual3-prompt.txt` | 682 | `cfc0331e9af0` | `치라미_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 가면무도회장 | a chandelier ballroom at a masquerade |
| 역할 | — |  |
| 의상 | 란제리풍 · 뷔스티에풍 | a bustier-inspired satin top with a long structured bodice and vertical seams |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | wave · chest_hand |  |

옷 종류 lingerie_set · 드러내기 high-cut leg, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야간 관측소 | a quiet hilltop observatory deck with a telescope under the night sky |
| 역할 | — |  |
| 의상 | 저녁 드레스 · 가운 + 이브닝 코트 | a long gown under an evening coat |
| 몸 자세 · 구도 | 서기 · face_close · 3/4 정면 | standing |
| 손 · 소품 동작 | cheek · out |  |

옷 종류 coat + dress · 드러내기 off-shoulder neckline, high thigh slit · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 갈라 만찬장 | a candlelit gala dinner hall |
| 역할 | — |  |
| 의상 | 홈웨어 · 오프숄더 니트 | an off-shoulder knit top slipping from one shoulder over shorts |
| 몸 자세 · 구도 | 의자에 앉기 · full_body · 옆모습 | seated on a chair |
| 손 · 소품 동작 | prop · lap · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 knit_top + shorts · 드러내기 off-shoulder neckline, mini length · 장면 칸 첫머리 detail · 직접 입력 scene, outfit
