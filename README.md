# enPiT2019
2019年度第1回演習用のリポジトリです。

## GitHub演習

![GitHub Flow](app/src/main/res/drawable/githubflow.jpg)

### 1. 課題提出用リポジトリの作成
1. メールから招待リンクをコピーします。
2. ブラウザのアドレスバーに招待リンクを貼り付け、アクセスします。
3. 組織アカウント「yu-enpit」上にリポジトリ「課題名-アカウント名」が作成されます。
![キャプチャ](app/src/main/res/drawable/image3.jpeg)

### 2. Fork（フォーク）
1. 「yu-enpit」上に作成されたリポジトリ「課題名-アカウント名」にアクセスします。
![キャプチャ](app/src/main/res/drawable/image4.jpeg)
2. 右上の「Fork」ボタンをクリックします。
![キャプチャ](app/src/main/res/drawable/image5.jpeg)
2. 自分のアカウント上に「課題名-アカウント名」のリポジトリが作成されます。
![キャプチャ](app/src/main/res/drawable/image6.jpeg)

### 3. Clone（クローン）
1. 自分のアカウント上のリポジトリ「課題名-アカウント名」にアクセスします。
2. 「Clone or download」ボタンをクリックします。
3. URLをコピーします。
![キャプチャ](app/src/main/res/drawable/image7.jpeg)
4. Git Bashを起動し、以下のコマンドを実行します。
課題名とアカウント名は適宜読み替えてください。
```
mkdir -p /c/work/yu-enpit
cd /c/work/yu-enpit
git clone https://github.com/アカウント名/課題名-アカウント名.git
```
5. 自分のアカウント上のリポジトリ「課題名-アカウント名」がローカルに保存されます。

### 4. プログラム修正
1. ローカルにクローンしたリポジトリ「課題名-アカウント名」をAndroid Studioで開きます。  
    1-1. 「Open an existing Android Studio project」を選択します。
    ![キャプチャ](app/src/main/res/drawable/image12.jpg)  
    1-2. 先ほどローカルに保存したリポジトリを選択し、「OK」を押下します。      
2. 「activity_main.xml」を開きます。
![キャプチャ](app/src/main/res/drawable/image14.jpg)
3. DesignペインでTextView「Hello World!」を選択します。
4. Propertiesペインでtextを「Hello enPiT」に修正します。
![キャプチャ](app/src/main/res/drawable/image15.jpg)

### 5. Commit（コミット）
1. ツールウィンドウ「Version Control」を表示します。
2. Defaultを右クリック > Commit Changes... をクリックします。
3. Commit Messageにコメント「TextViewのtextを修正。」を入力し、「Commit」ボタンをクリックします。
![キャプチャ](app/src/main/res/drawable/image17.jpg)

### 6. Push（プッシュ）
1. パンくずリストからプロジェクトのルートフォルダ「課題名-アカウント名」を右クリック > Git > Repository > Push をクリックします。
![キャプチャ](app/src/main/res/drawable/image18.jpg)
2. 「Push Commits」ウィンドウが表示されます。「Push」ボタンをクリックします。  
![キャプチャ](app/src/main/res/drawable/image19.jpg)  
3. ローカルで行ったプログラム修正が自分のアカウント上のリポジトリ「課題名-アカウント名」に反映されます。


### 7. Pull Request（プルリクエスト）
1. 自分のアカウント上のリポジトリ「課題名-アカウント名」にブラウザからアクセスします。
2. 「New pull request」ボタンをクリックします。
![キャプチャ](app/src/main/res/drawable/image9.jpeg)
3. 「Comparing changes」画面で変更内容を確認し、「Create pull request」ボタンをクリックします。
![キャプチャ](app/src/main/res/drawable/image10.jpeg)
4. コメントを入力し、「Create pull request」ボタンをクリックします。
![キャプチャ](app/src/main/res/drawable/image11.jpeg)
5. 組織アカウント「yu-enpit」上のFork元のリポジトリ「課題名-アカウント名」に Pull Request が送信されます。
