# エディタ入門

## エディタ
- コードを書く時に最も使う道具, それがエディタです.
- プログラミングに特化した様々なエディタが開発されていますが, Perl入学式ではその中でもAtomを紹介します.
    - 特にこだわりのない方は, 今回紹介するAtomを試してみましょう.
    - もちろん, EmacsやVimなど, 既に使い慣れているエディタがある方はそちらをお使いください.

## インストール for Ubuntu
- [https://atom.io/](https://atom.io/)へアクセスし, ｢Download .deb｣をクリックします.
- ダウンロードした`atom-amd64.deb`をダブルクリックすると, ｢Ubuntuソフトウェアセンター｣が起動します.
    - ｢インストール｣をクリックします.
    - 途中, ｢このパッケージをインストールするには, 認証が必要です｣と表示された場合, パスワードを入力し, ｢認証する｣をクリックします.

## インストール for Mac
- [https://atom.io/](https://atom.io/)へアクセスし, ｢Download For Mac｣をクリックします.
- ダウンロードした`atom-mac.zip`をダブルクリックすると, `atom.app`が生成されます.
- これをダブルクリックすればAtomが起動します.
    - ｢"Atom.app"はインターネットからダウンロードされたアプリケーションです｣という警告が出た場合, ｢開く｣をクリックします.

## 練習問題
- Atomなど, 好きなエディタで`perl-entrance`ディレクトリに`profile.txt`というファイルを用意しましょう.
    - ファイルの中には, あなたの自己紹介を書きます.
- ターミナルを使って, `profile.txt`を`profile2.txt`という名前でコピーしよう.
- コピーした`profile2.txt`をターミナルから削除しよう.
    - ヒント: ｢エディタで保存したファイルがターミナルから見つからない!｣という場合, `pwd`コマンドで現在いるディレクトリを確認してみましょう.
    - 大抵の場合, エディタからの保存先と違うディレクトリにいます. `cd`コマンドで移動しましょう.
