# 目標管理システム
当サイトは、目標を管理するために作成しました  
目標の種類は、週間・月間・年間の3つになります  

以下に、それぞれのサイトの説明を記載しています  

## 会員登録
概要  
・ユーザーを登録します（登録できる文字は英数字のみになります） 

機能説明  
・登録  --ユーザー情報を編集    

## 目標進捗
概要  
・目標を達成した際に、進捗率を更新する事ができます  
・作成した目標の進捗率を表示します  

機能説明  
・edit  --進捗を編集  
・finish --進捗率を更新  

## 目標編集
概要  
・目標を作成/編集する事ができます  

機能説明  
・create  --目標を作成  
※週間目標は,8日以上期間があると作成失敗します  
※月間目標は,1ヶ月以上期間がないと作成失敗します    
※年間目標は,1年以上期間がないと作成失敗します  
・edit  --目標を編集  
・delete  --目標を削除  

## 週間目標
概要  
・目標に達成条件回数を設定する必要がある為、目標作成後、目標達成回数を更新する必要があります  

機能説明  
・goal_add  --目標を追加  
・goal_update  --目標を更新  
・goal_delete  --目標を削除   

## 月/年間目標    
概要  
・親目標と子目標の構成になっています    
・親目標に工数が多い目標を作成し、子目標に親目標を達成する為に必要な目標を作成します  
・親目標で目標を作成した後、編集を押すと子目標ページに遷移します  

機能説明  
・edit  --子目標を編集(親目標ページにしかありません)  
・goal_add  --目標を追加  
・goal_rename  --目標名を更新  
・goal_delete  --目標を削除(親目標ページで削除すると子目標も削除されます)  
