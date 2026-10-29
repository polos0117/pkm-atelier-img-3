# 트래피더 (0918 · Spidops) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 5466246 · 2026-10-29T16:01:14.120Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 918 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 388 | `bbede5b3efb6` | `트래피더_light_glossy_promo_f.webp` |
| ② | heavy | ① 트래피더_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `ecc905a7eee6` | `트래피더_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 트래피더_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `90f692729509` | `트래피더_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 트래피더_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `e48ee9a5ccf3` | `트래피더_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 트래피더_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `7bd69a3979c7` | `트래피더_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 트래피더_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `32a743146c5d` | `트래피더_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 트래피더_light_glossy_promo_f.webp | `casual1-prompt.txt` | 726 | `bdd9f1a7fba5` | `트래피더_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 트래피더_light_glossy_promo_f.webp | `casual2-prompt.txt` | 791 | `a7a6b5803f39` | `트래피더_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 트래피더_light_glossy_promo_f.webp | `casual3-prompt.txt` | 636 | `de7f4479d1ef` | `트래피더_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호텔 방 · 저녁 자리 | a hotel suite with a city view and an open suitcase |
| 하는 일 | 화장대 앞 치장 · 앉기 | at a vanity, fastening one earring |
| 의상 계열 | 란제리풍 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 옷 | 베이비돌 | a babydoll slip with narrow straps, an empire waist and a softly flared hem |

옷 종류 slip · 드러내기 one-shoulder cut, open back · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 포켓몬 세계 내 방 · 포켓몬 세계 | her own room in a small house of a Pokémon-world town, a shelf of travel gear by the window |
| 하는 일 | 소파에서 게임하기 · 앉기 | playing a game on the sofa with a controller in her hands |
| 의상 계열 | 홈웨어 | soft homewear or loungewear |
| 옷 | 오프숄더 잠옷 셔츠 | a loose off-shoulder sleep shirt |

옷 종류 shirt · 드러내기 cropped hem, off-shoulder neckline · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 서커스 천막 · 환상 무대 | a circus tent ring under a striped canopy |
| 하는 일 | 링 가운데서 인사 · 서기 | bowing at the centre of the ring, one arm sweeping out |
| 의상 계열 | 무대·판타지 의상 | a stage or fantasy costume |
| 옷 | 마법사 | a sorceress costume — an off-shoulder velvet robe gown with a jewelled belt and a crystal staff prop |

옷 종류 dress + robe · 드러내기 plunging neckline, high thigh slit · 장면 칸 첫머리 action · 직접 입력 outfit
