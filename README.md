# AEC x Project Z 한글 패치 (7 Days to Die V3.2)

**다운로드:** [AEC_ProjectZ_KoreanPatch_v1.5_for_3.2.1.zip](https://github.com/flydel11-creator/AEC-ProjectZ-KoreanPatch/raw/main/AEC_ProjectZ_KoreanPatch_v1.5_for_3.2.1.zip)

```
========================================================
  AEC x Project Z 한글 패치  (7 Days to Die V3.2)
========================================================

■ 이게 뭔가요?
  AEC x Project Z 오버홀 팩(3.2.1 기준)의 영어 텍스트를 한국어로 바꿔주는 패치입니다.
  퀘스트 문구, 아이템/퍽 설명, 보스 이름, UI 라벨, 알림 메시지, 마켓 보급 요청 목록 등 약 38,000개 항목이 들어 있습니다. (v1.3: 보스 퀘스트/이벤트 문구 1,300여 개의 영·한 혼합문 재번역, "N 시간 처치"→"N회 처치" 교정 / v1.4: 바닐라 공식 한국어의 오역 검수 — 아이템·특성·속성·버프·퀘스트·상인 대사 5,120줄을 영어 원문과 대조해 오역 284, 누락 58, 어색 52건과 방어구 등급 표기 46건을 수정. 바닐라 텍스트도 이 패치가 덮어씁니다 / v1.5: Beyond Storage 3 모드 UI 34줄 한글화)
  (팩의 98-AECxProjectZ_Tweaks 한국어 열이 대부분 영어 원문을 복사해 넣은 상태라, 그 부분까지 전부 번역했습니다.)
  팩 안에 원래 들어 있던 한국어(ProjectZ 언어파일, AEC 이벤트 JSON)까지 켜주면
  게임 대부분이 한국어로 보입니다.

■ 대상 버전
  - 7 Days to Die  : V3.2.x
  - AEC x Project Z : 3.2.1 EXPERIMENTAL (3.1.x 에서도 대부분 적용되지만 미검증)
  - 이 패치는 XML/CSV 텍스트만 바꿉니다. DLL 없음. EAC 켜둔 상태에서도 동작합니다.

■ 설치 (서버와 클라이언트 모두 같은 방법)
  1) 압축 안의 [99-KoreanPatch] 폴더를 게임(또는 서버)의 Mods 폴더에 넣습니다.
       클라이언트 예: C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\Mods\99-KoreanPatch
       확인: Mods\99-KoreanPatch\ModInfo.xml 파일이 보이면 정상 (폴더가 두 겹이면 안 됨)
     ※ 폴더 이름 앞의 99- 는 지우지 마세요. 다른 모드보다 나중에 읽혀야 덮어쓰기가 됩니다.

  2) [KoreanPatch_Setup.bat] 를 Mods 폴더 안에 넣고 실행합니다.
       - 01-ProjectZ 의 언어 파일을 한국어로 교체 (원본은 .rus_backup 으로 보관)
       - 04-AEC-ENDGAME_OVERHAUL 의 이벤트/네메시스 JSON 언어를 koreana 로 변경 (원본 .eng_backup 보관)
     bat 실행이 꺼려지면 아래 "수동 설정" 대로 직접 하셔도 됩니다.

  3) 게임 언어를 한국어로 설정하고 실행합니다. 멀티플레이는 서버/클라이언트 양쪽 다 설치해야 합니다.

■ 수동 설정 (bat 를 안 쓸 때)
  [ProjectZ 언어파일]
    Mods\01-ProjectZ\Config\Localization.csv  →  이름을 Localization.csv.rus_backup 으로 변경
    Mods\01-ProjectZ\MultiLanguage\Localization.Eng.Koreana.csv  →  Config 폴더로 복사 후
    이름을 Localization.csv 로 변경
  [AEC 이벤트 JSON]
    Mods\04-AEC-ENDGAME_OVERHAUL\AeclipseNemesisLocalization.json
    Mods\04-AEC-ENDGAME_OVERHAUL\AeclipseEventsLocalization.json
    두 파일을 메모장으로 열어 맨 위쪽  "language": "english"  를  "language": "koreana"  로 수정

■ 삭제
  Mods\99-KoreanPatch 폴더를 지우면 됩니다. 자동설정으로 바꾼 파일은 *_backup 파일 이름을 되돌리면 원상복구.

■ 알려진 한계
  - 팩이 업데이트되어 새 문구가 추가되면 그 부분은 영어로 나옵니다. (패치는 없는 키를 건드리지 않으므로 깨지진 않음)
  - 일부 보스/장비 고유명사는 음차 표기입니다. (둠로드, 셰리프, 헬스카일리 등)
  - 어색한 문장을 발견하면 Localization.csv 의 koreana 열을 직접 고쳐도 됩니다. 메모장 말고 UTF-8 지원 편집기 권장.

■ 만든 방법 / 크레딧
  - 원작: AEC x Project Z Overhaul Pack (Exodusoul, BlackRabbitMsk, Aeclipse) / Project Z (BlackRabbitMsk)
  - 이 패치는 원작 텍스트를 한국어로 옮긴 것이며 원작 파일을 재배포하지 않습니다.
    (ProjectZ 한국어 파일과 AEC JSON 은 원래 팩에 들어 있는 것을 켜기만 합니다)
  - 번역: 용어집 기반 규칙 번역 + AI 보조 번역 후 수기 검수. 상업적 이용 금지, 자유 재배포 가능(출처 표기).

```

---

## Ducksfly 서버용 묶음 (우리 서버 접속자 전용)

한글패치 + 상자 연동 + 가방 확장을 한 번에 넣는 압축입니다. **공개 한글패치만 필요하면 위 링크를 받으세요.**

**다운로드:** [Ducksfly_ServerPack_v1_for_3.2.zip](https://github.com/flydel11-creator/AEC-ProjectZ-KoreanPatch/raw/main/Ducksfly_ServerPack_v1_for_3.2.zip)

| 포함 | 내용 |
|---|---|
| 99-KoreanPatch | 한글패치 v1.5 |
| BeyondStorage3 | 상자 연동 3.2.6 |
| 20-DucksflyBackpack | 가방 98칸 → 140칸 |
| 21-DucksflyFixes | 보급 투하 보상 상자 미생성 버그 수정 |

압축 안의 `설치방법.txt` 를 그대로 따라 하면 됩니다. EAC 를 끄고 실행해야 합니다.

**한 번만 설치하면 그다음부터는 `모드업데이트.bat` 더블클릭으로 최신판이 자동 적용됩니다.** (Mods 폴더 안에 있습니다. 새 버전이 없으면 아무것도 하지 않고 닫힙니다.)

Beyond Storage 3 는 superguru, gazorper 님의 모드이며 Apache-2.0 라이선스에 따라 원본 그대로 동봉했습니다.
원본 배포처: <https://www.nexusmods.com/7daystodie/mods/7809> / 후원: <https://ko-fi.com/gazorper>
