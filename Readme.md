# heroku でデプロイ

hogehoge

# 1.アカウントを作成

# 2.getting started から node.js を選択

https://devcenter.heroku.com/start

introduction の set up たぐをクリック

# 3.brew コマンドをうつ

https://devcenter.heroku.com/articles/getting-started-with-nodejs#set-up

コマンド：
% brew install heroku/brew/heroku

# 4.terminal から heroku にログインする

% heroku login
=>window が勝手に開くので login ボタンを押す

# 5.git のリポジトリを作成する

% git init
% git add .
% git commit -m "任意"

# 6. heroku 側にアプリを作る

% heroku create

# 7.git を heroku にプッシュする

% git push heroku master

# 8.deployed to Heroku の URL から web を開く
