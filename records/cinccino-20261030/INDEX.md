# 치라치노 (0573 · Cinccino) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 ed4c162 · 2026-10-30T12:05:45.563Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 573 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 409 | `0f6f4260aedd` | `치라치노_light_glossy_promo_f.webp` |
| ② | heavy | ① 치라치노_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `b69f1f9c4c0f` | `치라치노_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 치라치노_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `469e2b2f3369` | `치라치노_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 치라치노_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 244 | `f3fd77b3d1f1` | `치라치노_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 치라치노_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 250 | `ae8008fdda79` | `치라치노_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 치라치노_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 243 | `6cc6e8c9fa2c` | `치라치노_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 치라치노_light_glossy_promo_f.webp | `casual1-prompt.txt` | 684 | `3aba01531f0b` | `치라치노_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 치라치노_light_glossy_promo_f.webp | `casual2-prompt.txt` | 794 | `4574ad444fb9` | `치라치노_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 치라치노_light_glossy_promo_f.webp | `casual3-prompt.txt` | 659 | `8a952eb44570` | `치라치노_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 무대·환상 | a stylised stage, editorial or fantasy setting not bound to a real year |
| 장소 | 가면무도회장 | a chandelier ballroom at a masquerade |
| 역할 | — |  |
| 의상 | 레트로 · 80년대 에어로빅 | an 1980s high-cut aerobics leotard over shiny tights with leg warmers and a headband |
| 몸 자세 · 구도 | 걷기 · full_body · 3/4 정면 | walking |
| 손 · 소품 동작 | prop · down · 접부채 · 부채를 든다 | holds a folding fan open near her chest |

옷 종류 leggings · 드러내기 mini length, bare midriff · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 풀숲 길 | a route of tall grass and a dirt path between two Pokémon-world towns |
| 역할 | — |  |
| 의상 | 홈웨어 · 자동 — 계열 안에서 장면에 맞게 | soft homewear or loungewear |
| 몸 자세 · 구도 | 서기 · chest_up · 정면 | standing |
| 손 · 소품 동작 | prop · prop · 잔·컵 · 두 손으로 잔을 감싼다 | holds a cup in both hands, wrapped around its warm sides |

옷 종류 knit_top + shorts · 드러내기 off-shoulder neckline, one-shoulder cut · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 장면(버전2)

| 칸 | 고른 것 | 지시문 문장 |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 스티커 사진기 | an arcade photo-sticker booth under bright ring lights |
| 역할 | — |  |
| 의상 | 수영복 · 모노키니 | a sculptural monokini with asymmetric side cut-outs joined by a solid central panel |
| 몸 자세 · 구도 | 걷기 · environmental · 뒤 3/4 | walking |
| 손 · 소품 동작 | AUTO · AUTO |  |

옷 종류 swimsuit · 드러내기 plunging neckline, halter neck · 장면 칸 첫머리 light · 직접 입력 scene, outfit
