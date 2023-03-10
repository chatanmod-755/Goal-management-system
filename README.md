# 目標管理システム
当サイトは、目標を管理するために作成しました  
目標の種類は、週間・月間・年間の3つになります  

以下に、それぞれのサイトの説明を記載しています  

## 会員登録
概要  
・ユーザーを登録します（登録できる文字は英数字のみになります） 

機能説明  
・登録  --ユーザー情報を登録  

会員登録(操作使用イメージ)

https://user-images.githubusercontent.com/77880995/218292821-849b0541-98ce-4fb7-a37d-c6eda242c16f.mov

## 目標進捗
概要  
・目標を達成した際に、進捗率を更新する事ができます  
・作成した目標の進捗率を表示します  

機能説明  
・edit  --進捗を編集  
・finish --進捗率を更新  

週間目標達成達成(操作使用イメージ)

https://user-images.githubusercontent.com/77880995/218298804-d819bc27-34c3-4901-af84-71c2ca3c88c2.mov

月/年間目標達成(操作使用イメージ)

https://user-images.githubusercontent.com/77880995/218298982-81daf323-1053-4a17-b2b1-3db45c055e01.mov

## 目標編集
概要  
・目標を作成・編集・削除する事ができます  

機能説明  
・create  --目標を作成  
・edit  --目標を編集  
・delete  --目標を削除  
※週間目標は,8日以上期間があると作成失敗します  
※月間目標は,1ヶ月以上期間がないと作成失敗します    
※年間目標は,1年以上期間がないと作成失敗します  


週間目標作成(操作使用イメージ)

https://user-images.githubusercontent.com/77880995/218293973-7a9baa88-d703-4d4b-976f-7c14997a337d.mov

月間目標作成(操作使用イメージ)

https://user-images.githubusercontent.com/77880995/218295413-9a5f5cec-a677-4a8e-b8e8-201d0d8cc288.mov

年間目標作成(操作使用イメージ)

https://user-images.githubusercontent.com/77880995/218295563-113b4368-c4a0-47e9-82ab-b0874dcc799d.mov



## 週間目標
概要  
・目標を追加・更新・削除する事ができます  
・目標に達成条件回数を設定する必要があります  

機能説明  
・goal_add  --目標を追加  
・goal_update  --目標名・達成条件回数を更新  
・goal_delete  --目標を削除   

週間目標編集(操作使用イメージ)

https://user-images.githubusercontent.com/77880995/218296035-25ffc9a5-8308-4939-afb9-97b1f6ddcc64.mov

## 月/年間目標    
概要  
・目標を追加・更新・削除する事ができます  
・親目標と子目標の構成になっています    
・親目標に目標を達成するべき目標を作成し、子目標に親目標を達成する為に必要な目標を作成します  
・親目標で目標を作成した後、編集を押すと子目標ページに遷移します  

機能説明  
・edit  --子目標を編集(親目標ページにしかありません)  
・goal_add  --目標を追加  
・goal_rename  --目標名を更新  
・goal_delete  --目標を削除(親目標ページで削除すると子目標も削除されます)  


月/年間目標編集(操作使用イメージ)

https://user-images.githubusercontent.com/77880995/218297010-b3802461-665e-442b-a314-64002de4b26b.mov

