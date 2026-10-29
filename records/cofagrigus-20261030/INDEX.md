# 데스니칸 (0563 · Cofagrigus) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 7954204 · 2026-10-29T23:17:02.324Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 563 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 415 | `8fad62d6ec6c` | `데스니칸_light_glossy_promo_f.webp` |
| ② | heavy | ① 데스니칸_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `aed7f164e6e2` | `데스니칸_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 데스니칸_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `017d41bd364b` | `데스니칸_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 데스니칸_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 248 | `4d6473bc1034` | `데스니칸_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 데스니칸_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 254 | `633261f8ff18` | `데스니칸_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 데스니칸_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 247 | `c22babd83527` | `데스니칸_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 데스니칸_light_glossy_promo_f.webp | `casual1-prompt.txt` | 680 | `0ba99cbafdd2` | `데스니칸_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 데스니칸_light_glossy_promo_f.webp | `casual2-prompt.txt` | 797 | `7d5e82442247` | `데스니칸_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 데스니칸_light_glossy_promo_f.webp | `casual3-prompt.txt` | 713 | `03de5760ae98` | `데스니칸_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 트레이너 숙소 휴게실 · 포켓몬 세계 | a trainers' lodge lounge at night with a fireplace, a small bar counter and wooden tables |
| 하는 일 | 여관 카운터에 기대기 · 서기 | leaning on the counter at night with a warm cup |
| 의상 계열 | 저녁 드레스 | an evening dress or night-out outfit |
| 옷 | 슬립 위 실크 로브 | a silk robe over an evening slip |

옷 종류 robe + slip · 드러내기 plunging neckline, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 리그 경기장 · 포켓몬 직업 현장 | a Pokémon League arena with a reception desk, a marked battle court and a commentary desk |
| 하는 일 | 일 사이 숨 돌리기 · 서기 | pausing between tasks with a warm mug, her tools set down beside her |
| 의상 계열 | 직업복 | practical clothing for her Pokémon-world job, readable through its tools — her own original workwear — never a copy of an existing trainer, Gym Leader or Pokémon Center uniform |
| 옷 | 공방 앞치마 | a work shirt under a canvas workshop apron, safety glasses pushed up |

옷 종류 apron + shirt · 드러내기 one-shoulder cut, side cutouts · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호숫가 · 여행지 | a lakeside of flat rocks and still water |
| 하는 일 | 소풍 · 앉기 | having a small picnic on a blanket with fruit and a basket |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 딥 플런지 원피스 | a one-piece swimsuit with a deep plunging V and a secure wide waistband |

옷 종류 swimsuit · 드러내기 high-cut leg, halter neck · 장면 칸 첫머리 place · 직접 입력 scene, outfit
