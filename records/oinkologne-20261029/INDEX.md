# 퍼퓨돈 (0916 · Oinkologne) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 81c5f25 · 2026-10-29T14:22:53.185Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 916 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 413 | `b5621c79878c` | `퍼퓨돈_light_glossy_promo_f.webp` |
| ② | heavy | ① 퍼퓨돈_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `231c58fe5d9f` | `퍼퓨돈_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 퍼퓨돈_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `dc0dda42414b` | `퍼퓨돈_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 퍼퓨돈_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 244 | `072311c63b1d` | `퍼퓨돈_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 퍼퓨돈_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 250 | `6f237fa67ddc` | `퍼퓨돈_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 퍼퓨돈_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 243 | `363bd69d64d3` | `퍼퓨돈_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 퍼퓨돈_light_glossy_promo_f.webp | `casual1-prompt.txt` | 784 | `661e40b88dec` | `퍼퓨돈_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 퍼퓨돈_light_glossy_promo_f.webp | `casual2-prompt.txt` | 624 | `9c4315c0fe9b` | `퍼퓨돈_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 퍼퓨돈_light_glossy_promo_f.webp | `casual3-prompt.txt` | 738 | `c7b2f6fa55fd` | `퍼퓨돈_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 내 방 · 포켓몬 세계 | her own room in a small house of a Pokémon-world town, a shelf of travel gear by the window |
| 하는 일 | 거울 앞 머리 묶기 · 서기 | tying her hair up in front of a mirror |
| 의상 계열 | 홈웨어 | soft homewear or loungewear |
| 옷 | 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |

옷 종류 shirt · 드러내기 one-shoulder cut, cropped hem · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호텔 방 · 저녁 자리 | a hotel suite with a city view and an open suitcase |
| 하는 일 | 침대에서 아침 · 앉기 | sitting up in bed with a breakfast tray across her lap |
| 의상 계열 | 란제리풍 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 옷 | 란제리 슬립 | a bias-cut satin slip with narrow straps and a straight hem |

옷 종류 slip · 드러내기 high thigh slit, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 육상 트랙 · 운동 | a running track with lane lines and a grandstand |
| 하는 일 | 몸풀기 · 움직임 | warming up in a forward lunge stretch, both hands resting on her front knee |
| 의상 계열 | 운동복 | activewear made for the activity |
| 옷 | 스포츠 브라 + 레깅스 | a sports bra and high-waisted leggings |

옷 종류 crop_top + leggings · 드러내기 one-shoulder cut, off-shoulder neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit
