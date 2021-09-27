# manaba_task_notification

### API要求仕様
| name | 内容 | 型 |
| -- | -- | -- |
| taskTitle | 課題タイトル | String |
| taskDeadline | 受付終了日時 | Date |
| taskType | 課題タイプ（小テスト・アンケート・レポート） | int |
| taskURL | 課題提出URL | String |
| className | 講義名 | String |

### タスクの優先度
| ID | 色 | 基準 |
| -- | -- | -- |
| 0 | danger | 締切まで24時間以内 |
| 1 | warning | 締切まで48時間以内 |
| 2 | #898989 | 締切まで猶予あり |
