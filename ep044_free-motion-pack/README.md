<!-- 무료 모션그래픽 팩 v2 안내서 — 10종이 전부 무료라는 것, 들어 있는 것, 편집기별 파일 고르기, 글자 고쳐 다시 뽑는 법(Claude에게 맡기기 포함), 라이선스 -->
# 무료 모션그래픽 팩 v2 — 요즘 쇼츠 스타일 10종

> ## 🎁 전부 무료입니다
>
> **자막 효과·모션그래픽 10종 × 세로·가로 × 한국어·영어 × 투명 MOV·투명 WebM·초록 화면 MP4 = 완성 영상 120개**,
> 여기에 **글자·색·시간을 바꿔 다시 뽑는 원본 템플릿 20벌**까지 한 푼도 받지 않습니다.
>
> **출처 한 줄만 적으면 광고·협찬이 붙은 상업 영상에도 그대로 쓸 수 있습니다** (CC BY 4.0, 아래 「라이선스」).

영상 위에 얹어 쓰는 자막 효과·모션그래픽입니다. 요즘 쇼츠·릴스·틱톡에서 많이 보는 연출을 담았습니다.
낱말마다 톡 튀는 큰 자막, 흐릿했다 또렷해지는 글자, 3D로 뒤집히며 서는 제목, 네온 빛 테두리, 무지개빛 그러데이션, 터지는 반짝이, 색 번짐(글리치), 쾅 부딪히는 화면 흔들림이 들어 있습니다.
모든 그래픽은 처음 1~2초 안에 눈길을 끌고, 끝나기 전에 스스로 퇴장합니다.

이 팩은 **HTML·CSS 코드로 만든 것**입니다. 글자를 바꾸고 싶으면 `vars` 파일의 글만 고친 뒤 렌더 명령 한 줄을 돌리면 됩니다. 직접 하기 어렵다면 **Claude에게 「이 문장으로 바꿔서 뽑아 줘」라고 맡겨도 됩니다** (아래 「글자 바꿔 다시 뽑기」).

## 들어 있는 것

| # | 이름 | 움직임 | 길이 |
|---|---|---|---|
| 1 | **낱말별 팝 자막** `word-caption` | 두세 낱말씩 아주 큰 글씨(굵은 검은 외곽선·그림자)로 쾅 나옵니다. 지금 말하는 낱말은 노랑·분홍·하늘색으로 바뀌며 튕기듯 커지고 살짝 기울어집니다. 첫 묶음은 충격파·불꽃·화면 흔들림과 함께 나옵니다. | 7초 |
| 2 | **첫 장면 큰 제목** `kinetic-title` | 머리글 알약이 열리고 흩어진 글자가 모입니다. 둘째 줄은 한 글자씩 3D로 뒤집혀 서고, 셋째 줄은 크게 흐린 글자가 쾅 박히며 강조 낱말이 무지개빛으로 빛나고 색이 번집니다. | 5초 |
| 3 | **네온 형광펜 자막** `highlight-marker` | 낱말이 흐릿하게 떠올라 또렷해지고, 고른 말 뒤로 빛나는 그러데이션 형광펜이 쭉 그어지며 글자색이 뒤집히고 별이 반짝입니다. | 5초 |
| 4 | **체크리스트** `checklist` | 흰 알약 줄들이 오른쪽에서 잔상을 끌며 날아와 서고, 차례로 동그라미에 체크가 그어지며 줄이 노랑→분홍으로 차오르고 불꽃이 터집니다. | 6초 |
| 5 | **화살표 콜아웃** `arrow-callout` | 가리킬 곳에 조준 모서리가 돌며 조여 들고 음파 고리가 퍼집니다. 빛 머리를 단 그러데이션 화살표가 그어지고 이름표 스티커가 튕겨 나옵니다. 가리킬 곳은 % 위치로 정합니다. | 5초 |
| 6 | **비교 카드 VS** `versus` | 기울어진 두 색 판이 양쪽에서 잔상을 끌며 쾅 부딪히고, 큰 VS가 충격파·전기 불꽃과 함께 떨어집니다. 고른 쪽은 왕관 배지를 달고 커지고, 다른 쪽은 흑백으로 물러납니다. | 6초 |
| 7 | **이름표 (로워서드)** `lower-third` | 빛나는 세로 막대가 솟고, 이름이 한 글자씩 흐릿하게 미끄러져 서고, 빛 머리가 밑줄을 그은 뒤 직함 알약이 그러데이션으로 열립니다. | 5초 |
| 8 | **주의·팁 스티커** `alert-tag` | 꼬리표가 지직거리는 글리치로 나타나 튕겨 서고, 아이콘이 흔들리며 고리가 퍼집니다. 끝에는 옛날 TV가 꺼지듯 한 줄로 접혀 사라집니다. 주의·팁·알림 세 가지입니다. | 4.5초 |
| 9 | **타임라인 리스트** `list-timeline` | 빛나는 세로선이 그어지고 빛 구슬이 줄마다 내려가며, 번호가 아래부터 그러데이션으로 차오르고 항목이 미끄러져 나옵니다. 지난 줄은 작아지며 물러납니다. | 6초 |
| 10 | **네온 정보 카드** `glow-card` | 어두운 카드가 3D로 휙 돌아 들어오고, 무지개빛 테두리와 빛 번짐이 카드 둘레를 계속 돕니다. 꼬리표·제목·밑줄·본문이 차례로 떠오르고, 끝에는 뒤로 넘어가며 사라집니다. (v1의 `paper-card`가 바뀐 것) | 5초 |

