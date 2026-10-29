# 두루지벌레 (0824 · Blipbug) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 9bb0604 · 2026-10-29T15:09:56.420Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 824 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 395 | `24f9491f5195` | `두루지벌레_light_glossy_promo_f.webp` |
| ② | heavy | ① 두루지벌레_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `579f37ff6fa0` | `두루지벌레_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 두루지벌레_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `288c4d302e98` | `두루지벌레_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 두루지벌레_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `47e64ebef105` | `두루지벌레_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 두루지벌레_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `bb2041bba12e` | `두루지벌레_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 두루지벌레_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `c74ecd2f1bad` | `두루지벌레_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 두루지벌레_light_glossy_promo_f.webp | `casual1-prompt.txt` | 735 | `4a00dcb69153` | `두루지벌레_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 두루지벌레_light_glossy_promo_f.webp | `casual2-prompt.txt` | 728 | `d6ff694349be` | `두루지벌레_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 두루지벌레_light_glossy_promo_f.webp | `casual3-prompt.txt` | 710 | `23d590be7bb2` | `두루지벌레_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 지붕 있는 현관 · 동료 포켓몬과 함께 | a covered porch on a rainy day, umbrellas resting by the door |
| 하는 일 | 브러싱 시간 · 무릎·쪼그림 | gently brushing her Pokémon companion on a grooming mat |
| 의상 계열 | 평상복 | everyday clothes that suit the place and activity |
| 옷 | 롱코트 + 머플러 | a long wool coat and a knitted scarf |

옷 종류 coat · 드러내기 side cutouts, open back · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 호숫가 · 여행지 | a lakeside of flat rocks and still water |
| 하는 일 | 수영하기 · 움직임 | swimming through the water mid-stroke |
| 의상 계열 | 수영복 | modern swimwear, fully lined and secure during movement |
| 옷 | 클래식 비키니 | a high-waisted bikini with a supportive halter top |

옷 종류 bikini · 드러내기 high-cut leg, plunging neckline · 장면 칸 첫머리 place · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 스티커 사진기 · 오락실·사진 부스 | an arcade photo-sticker booth under bright ring lights |
| 하는 일 | 앉아 쉬기 · 앉기 | resting on a seat for a moment, catching her breath |
| 의상 계열 | 서브컬처 | a subculture street look |
| 옷 | 로맨틱 고스 | romantic goth — a black velvet dress with a corset belt and lace sleeves |

옷 종류 dress + lingerie_set · 드러내기 halter neck, strapless top · 장면 칸 첫머리 action · 직접 입력 scene, outfit
