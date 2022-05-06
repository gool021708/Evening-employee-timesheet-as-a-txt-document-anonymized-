# 夕勤シフトメールを自動生成するソフト
- This Excel file or Excel VBA file is to create a txt document of evening employee timesheet used in Email anouncement of it by only input name in the schedule sheet which is named "Sheet1".  
- バージョン名はX.Y.Z,  
    - Xは大規模アップデート(予定なし)
    - Yは納入を伴うバージョンアップ
    - Zはマイナーチェンジアップデートを表します。
- マクロなしVerは納入を伴うリリースのときのみ添付

## 機能一覧
- 勤務表からメール本文の作成 
- 研修駅を入力すると時刻を自動表示する機能 
- n人体制時の入力補助機能
- 自動生成ボタン
- 勤務表に入社順に記入しないとエラーを出す機能 

## 注意
- このファイルをOneDriveに保存しないこと。メール本文生成機能が使えません
- バグの可能性は否定できないので、生成メールを確認すること
- 修正点、要望等あればGithubのIssuesからどうぞ
## 使い方
1. 勤務表を入力する  
    1. n人体制時の入力補助機能を使い規定通りに  
    2. 黄色になったら入社順エラー  
    3. 赤色になったらその他のエラー  
2. Sheet1またはSheet2にあるボタンを押す  
3. このエクセルファイルがある同じファイルに保存される  