> 낱말별 팝 자막·VS 화면·형광펜 같은 연출은 쇼츠·릴스에서 널리 쓰이는 기법을 참고해 처음부터 새로 만든 것입니다. 특정 채널의 로고·이름·고유 디자인은 쓰지 않았습니다.

각 그래픽마다 **세로 1080×1920 · 가로 1920×1080** 원본 템플릿이 있고, 안에 한국어·영어 문장 파일이 들어 있습니다(30fps). 모두 합쳐 **원본 템플릿 20벌**입니다. 영상 파일은 들어 있지 않고, 아래 「뽑기」대로 명령 한 줄이면 원하는 형식으로 직접 만들어집니다.

```
templates/<그래픽>_<vertical|horizontal>/index.html      고쳐 쓰는 원본(HTML·CSS 코드)
templates/<그래픽>_<vertical|horizontal>/vars/ko.json    한국어 문장
templates/<그래픽>_<vertical|horizontal>/vars/en.json    영어 문장
preview.png                                              10종 미리보기
```

뽑을 수 있는 형식: `.mov` 투명(ProRes 4444, 프리미어·다빈치·파이널컷), `.webm` 투명(VP9 알파, OBS), 초록 화면 `.mp4`(캡컷 등 크로마키).

세로판은 쇼츠 화면 아래쪽 UI(약 420px)와 오른쪽 버튼 줄(약 180px)을 피해서 놓았습니다.

## 내 편집기에는 어떤 파일을 쓰나

| 편집기 | 쓸 파일 | 넣는 법 |
|---|---|---|
| 프리미어 프로 | `.mov` | 영상 위 트랙에 올리면 배경이 투명하게 겹칩니다 |
| 다빈치 리졸브 (무료판·윈도 포함) | `.mov` | 영상 위 트랙에 올립니다. 투명하지 않으면 클립 속성의 Alpha Mode를 확인합니다 |
| 파이널 컷 프로 | `.mov` | 연결 클립으로 붙이면 자동으로 겹칩니다 |
| OBS 스튜디오 | `.webm` | 「미디어 소스」로 추가합니다 |
| 캡컷 (모바일·PC), 블로(VLLO), iMovie | `_green.mp4` | 오버레이(PIP)로 넣고 **크로마 키**로 초록을 뺍니다 |

> **초록 화면으로 뽑으면 빛 번짐이 자동으로 꺼져요.** 네온 빛·빛 후광·흐린 그림자·충격파 고리처럼 반쯤 투명한 효과는 초록 위에 얹히면 초록이 비쳐 크로마 키로 깨끗하게 빠지지 않습니다. 그래서 `_green.mp4`는 이런 효과를 끄고, 가장자리가 딱 떨어지는 모습으로 따로 렌더했습니다. 크로마 키로 빼도 초록 테두리가 남지 않습니다.
> 빛 번짐까지 다 들어간 모습을 원하면 투명 파일(`.mov`·`.webm`)을 쓰세요. 두 파일은 같은 그래픽이고, 빛 효과만 다릅니다.
>
> 캡컷이 투명 MOV·WebM을 그대로 겹치는지는 공식 문서에 없어 아직 확인하지 못했습니다. 캡컷에서는 초록 화면 파일을 쓰세요.

