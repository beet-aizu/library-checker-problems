Problem Statement (Japanese) / 問題文 (日本語)
---------

$N$ 頂点 $M$ 辺の無向グラフが与えられる。$i$ 番目の辺は $(a_i, b_i)$ である。このグラフは単純とは限らないが、自己ループを含まない。
このグラフを二重頂点連結成分分解してください。



Constraints / 制約
---------

- ${{param N_MIN}} \leq N \leq {{param N_MAX}}$
- ${{param M_MIN}} \leq M \leq {{param M_MAX}}$
- $0 \leq a_i, b_i < N$
- $a_i \neq b_i$

Input / 入力
---------

~~~
$N$ $M$
$a_0$ $b_0$
$a_1$ $b_1$
:
$a_{M - 1}$ $b_{M - 1}$
~~~

Output / 出力
---------

$K$ を二重頂点連結成分の個数として、$1 + K$ 行出力する。
最初の行には $K$ を出力し、その後 $K$ 行では以下のように出力する。$l$ は二重頂点連結成分の辺数であり、$v_i$ はその辺番号である。

~~~
$l$ $v_0$ $v_1$ ... $v_{l-1}$
~~~

正しい出力が複数存在する場合は、どれを出力しても構わない。


Sample / サンプル
---------

{{example example_00}}

{{example example_01}}

{{example example_02}}
