# RimWorld Mod Template

기본 빌드 템플릿은 RimWorld 1.7 및 Harmony 3 기준입니다.

## DLL 경로

- Harmony: `Y:\SteamLibrary\steamapps\workshop\content\294100\2009463077\1.7\Assemblies\0Harmony.dll`
- RimWorld: `Y:\SteamLibrary\steamapps\common\RimWorld\Assembly-CSharp.dll`

RimWorld 1.7 설치본에 없는 `UnityEngine.CoreModule.dll`은 참조하지 않습니다.

## 빌드

저장소 루트의 `Build.bat`을 실행합니다.

경로가 다른 환경에서는 환경 변수 `RIMWORLD_DIR` 및 `HARMONY_DLL`을 지정할 수 있습니다.

빌드 출력은 `Assemblies\RimWorldModTemplate.dll`입니다.
