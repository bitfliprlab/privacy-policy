# 개인정보처리방침 (수뿌: 수세미 ASMR)

**시행일:** 2026-11-18 (이전 판 2026-11-16)  
**앱 이름:** 수뿌: 수세미 ASMR (영문명 Loofah Crunch)  
**개발자(운영자):** FliprLab

FliprLab(이하 "개발자")은 수뿌(이하 "앱") 이용자의 개인정보를 중요하게 생각하며, 관련 법령과 Google Play 정책을 지킵니다.

## 1. 기기에 저장하는 정보

아래 정보는 이용자의 기기에만 저장하며 개발자에게 보내지 않습니다.

- 설정(소리 출력 방식, 진동 세기, 언어 등)
- 다 깐 수세미 수와 광고 표시 간격 기록
- 온라인 랭킹에 아직 보내지 못한 완료 기록(연결되면 보냄)과 이미 알린 배지 목록

## 2. 온라인 주간 랭킹 (선택)

앱에는 매주 "완익 vs 덜익" 대결과 개인 랭킹이 있습니다. 이 기능은 **Google Play 게임즈 서비스에 로그인한 경우에만** 쓰이며, 로그인하지 않아도 게임은 모두 할 수 있습니다.

로그인하면 개발자는 Google Firebase(Firebase 인증, Cloud Firestore, Cloud Functions, 서버 위치: 대한민국 서울)를 통해 아래 정보를 저장합니다.

| 정보 | 용도 |
|---|---|
| 계정 식별자(Play 게임즈 로그인으로 만든 Firebase 사용자 ID) | 기록을 이용자별로 모으고 중복·부정 제출을 막음 |
| Play 게임즈 닉네임 | 주간 랭킹에 표시 — **다른 이용자에게 보입니다** |
| 완료 기록(수세미 종류, 걸린 시간, 주, 제출 시각, 최근 제출 번호) | 주간 대결 점수, 내 기록, 순위 |
| 주간 순위와 배지 | 랭킹·결과 화면, 배지 알림 |

- 이메일 주소, 실명, 연락처는 받지 않습니다. 닉네임은 Play 게임즈에서 이용자가 정한 이름입니다.
- 각 편(완익·덜익)의 주간 합계는 누가 했는지 남지 않는 숫자로만 집계합니다.
- 위 정보는 랭킹 기능을 제공하는 데만 쓰며, 판매하거나 광고에 쓰지 않습니다. 저장과 전송은 Google이 암호화해 처리합니다.
- Play 게임즈 로그인 자체는 Google이 처리합니다: https://policies.google.com/privacy

## 3. 광고를 위해 처리되는 정보

앱은 Google AdMob(Google 모바일 광고 SDK, 사용자 메시지 플랫폼)으로 광고를 보여 줍니다. 보상형 광고는 이용자가 직접 고른 경우에만, 전면 광고는 수세미 하나를 다 깐 뒤 다음 수세미로 넘어갈 때만 제한된 횟수로 나오며, 수세미를 만지는 중에는 광고가 나오지 않습니다. Google은 광고 제공 과정에서 아래 정보를 수집하거나 처리할 수 있습니다.

- 광고 ID 등 기기 식별자
- IP 주소와 이를 바탕으로 한 대략적인 위치
- 기기와 앱 정보(기종, 운영체제, 언어, 앱 버전 등)
- 광고 노출과 클릭 등 광고 상호작용 정보
- 오류와 성능 진단 정보

이 정보는 광고 제공, 광고 성과 측정, 부정 사용 방지, 동의 관리에 쓰이며 Google의 정책에 따라 처리됩니다.

앱에 포함된 Google Play 서비스 구성 요소(Google 모바일 광고 SDK, Firebase SDK, Play 게임즈 서비스)는 Google의 정책에 따라 기기에 로그인된 Google 계정 정보(이메일 주소 등)에 접근하거나 이를 Google로 전송할 수 있습니다. 앱 자체는 이메일 주소를 묻거나 사용하지 않으며, 개발자는 이 정보를 받지 않습니다.

- Google의 파트너 사이트·앱 데이터 사용 방식: https://policies.google.com/technologies/partner-sites
- Google 광고 관련 정책: https://policies.google.com/technologies/ads

## 4. 앱 사용 분석 (Google 애널리틱스 for Firebase)

게임을 개선하기 위해 Google 애널리틱스 for Firebase로 앱 사용 통계를 수집합니다. 개발자는 Google이 집계한 통계만 보며, 분석에 이름·이메일·닉네임·계정 식별자를 보내지 않습니다.

- 앱 인스턴스 ID, 광고 ID 등 기기 식별자
- IP 주소를 바탕으로 한 대략적인 위치(국가·지역)
- 기기와 앱 정보(기종, 운영체제, 언어, 앱 버전 등)
- 앱 사용 정보(앱 실행, 수세미 종류 선택, 첫 파열·벗기기·자르기·물뿌리기·돌리기, 한 통 완료까지 걸린 시간과 주 조작, 대결·랭킹 화면 사용, 이어폰/스피커 출력 설정, 진동 지원 방식, 광고 제안과 시청 결과 등 게임 내 이벤트)

