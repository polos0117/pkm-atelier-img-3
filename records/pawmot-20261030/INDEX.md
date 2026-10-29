# 빠르모트 (0923 · Pawmot) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 093fec5 · 2026-10-29T22:31:21.148Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 923 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 413 | `a878978689b1` | `빠르모트_light_glossy_promo_f.webp` |
| ② | heavy | ① 빠르모트_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `844f86ed0345` | `빠르모트_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 빠르모트_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `d7064f921612` | `빠르모트_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 빠르모트_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `f6602fa44522` | `빠르모트_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 빠르모트_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `e0d6578ac095` | `빠르모트_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 빠르모트_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `778203edd208` | `빠르모트_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 빠르모트_light_glossy_promo_f.webp | `casual1-prompt.txt` | 824 | `e70cbf2ef4ef` | `빠르모트_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 빠르모트_light_glossy_promo_f.webp | `casual2-prompt.txt` | 755 | `55a4b7eb0956` | `빠르모트_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 빠르모트_light_glossy_promo_f.webp | `casual3-prompt.txt` | 729 | `2921c44cdde3` | `빠르모트_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 마을 열매 시장 · 나무열매·요리 | a village market stall piled with fresh berries |
| 하는 일 | 천천히 거닐기 · 걷기 | strolling through the place at an easy pace |
| 의상 계열 | 평상복 | everyday clothes that suit the place and activity |
| 옷 | 롱코트 + 머플러 | a long wool coat and a knitted scarf |

옷 종류 coat · 드러내기 cropped hem, side cutouts · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호숫가 · 여행지 | a lakeside of flat rocks and still water |
| 하는 일 | 걸터앉아 발 담그기 · 앉기 | sitting on the edge with her feet over the water |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 링 장식 비키니 | a bikini joined at the centre and hips by polished metal rings |

옷 종류 bikini · 드러내기 high-cut leg, bare midriff · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 축제 거리 · 무대·행사 | a festival street of lanterns, food stalls and paper decorations |
| 하는 일 | 앉아 쉬기 · 앉기 | resting on a seat for a moment, catching her breath |
| 의상 계열 | 역할극·직업 의상 | a playful adult event costume inspired by an occupation or role — clearly a costume, not a real uniform, no real insignia |
| 옷 | 메이드 코스튬 | a black-and-white maid costume with a structured bodice, puffed sleeves and a full apron |

옷 종류 apron · 드러내기 open back, halter neck · 장면 칸 첫머리 action · 직접 입력 scene, outfit
