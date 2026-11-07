# 比赛列表 API

JSON 里有解释，这里就不再赘述了。

```json
{
  "title": "比赛名称",
  "start": "ISO8601 时间 (UTC+8)",
  "end": "ISO8601 时间 (UTC+8)",
  "duration": "时长(秒)",
  "source": "luogu|atcoder|codeforces",
  "id": "平台赛事ID (如有)",
  "type": "赛事类型 (如有)",
  "phase": "状态 (Codeforces: BEFORE/IN_PROGRESS/FINISHED)"
}