# know-how

機種固有のノウハウ

## IM切り替え(Super + Space)時にアプリ一覧が表示される
アプリ一覧はSuper + aキーで表示できるのでアプリ一覧表示（アクティビティ画面）のショートカットキーを変更することで解決する。
```bash
gsettings set org.gnome.mutter overlay-key 'Super_R'
```