### 근거 — 편집기별 투명 영상 지원 (공식 문서 확인, 2026-10-09)

✅ 공식 문서로 확인 · ✗ 공식 지원 목록에 없음 · ❓ 공식 문서 없음

| 편집기 | ProRes 4444 알파 `.mov` | WebM VP9 알파 | 크로마 키 기능 | 근거 |
|---|---|---|---|---|
| 캡컷 모바일 | ❓ | ❓ | ✅ 편집 › 배경 제거 › 크로마 키 | [CapCut 도움말](https://www.capcut.com/help/chroma-key-feature) |
| 캡컷 PC | ❓ | ❓ | ✅ 클립 선택 › 크로마 키 | 같은 문서 |
| 프리미어 프로 | ✅ ProRes 가져오기, QuickTime 알파 인식 | ✗ 지원 형식 목록·릴리스 노트(26.5.2까지)에 없음 | ✅ Ultra Key | [지원 형식](https://helpx.adobe.com/premiere/desktop/organize-media/import-files/supported-file-formats.html) · [합성·알파](https://helpx.adobe.com/premiere/desktop/add-video-effects/work-with-composites/compositing-overview.html) · [Ultra Key](https://helpx.adobe.com/premiere/desktop/add-video-effects/effects-and-transitions-library/apply-and-customize-chromakey-using-the-ultra-key-effect.html) |
| 다빈치 리졸브 (무료) | ✅ 맥·윈도·리눅스 모두 ProRes MOV 디코드 | ✗ `.webm`은 VP8만 목록에 있음 | ✅ Delta Keyer | [Resolve 21 코덱 목록 PDF](https://documents.blackmagicdesign.com/SupportNotes/DaVinci_Resolve_21_Supported_Codec_List.pdf) · [Fusion](https://www.blackmagicdesign.com/products/davinciresolve/fusion) |
| 파이널 컷 프로 | ✅ ProRes 4444는 알파 지원 형식 | ✗ 지원 형식 목록에 없음 | ✅ Keyer | [지원 형식](https://support.apple.com/guide/final-cut-pro/supported-media-formats-ver2833f855/mac) · [알파 채널](https://support.apple.com/guide/final-cut-pro/use-alpha-channels-ver52cf382e/mac) |
| OBS 스튜디오 | ❓ (`.mov` 재생은 지원) | ✅ 17.0.1부터 미디어 소스가 알파 WebM 재생 | ✅ Chroma Key 필터 | [미디어 소스](https://obsproject.com/kb/media-sources) · [17.0.1 릴리스](https://github.com/obsproject/obs-studio/releases/tag/17.0.1) · [필터](https://obsproject.com/kb/filters-guide) |
| iMovie | ❓ | ❓ | ✅ 초록/파랑 화면 | [맥](https://support.apple.com/guide/imovie/create-a-green-screen-effect-mov82da1338a/mac) · [아이폰](https://support.apple.com/en-us/102308) |

## 쓰는 법 (편집기)

1. 내 영상을 아래 트랙에, 그래픽 파일을 그 위 트랙에 놓습니다.
2. 그래픽을 말에 맞춰 옮깁니다. 낱말별 팝 자막은 0.42초마다, 체크리스트는 0.7초마다, 타임라인 리스트는 1.1초마다 다음 것이 나옵니다. 말 속도에 딱 맞추려면 아래처럼 간격을 바꿔 다시 뽑는 편이 가장 깔끔합니다.
3. 크기·위치는 편집기에서 바꿔도 됩니다. 원본 크기 그대로 쓰면 글자가 가장 또렷합니다.

## 글자 바꿔 다시 뽑기 (원본 템플릿)

원본은 [HyperFrames](https://github.com/heygen-com/hyperframes)(HTML로 영상을 만드는 무료 프로그램) 프로젝트이고, 그래픽 하나가 `index.html` 한 장입니다. 컴퓨터에 Node.js와 FFmpeg가 있으면 됩니다.

**가장 쉬운 길: 글만 고치고 한 줄 돌리기**

1. `templates/word-caption_vertical/vars/ko.json`을 열어 따옴표 안의 글을 바꿉니다.
2. 그 폴더에서 아래 한 줄을 돌립니다.

```bash
cd templates/word-caption_vertical
npx hyperframes render . --format mov --variables-file vars/ko.json -o my_caption.mov
```

- 미리보기를 보며 고치려면 `npx hyperframes preview`(브라우저에서 변수 칸에 글을 넣어 바로 봄).
- 투명 WebM은 `--format webm`입니다.
- **초록 화면 MP4 뽑기**: `vars/ko.json`에 `"backdrop": "green"` 한 줄을 더한 뒤 `--format mp4`로 렌더합니다. 이 모드에서는 빛 번짐이 저절로 꺼져 크로마 키가 깨끗하게 됩니다.

```json
{
  "text": "말하는 낱말마다 색이 톡 튀어 오르는 요즘 쇼츠 자막",
  "wordGap": 0.42,
  "startAt": 0.3,
  "backdrop": "green"
}
```

```bash
npx hyperframes render . --format mp4 --variables-file vars/ko.json -o my_caption_green.mp4
```
- 빈칸(`""`)으로 둔 줄은 숨겨집니다. 긴 글은 글자 크기가 저절로 줄어 칸 안에 맞춰집니다.

**Claude에게 맡기기**: 이 폴더를 Claude(Claude Code)에게 열어 주고 「`word-caption` 세로판을 "오늘 배운 것 세 가지" 문장으로 바꿔서 투명 MOV로 뽑아 줘」처럼 말하면, Claude가 `vars` 파일을 고치고 렌더 명령까지 돌려 줍니다. 색·속도도 말로 부탁하면 됩니다.

**색·시간 바꾸기**

- **색**: `--variables '{"accent":"#FF2D87"}'`처럼 넘깁니다. 그래픽마다 `accent`·`accent2`·`accent3`(강조색), `ink`(외곽선), `base`(글자색) 같은 색 변수가 있습니다(아래 표). 초록 화면을 쓸 생각이면 초록 계열 색은 피하세요.
- **시간**: 모든 그래픽에 `exitAt`(퇴장 시작)이 있습니다. 전체 길이를 늘리려면 `index.html`의 `data-duration` 두 곳을 함께 고치고, `exitAt`은 전체 길이보다 0.7초쯤 앞에 둡니다.

### 그래픽별 변수

| 그래픽 | 글자 변수 (`vars/ko.json`·`en.json`) | 그 밖의 변수 |
|---|---|---|
| `word-caption` | `text`(띄어쓰기로 낱말을 나눈 문장) | `wordGap`(낱말 사이 초), `startAt`(첫 낱말 시작 초), 강조색 `accent`·`accent2`·`accent3`(묶음마다 돌아가며 씀). 낱말이 많아 `exitAt` 안에 다 못 나오면 간격이 저절로 좁아집니다 |
| `kinetic-title` | `line1`(작은 머리글), `line2`, `line3`, `emph`(무지개빛으로 빛날 낱말, 비우면 마지막 낱말) | `accent`~`accent3`(머리글 알약·무지개빛 색) |
| `highlight-marker` | `line1`, `line2`, `mark`(형광펜 칠할 말, 여러 개는 쉼표로. 줄 안에 똑같이 들어 있는 말이어야 칠해집니다) | `accent`·`accent2`(첫 형광펜), `accent3`(둘째 형광펜) |
| `checklist` | `heading`(머리말), `item1`~`item5` | `firstAt`(첫 체크), `itemGap`(체크 간격), `accent`·`accent2`(차오르는 색), `paper`(알약 색) |
| `arrow-callout` | `label`(이름표 글) | `targetX`·`targetY`(가리킬 곳, 화면 왼쪽 위에서부터 %), `side`(`left`·`right`), `accent3`(조준 고리 색) |
| `versus` | `leftTitle`·`leftSub`, `rightTitle`·`rightSub`, `winTag`(고른 쪽 배지 글) | `winner`(`left`·`right`·`none`), 판 색 `accent`·`accent2`(왼쪽)·`accent3`·`accent4`(오른쪽), `vsColor`. 세로판에서 left는 위 판, right는 아래 판입니다 |
| `lower-third` | `name`(이름), `role`(직함·소개) | `accent`~`accent3`(막대·밑줄·알약 색) |
| `alert-tag` | `text`(내용), `label`(머리 글, 비우면 종류에 맞춰 주의·팁·알림) | `kind`(`warn` 주의 · `tip` 팁 · `info` 알림), 종류별 색 `warnA`·`warnB`·`tipA`·`tipB`·`infoA`·`infoB` |
| `list-timeline` | `heading`(머리말), `item1`~`item5` | `firstAt`(첫 줄 등장), `itemGap`(줄 간격), `accent`~`accent3` |
| `glow-card` | `tag`(꼬리표), `title`(제목, 두 줄까지), `body1`·`body2`(본문 두 줄) | 테두리 색 `accent`~`accent3`, `card`(카드 색), `bodyInk`(본문 글자 색) |

## 디자인 원칙 (v2)

- **어떤 화면에서도 읽히게**: 큰 글자에는 두꺼운 검은 외곽선과 부드러운 그림자를 둘러, 밝은 하늘이든 어두운 방이든 글자가 묻히지 않습니다.
- **처음 1~2초에 눈길**: 쾅 부딪힘, 화면 흔들림, 충격파 고리, 반짝이 터짐으로 시작합니다.
- **10가지가 다 다르게**: 팝 자막·3D 뒤집힘·네온 형광펜·흰 알약 체크·조준 화살표·격투 게임풍 VS·빛 막대 이름표·글리치 스티커·빛 구슬 타임라인·네온 테두리 카드. 색(노랑·분홍·하늘·보라)과 글꼴은 같은 식구로 맞췄습니다.
- **나갈 때도 움직임**: 모든 그래픽은 끝나기 전에 흐려지며 날아가거나, 접히거나, 뒤로 넘어가며 스스로 퇴장합니다.
- 반짝이 위치·흔들림은 정해진 값이라 몇 번을 다시 뽑아도 똑같이 나옵니다. 아이콘·왕관은 글꼴이 아니라 도형으로 그려서 어느 컴퓨터에서나 같게 나옵니다.

## 라이선스

- 그래픽 영상과 템플릿 원본 모두 **CC BY 4.0**입니다. 받은 파일을 그대로 쓸 때도, 템플릿으로 직접 렌더한 영상에도 출처를 표시해야 합니다.
- 글꼴 Pretendard·Black Han Sans·Anton은 **SIL OFL 1.1**, GSAP·HyperFrames 같은 제3자 코드는 각자 원래 라이선스를 따릅니다(이 묶음에는 들어 있지 않음).

### 출처 표시 예시

영상 설명란에 한 줄을 넣습니다.

```
모션그래픽: 깃냥이 (CC BY 4.0)
```

끝 크레딧에 넣을 때도 같은 한 줄이면 됩니다. 고쳐서 썼다면 `모션그래픽: 깃냥이 (CC BY 4.0) · 색·글자 고쳐서 씀`처럼 적습니다. 영어 영상에는 `Motion graphics by 깃냥이 (Gitnyangi), CC BY 4.0`을 씁니다.

자세한 내용은 [LICENSE.md](LICENSE.md)에 있습니다.

---

### English (short)

**Everything here is free**: 10 trendy Shorts/Reels-style caption effects and motion graphics × vertical (1080×1920) and horizontal (1920×1080) × Korean and English × three formats — 120 ready-to-use video files — plus 20 editable source templates written in plain HTML/CSS. Commercial use is allowed with a one-line credit.

The pack contains word-by-word pop captions, a kinetic opening title (blur-to-sharp, 3D flips, rainbow emphasis), a neon highlighter caption, a pop checklist, a lock-on arrow callout, a VS clash card, a glowing lower third, a glitch alert/tip sticker, a glowing timeline list and a neon-border info card. Use `.mov` (ProRes 4444 with alpha) in Premiere Pro, DaVinci Resolve and Final Cut Pro, `.webm` (VP9 alpha) in OBS, and `_green.mp4` with a chroma key in CapCut or other mobile editors. Green-screen renders (`"backdrop": "green"`) automatically turn off the soft glows, halos and blurred shadows so the key comes out clean; the transparent files keep the full glow. To change the text, edit `vars/en.json` in a template folder and run `npx hyperframes render . --format mov --variables-file vars/en.json -o out.mov` — or ask Claude to do it for you. Both the graphics and the templates are CC BY 4.0, so credit "Motion graphics by 깃냥이 (Gitnyangi), CC BY 4.0". The Pretendard, Black Han Sans and Anton fonts are under the SIL OFL 1.1, and third-party code (GSAP, HyperFrames) keeps its own license.
