# このライブラリはtest用兼ポートフォリオ用です
## 注意事項
あくまでも学習とポートフォリオを兼ねたものなのでインストールの際は自己責任でお願いします
## 使用方法
import algomath_def で使用できるようになります
## 使用できるモジュール
例 algomath_def.関数名 で使用できます
### 1.数学系関数
数学系に関する関数です
#### mcd(最大公約数を返すメソッド)引数(int a, int b)計算量O(log N)
x = algomath.mcd(a,b)  
int型の最大公約数を返します  
ユークリッドの互除法を使用

### 2.アルゴリズム系関数
アルゴリズムに関する関数です
#### parSum(ビット全探索を用いた部分和問題のメソッド)引数(int a,list b)計算量(N*2^N)
list bの中に存在する数字の内、特定の組み合わせの結果がansに一致するものを探す。  
ansに一致する組み合わせを選んだものを２進数で表現し(リスト内の各位置を表す)、全てリストに格納して返す

## その他事項
学習したものを関数化したものを随時追加していきます  
問題点や異常点などございましたらご指摘頂けましたら幸いです

