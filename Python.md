```Python
ファイルオープン
f = open('input/donation_202004.txt','r',encoding='utf-8')
donations = f.read()
donations = f.readlines()
#一行ずつリスト形式で保存する。
f.close()
print(donations)

#文字列の後ろに .strip() をつけると末尾の改行文字を除去できる
schedule.replace('コナツ製薬','ココナッツ製薬')
#対象文字列.replace(変換前の文字列, 変換後の文字列) で文字列を置換する

#3つのダブルクォーテーションで囲むと、改行付きの文章を囲める。

#文字列.strip()で改行を除去

#文字列.split(区切りたい文字列)で区切りたい文字列で文字列を区切り、リスト化する。

#文字列.endswith(特定の文字列) を使うと、 特定の文字列 で終わるとき

#strip()関数はリストに対しては使えない。

#with openをつかうことで、f.close()を書く必要がない。ただし、インデントを忘れてはいけない。

#文字列.rstrip() メソッドは文字列の末尾部分に存在する空白文字（半角スペース 、 全角スペース 、 タブ 、 改行 など）を取り去ります。

#文字列.split(区切り文字) と文字列を区切っている文字を指定するとその文字ごとに値を分割し、リストを作成します。

#ファイルの関数を実行するときには
if __name__ == '__main__':
    関数呼び出し
```