동의가 필요한 지역에서는 광고 동의 화면에서 이용자가 고른 선택에 따라 분석 데이터의 저장과 사용을 제한합니다. 분석 데이터는 Google의 정책에 따라 처리되며, 개발자 쪽 보관 기간은 14개월입니다.

- Google 애널리틱스의 데이터 보호: https://support.google.com/analytics/answer/6004245

## 5. 동의와 선택

- 유럽 경제 지역, 영국, 스위스 등 동의가 필요한 지역에서는 처음 실행할 때 광고 데이터 사용에 대한 동의를 묻습니다. 앱 안의 "개인정보 설정" 버튼으로 언제든 선택을 바꿀 수 있습니다.
- 맞춤 광고를 원하지 않으면 Android 설정의 개인 정보 보호 > 광고에서 광고 ID를 삭제하거나 재설정할 수 있습니다.
- 온라인 랭킹은 Play 게임즈에 로그인하지 않으면 쓰이지 않습니다. 참여한 뒤에도 아래 7항의 방법으로 언제든 기록을 지우고 빠질 수 있습니다.
- 광고를 보지 않아도 기본 수세미(갈색·초록)는 모두 이용할 수 있습니다.

## 6. 앱 권한

- 인터넷, 네트워크 상태 확인: 광고, 앱 사용 분석, 온라인 랭킹에 사용합니다.
- 광고 ID: 광고 제공과 측정, 앱 사용 분석에 사용합니다.
- 진동: 수세미를 부술 때의 진동 효과에 사용합니다.

## 7. 온라인 기록 삭제 (계정 삭제)

**앱에서:** 설정 > **내 온라인 기록 삭제** > 삭제. 서버에 있는 닉네임, 주간 랭킹 기록, 완료 기록, 배지와 로그인 계정(Firebase 사용자)이 바로 삭제되고, 이 기기에 남은 대기 기록도 지워집니다. 삭제한 뒤에는 자동으로 다시 로그인하지 않으며, 설정 > 온라인 랭킹 다시 참여를 누를 때만 새로 참여합니다.

**앱 없이:** 앱을 지웠거나 앱에서 삭제할 수 없으면 아래 이메일로 "수뿌 온라인 기록 삭제 요청"과 Play 게임즈 닉네임(가능하면 랭킹 화면 캡처)을 보내 주세요. 본인 기록을 확인한 뒤 30일 안에 위와 같은 정보를 모두 삭제하고 회신합니다.

- 지워지지 않고 남는 것: 각 편의 주간 합계(누가 했는지 남지 않는 숫자), 이미 끝난 주에 기록된 전체 참여 인원 수.
- Play 게임즈 계정 자체와 Google이 처리하는 정보는 Google에서 관리합니다(Play 게임즈 앱 또는 Google 계정 설정).

## 8. 보관과 파기

- 기기 안의 정보는 앱을 삭제하면 함께 삭제됩니다.
- 온라인 랭킹 정보는 이용자가 7항의 방법으로 삭제할 때까지 보관하며, 랭킹 서비스를 끝내면 모두 삭제합니다.
- Google이 처리하는 광고 정보의 보관 기간은 Google의 정책을 따릅니다.
- 앱 사용 분석 데이터는 Google 애널리틱스에서 14개월 뒤 삭제됩니다.

## 9. 아동의 개인정보

앱은 만 13세 이상을 대상으로 하며, 만 13세 미만 아동을 대상으로 하지 않습니다. 개발자는 아동의 개인정보를 알고서 수집하지 않습니다.

## 10. 이용자의 권리

이용자는 앱을 삭제해 기기 안의 정보를 지울 수 있고, 7항의 방법으로 온라인 기록을 삭제할 수 있으며, 5항의 방법으로 광고·분석 데이터 사용을 제한할 수 있습니다. 저장된 온라인 정보의 열람이나 정정을 원하면 아래 연락처로 요청해 주세요.

## 11. 방침의 변경

법령이나 앱의 기능이 바뀌면 이 방침을 고칠 수 있으며, 고친 내용은 이 페이지에 게시합니다.

## 12. 문의처

- 이메일: bitflipr.lab@gmail.com
- 개발자: FliprLab

---

# Privacy Policy (Loofah Crunch)

**Effective date:** November 18, 2026 (previous version November 16, 2026)  
**App:** Loofah Crunch (Korean title: 수뿌: 수세미 ASMR)  
**Developer:** FliprLab

## 1. Data stored on your device

Settings (sound output, haptic strength, language and so on), the number of loofahs you have finished, the timing of ads shown, finished records waiting to be sent to the online rankings, and the badges already shown to you are stored only on your device and are not sent to the developer.

