# Embed Images with original file name
Inkscape extension for embedding images with adding original file name to object label, "inkscape:label"

リンク画像を埋め込む際に、元のファイル名をオブジェクトのラベル("inkscape:label"プロパティ)に保存する。

inkscape ver 1.3 (または、extensions ディレクトリに image_embed.py がある)場合は
embedimage.py の代わりに image_embed.py をコピーしてください。

## install

embedimage.py ファイルをinkscapeのextensionフォルダにコピーしてください。

### Linux

```console
cp embedimage.py ~/.config/inkscape/extensions/
```

### Mac OS

パッケージの内容を表示して
```
/Applications/Inkscape.app/Contents/Resources/share/inkscape/extensions 
```
フォルダに 
```
embedimage.py
```
をコピーする。
**オリジナルのextensionを削除したくない場合は、ユーザーのextensionフォルダにインストールしてください。**
Mac OSでの動作は検証していません。

### windows

```
%APPDATA%\Inkscape\extensions
```
フォルダに
```
embedimage.py
```
をコピーする。
**オリジナルのextensionを削除したくない場合は、ユーザーのextensionフォルダにインストールしてください。**
Windows での動作は検証していません。


> [!NOTE]
> オリジナルのembedimage.py, embedimage.inx (またはimage_embed.py, image_embed.inx)を削除したくない場合は事前にコピーをとっておく.

## 使い方

リンク画像を選択し、右クリック->画像の埋め込み を選択するか、「エクステンション(extension)」 -> 「画像(Images)」-> 「画像の埋め込み(Embed Images)」を選択してください。


