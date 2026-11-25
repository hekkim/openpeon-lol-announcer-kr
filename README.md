# lol_announcer_kr — 리그 오브 레전드 아나운서 (한국어)

리그 오브 레전드 한국어 아나운서 음성을 [CESP v1.0](https://openpeon.com) 이벤트 카테고리에 맞춰 묶은 사운드 팩입니다. "소환사의 협곡에 오신 것을 환영합니다"로 세션을 시작하고, 작업이 끝나면 "적을 처치했습니다", 실패하면 "아군이 당했습니다"가 나옵니다.

## 설치

```bash
peon packs install lol_announcer_kr
peon packs use lol_announcer_kr
```

## 카테고리별 음성

### `session.start` (세션 시작)

| 파일 | 대사 |
|------|------|
| `sounds/AnnouncerWelcomeSummonersRift_KR.wav` | 소환사의 협곡에 오신 것을 환영합니다. |
| `sounds/AnnouncerWelcomeLeague_KR.wav` | 리그 오브 레전드에 오신 것을 환영합니다. |
| `sounds/AnnouncerWelcome_KR.wav` | 환영합니다. |

### `task.acknowledge` (작업 수락)

| 파일 | 대사 |
|------|------|
| `sounds/AnnouncerBattleBegun_KR.wav` | 전투가 시작되었습니다. |
| `sounds/AnnouncerMinionsSpawned_KR.wav` | 미니언들이 생성되었습니다. |

### `task.complete` (작업 완료)

| 파일 | 대사 |
|------|------|
| `sounds/AnnouncerVictory_KR.wav` | 승리. |
| `sounds/AnnouncerEnemySlain_KR.wav` | 적을 처치했습니다. |
| `sounds/AnnouncerVictoryNear_KR.wav` | 승리가 눈앞에 있습니다. |
| `sounds/AnnouncerEnemyInhibitorDestroyed_KR.wav` | 적의 억제기를 파괴했습니다. |
| `sounds/AnnouncerPentaKill_KR.wav` | 펜타킬! |
| `sounds/AnnouncerYouLegendary_KR.wav` | 당신은 전설적입니다. |

### `task.error` (오류)

| 파일 | 대사 |
|------|------|
| `sounds/AnnouncerDefeat_KR.wav` | 패배. |
| `sounds/AnnouncerAllySlain_KR.wav` | 아군이 당했습니다. |
| `sounds/AnnouncerEliminated_KR.wav` | 제거되었습니다. |
| `sounds/AnnouncerShutDown_KR.wav` | 제압되었습니다. |

### `input.required` (입력 대기)

| 파일 | 대사 |
|------|------|
| `sounds/AnnouncerTurretUnderAttack_KR.wav` | 포탑이 공격받고 있습니다. |
| `sounds/AnnouncerInhibitorUnderAttack_KR.wav` | 억제기가 공격받고 있습니다. |
| `sounds/AnnouncerNexusUnderAttack_KR.wav` | 넥서스가 공격받고 있습니다. |
| `sounds/AnnouncerAllyDisconnected_KR.wav` | 아군 한 명의 연결이 끊어졌습니다. |

### `resource.limit` (한도 도달)

| 파일 | 대사 |
|------|------|
| `sounds/AnnouncerInhibitorRespawningSoon_KR.wav` | 억제기가 곧 재생성됩니다. |
| `sounds/AnnouncerEnemyVictoryNear_KR.wav` | 적의 승리가 눈앞에 있습니다. |
| `sounds/AnnouncerThirtySecondsToMinions_KR.wav` | 미니언 생성까지 30초 남았습니다. |

### `user.spam` (연타)

| 파일 | 대사 |
|------|------|
| `sounds/AnnouncerYouRampage_KR.wav` | 당신은 미쳐 날뛰고 있습니다. |
| `sounds/AnnouncerKillingSpree_KR.wav` | 학살 중입니다. |
| `sounds/AnnouncerYouUnstoppable_KR.wav` | 당신을 도저히 막을 수 없습니다. |
| `sounds/AnnouncerUnstoppable_KR.wav` | 도저히 막을 수 없습니다. |
| `sounds/AnnouncerYouDominating_KR.wav` | 당신이 전장을 지배하고 있습니다. |

## 출처

League of Legends 음성입니다. 클립은 PucsRes 님의 [LoL Voices - Female Announcer 1 Soundboard - Korean](https://www.youtube.com/watch?v=TDaefhDaN3c) 영상에서 대사 단위로 잘라 정리했습니다.

## 라이선스

CC-BY-NC-4.0. 음성의 저작권은 Riot Games에 있으며, 비상업적 팬 용도로만 배포합니다.
