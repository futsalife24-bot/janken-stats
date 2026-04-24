# 学長ライブ じゃんけん集計ダッシュボード

リベ大（[@ryogakucho](https://www.youtube.com/@ryogakucho)）チャンネルの学長ライブ末尾を  
faster-whisper で文字起こしし、グー・チョキ・パーの発言回数を集計したデータです。

## 📊 ダッシュボード

**[→ GitHub Pages で見る](https://futsalife24-bot.github.io/janken-stats/app.html)**

## データについて

| 項目 | 内容 |
|------|------|
| 対象チャンネル | @ryogakucho（リベ大） |
| 対象動画 | 学長ライブ |
| 文字起こしモデル | faster-whisper tiny (CPU) |
| 更新頻度 | 毎日 03:00 自動更新 |

## ファイル構成

```
app.html                  ダッシュボード（GitHub Pages）
janken_result_slim.csv    集計データ（id / title / url / グー / チョキ / パー）
```

## 集計結果（調査再開後）

| 手 | 回数 |
|----|------|
| ✊ グー | 0 |
| ✌️ チョキ | 0 |
| ✋ パー | 0 |
