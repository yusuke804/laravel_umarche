## インストール方法

## インストール後の実施事項

画像のダミーデータは
public/imagesフォルダ内に
sample1.jpg ~ sample6.jpgとして
保存しています。

```
php artisan storage:link
```

で storageフォルダにリンク後、
`storage/app/public/products`フォルダ内に
保存すると、表示されます。
(productsフォルダがない場合は作成してください)
