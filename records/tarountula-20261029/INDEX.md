# 타랜툴라 (0917 · Tarountula) — 지시문 묶음

화풍 `glossy_promo` · 만든 도구 `tools/prompt-pack.cjs build` · 생성기 코드 81c5f25 · 2026-10-29T14:33:09.756Z

자리마다 `<자리>-prompt.txt` 를 **고치지 않고 그대로** 제출하고, 첨부 칸의 그림을 붙인다. 고칠 것이 있으면 settings.json 을 고쳐 build 를 다시 돌린다.
기록에는 `<자리>-ui.json`(생성기 저장값과 같은 꼴)과 지시문을 둔다 — 관리기를 쓰면 `python3 tools/image-runner.py intent --card 917 --slot <자리> --prompt <이 폴더>/<자리>-prompt.txt --ui <이 폴더>/<자리>-ui.json`.

| 차례 | 자리 | 첨부 | 지시문 | 낱말 | sha256(앞 12) | 올릴 파일 |
|---|---|---|---|---|---|---|
| ① | light | 없음 | `light-prompt.txt` | 405 | `16cb5a8d01fb` | `타랜툴라_light_glossy_promo_f.webp` |
| ② | heavy | ① 타랜툴라_light_glossy_promo_f.webp | `heavy-prompt.txt` | 319 | `c7ef9275f4f8` | `타랜툴라_heavy_glossy_promo_f.webp` |
| ③ | mobility | ① 타랜툴라_light_glossy_promo_f.webp | `mobility-prompt.txt` | 309 | `a94373f22572` | `타랜툴라_mobility_glossy_promo_f.webp` |
| ④ | light_overdrive | ① 타랜툴라_light_glossy_promo_f.webp | `light_overdrive-prompt.txt` | 247 | `f1cf84f9ec48` | `타랜툴라_light_overdrive_glossy_promo_f.webp` |
| ⑤ | heavy_overdrive | ② 타랜툴라_heavy_glossy_promo_f.webp + (되면 ①) | `heavy_overdrive-prompt.txt` | 253 | `60fdfde52928` | `타랜툴라_heavy_overdrive_glossy_promo_f.webp` |
| ⑥ | mobility_overdrive | ③ 타랜툴라_mobility_glossy_promo_f.webp + (되면 ①) | `mobility_overdrive-prompt.txt` | 246 | `7766139f49a0` | `타랜툴라_mobility_overdrive_glossy_promo_f.webp` |
| ⑦ | casual1 | ① 타랜툴라_light_glossy_promo_f.webp | `casual1-prompt.txt` | 752 | `76e1cfb95ea0` | `타랜툴라_glossy_promo_f_casual1.webp` |
| ⑧ | casual2 | ① 타랜툴라_light_glossy_promo_f.webp | `casual2-prompt.txt` | 797 | `fa2da3bc8ac5` | `타랜툴라_glossy_promo_f_casual2.webp` |
| ⑨ | casual3 | ① 타랜툴라_light_glossy_promo_f.webp | `casual3-prompt.txt` | 712 | `25ae77aebe00` | `타랜툴라_glossy_promo_f_casual3.webp` |

## ⑦ casual1 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 지금 현실 | present-day real world |
| 장소 | 쇼핑몰 · 거리·도시 | a shopping mall atrium with a fountain and glass railings |
| 하는 일 | 앉아 쉬기 · 앉기 | resting on a seat for a moment, catching her breath |
| 의상 계열 | 레트로 | a period look from a past decade |
| 옷 | 50년대 홀터 플레이수트 | a 1950s halter playsuit |

옷 종류 jumpsuit · 드러내기 mini length, open back · 장면 칸 첫머리 light · 직접 입력 scene, outfit

## ⑧ casual2 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 첫 등장 무렵 현실 | the real world around the year her Pokémon first appeared |
| 장소 | 산장 · 여행지 | a mountain lodge with a front counter and a fireplace |
| 하는 일 | 창밖 비 구경 · 앉기 | watching rain run down the window from an armchair, mug in hand |
| 의상 계열 | 전통 의상 | a traditional dress that suits her, worn naturally — the traditional dress named in Outfit wins over her apparent ethnicity and the attached image's costume |
| 옷 | 크바야 | a daily kebaya — a sheer embroidered fitted blouse over a batik sarong |

옷 종류 blouse · 드러내기 bare midriff, strapless top · 장면 칸 첫머리 detail · 직접 입력 scene, outfit

## ⑨ casual3 — 고른 길

| 칸 | 고른 것 | 트리 문장(지시문 그대로) |
|---|---|---|
| 시대 | 포켓몬 세계 안 | inside the Pokémon world, as if she simply lives there |
| 장소 | 야영 조리장 · 나무열매·요리 | an outdoor cooking site at a campsite with a camp stove and a folding table |
| 하는 일 | 캠프 정리 · 무릎·쪼그림 | kneeling to fold a camping blanket beside the tent |
| 의상 계열 | 운동복 | activewear made for the activity |
| 옷 | 자동 — 계열 안에서 장면에 맞게 |  |

옷 종류 jumpsuit · 드러내기 high thigh slit, off-shoulder neckline · 장면 칸 첫머리 action · 직접 입력 scene, outfit
