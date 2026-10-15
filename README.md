# 팀짜기 · 농구 공정 추첨

농구 동호회 팀을 공격·수비·패스 실력과 포지션 균형으로 나누고,
주 1회 **최종 추첨** 과정을 효과음이 들어간 영상(GIF·MP4)으로 만들어 공유하는 앱입니다.

## 받는 곳
- **웹앱 (아이폰·안드로이드 모두)**: https://haminkyu.github.io/teamdraft/
  → 열고 메뉴에서 **홈 화면에 추가**하면 앱처럼 설치돼요.
- **안드로이드 설치 파일(APK)**: https://github.com/haminkyu/teamdraft/releases/latest/download/teamdraft.apk

## 구성
- `web/` 웹앱 (index.html 하나에 모든 기능)
- `android/` 웹앱을 담는 안드로이드 앱 (갤러리 저장 + 카톡 공유)
- `.github/workflows/build.yml` main에 올리면 APK와 웹앱이 자동으로 만들어져요.

명단과 점수는 각자 기기에만 저장되고 서버로 보내지지 않아요.
