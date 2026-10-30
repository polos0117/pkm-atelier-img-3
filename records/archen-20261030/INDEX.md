# 아켄 (0566 · Archen) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 6b9f8ca · 2026-10-30T00:19:25.035Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 566 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 426 | `312eabfa53cb` | `아켄_light_glossy_promo_f.webp` |
| ② | heavy | ① 아켄_light_glossy_promo_f.webp | `heavy-prompt.txt` | 321 | `3f0f628a0e7b` | `아켄_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 아켄_light_glossy_promo_f.webp | `mobility-prompt.txt` | 311 | `2de786dff76e` | `아켄_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 아켄_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 249 | `d6b89de4e5ea` | `아켄_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 아켄_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 255 | `950604a6cc63` | `아켄_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 아켄_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 248 | `a1d0868633bc` | `아켄_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 아켄_light_glossy_promo_f.webp | `casual1-prompt.txt` | 612 | `93322b6c95ab` | `아켄_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 아켄_light_glossy_promo_f.webp | `casual2-prompt.txt` | 791 | `1e8157690e74` | `아켄_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 아켄_light_glossy_promo_f.webp | `casual3-prompt.txt` | 631 | `1cb76bb9c53c` | `아켄_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 침실 · 집 | her bedroom, an unmade bed and soft window light |
| 하는 일 | 창밖 비 구경 · 앉기 | watching rain run down the window from an armchair, mug in hand |
| 의상 계열 | 란제리풍 | tasteful lingerie-inspired fashion, fully opaque and securely fitted, with full intimate coverage |
| 옷 | 사리 블라우스 응용 | a sari-blouse-inspired set with a short fitted top and a draped lower piece |

옷 종류 blouse + traditional · 드러내기 high thigh slit, cropped hem · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 노천 온천 · 목욕·스파 | an open-air hot spring among steaming rocks |
| 하는 일 | 젖은 머리 쓸어넘기기 · 서기 | pushing her wet hair back with both hands |
| 의상 계열 | 목욕 차림 | a bath-time wrap, robe or bathhouse loungewear that stays fully covering at chest and hips |
| 옷 | 목욕 유카타 | a light cotton bath yukata with a soft sash |

옷 종류 traditional · 드러내기 open back, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 박물관 갈라 · 저녁 자리 | a grand museum hall with marble statues at night |
| 하는 일 | 천천히 거닐기 · 걷기 | strolling through the place at an easy pace |
| 의상 계열 | 저녁 드레스 | an evening dress or night-out outfit |
| 옷 | 가운 + 이브닝 코트 | a long gown under an evening coat |

옷 종류 coat + dress · 드러내기 mini length, plunging neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit
