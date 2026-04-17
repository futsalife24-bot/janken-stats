# じゃんけん集計ダッシュボード

リベ大（[@ryogakucho](https://www.youtube.com/@ryogakucho)）チャンネルの全動画末尾5分を  
faster-whisper で文字起こしし、グー・チョキ・パーの発言回数を集計したデータです。

## 📊 ダッシュボード

**[→ GitHub Pages で見る](https://futsalife24-bot.github.io/janken-stats/app.html)**

## データについて

| 項目 | 内容 |
|------|------|
| 対象チャンネル | @ryogakucho（リベ大） |
| 動画数 | 2,522 本 |
| 集計範囲 | 各動画の末尾 5 分 |
| 文字起こしモデル | faster-whisper tiny (CPU) |
| 更新頻度 | 毎日 03:00 自動更新 |

## ファイル構成

```
app.html                  ダッシュボード（GitHub Pages）
janken_result_slim.csv    集計データ（id / title / url / グー / チョキ / パー）
```

## 集計結果（最終更新時点）

| 手 | 回数 |
|----|------|
| ✊ グー | 117 |
| ✌️ チョキ | 43 |
| ✋ パー | 1,125 |