## 2. Weekly online rankings (optional)

The app has a weekly "Ripe vs Raw" battle and personal rankings. They are used **only if you sign in with Google Play Games Services**; the whole game can be played without signing in.

When you sign in, the developer stores the following with Google Firebase (Firebase Authentication, Cloud Firestore, Cloud Functions; servers in Seoul, South Korea):

| Data | Purpose |
|---|---|
| Account identifier (the Firebase user ID created by the Play Games sign-in) | Group your records and prevent duplicate or abusive submissions |
| Play Games nickname | Shown in the weekly rankings — **visible to other players** |
| Finished records (loofah type, time taken, week, submission time, recent submission IDs) | Weekly battle score, your records, rankings |
| Weekly ranks and badges | Ranking and result screens, badge notices |

- The developer does not receive your email address, real name or contact details. Your nickname is the name you chose in Play Games.
- Weekly team totals (Ripe and Raw) are kept only as counts that do not record who contributed.
- This data is used only to run the rankings; it is never sold or used for ads. Google encrypts it in storage and in transit.
- Play Games sign-in itself is handled by Google: https://policies.google.com/privacy

## 3. Data processed for ads

The app shows ads through Google AdMob (Google Mobile Ads SDK and User Messaging Platform). Rewarded ads appear only when you choose to watch one, and interstitial ads appear, at a limited rate, only when you move on to the next loofah after finishing one — never while you are touching a loofah. Google may collect or process the advertising ID and other device identifiers, your IP address and the approximate location derived from it, device and app information, ad interactions, and diagnostic data. This is used to serve and measure ads, prevent fraud and manage consent, under Google's policies. The Google Play services components bundled in the app (Google Mobile Ads SDK, Firebase SDK, Play Games Services) may access the Google account information signed in on the device, such as the email address, or send it to Google under Google's policies. The app itself never asks for or uses your email address, and the developer never receives it:

- https://policies.google.com/technologies/partner-sites
- https://policies.google.com/technologies/ads

## 4. App usage analytics (Google Analytics for Firebase)

To improve the game, the app collects usage statistics with Google Analytics for Firebase: the app instance ID, the advertising ID and other device identifiers, approximate location derived from your IP address, device and app information, and in-game events such as app opens, the loofah type you pick, the first crack, peeling, cutting, spraying water and turning the loofah, finishing a loofah with the time taken and main gesture used, use of the battle and ranking screens, earphone or speaker output setting, haptics support, and ad offers and results. The developer sees only aggregated statistics and never sends your name, email, nickname or account identifier to analytics. Where consent is required, analytics storage and use follow the choice you make in the ad consent message. Analytics data is kept for 14 months.

- https://support.google.com/analytics/answer/6004245

## 5. Consent and choices

- Where consent is required, such as the EEA, the UK and Switzerland, the app asks for it on first launch. You can change your choice at any time with the "Privacy settings" button in the app.
- To opt out of personalized ads, delete or reset your advertising ID in Android Settings > Privacy > Ads.
- The online rankings are not used unless you sign in to Play Games. After joining, you can delete your records and leave at any time (section 7).
- Both basic loofahs (brown and green) can be played without watching ads.

## 6. Permissions

Internet and network state for ads, analytics and the online rankings; the advertising ID for serving and measuring ads and for analytics; and vibrate for haptic feedback while crushing.

## 7. Deleting your online records (account deletion)

**In the app:** Settings > **Delete my online records** > Delete. Your nickname, weekly ranking entries, finished records, badges and sign-in account (Firebase user) are deleted from the server right away, and records waiting on the device are cleared. The app then stops signing you in automatically; you rejoin only if you tap Settings > Join online rankings again.

**Without the app:** if you have uninstalled the app or cannot delete in the app, email the address below with "Loofah Crunch online data deletion request" and your Play Games nickname (a screenshot of the ranking screen helps). After confirming the records are yours, we delete all of the data above within 30 days and reply.

- Kept after deletion: weekly team totals (counts that do not record who contributed) and the number of players recorded for weeks that have already closed.
- Your Play Games account itself and data processed by Google are managed by Google (Play Games app or Google Account settings).

## 8. Retention

Data on your device is deleted when you uninstall the app. Online ranking data is kept until you delete it as described in section 7, and all of it is deleted if the rankings are shut down. Ad data processed by Google is kept according to Google's policies. Analytics data is deleted after 14 months.

## 9. Children

The app is meant for users aged 13 and over and is not directed to children under 13. The developer does not knowingly collect personal data from children.

## 10. Your rights

You can remove on-device data by uninstalling, delete your online records (section 7), and limit ad and analytics use (section 5). To access or correct the online data stored about you, contact us below.

## 11. Changes and contact

This policy may change with the law or the app's features; changes are posted on this page.

- Email: bitflipr.lab@gmail.com
- Developer: FliprLab
