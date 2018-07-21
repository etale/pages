# アデール

__Z__ は有理整数環，`lim` は射影極限，`colim` は帰納極限とする．

- __Zˆ__ `=` `lim` _n_ `\` __Z__
- __Q__ `=` `colim` __Z__ `/` _s_
- __A__ `=` __Zˆ__ `×` __R__

- (∂<sub>_t_</sub> `+` _H_ )ψ `=` `0`
- _F_ `=` _mM_ `/` `4π`_r_<sup>`2`</sup>
- _F_ `=` _qQ_ `/` `4π`_r_<sup>`2`</sup>

- 有理数体
  - __Q__ `=` `colim` __Z__ `/` _s_

- 有理整数環の副有限完備化（は長いので __剰余環__ はどう？）
  - __Zˆ__ `=` `lim` _n_ `\` __Z__

- _p_ 進整数環
  - __Z__<sub>_p_</sub> `=` `lim` _p_<sup>ν</sup> `\` __Z__
  - __Zˆ__ `=` `∏`<sub>_p_</sub> __Z__<sub>_p_</sub>（中国式剰余定理）

- _p_ 進体
  - __Q__<sub>_p_</sub> `=` __Z__<sub>_p_</sub> `⊗` __Q__

- 実数体
  - __R__ `=` __Q__<sub>`∞`</sub>

- アデール環
  - __A__ `=` __Zˆ__ `×`  __R__
  - __A<sub>Q</sub>__ `=` __A__ `⊗` __Q__ というか代数体 _K_ に対して __A__<sub>_K_</sub> `=` __A__ `⊗` _K_

- 有限アデールの表現
  - _n_ `\` _r_ `/` _s_

ここで _n_ は __法__ ，_s_ は __分母__ ，_r_ は __分子__ であり，
アデールの有限部分 __Zˆ__ `⊗` __Q__ の元の近似表示とみなす．

- `0` `\` _r_ `/` _s_ `=` _r_ `/` _s_
- _n_ `\` _r_ `/` `1` `=` _n_ `\` _r_

と書く．以下の対称的な操作がある．

- _s_ の逆元が `1` `/` _s_
  - _s_ `×` `1` `/` _s_ `=` `1`
- _r_ の反元が `-`_r_
  - _r_ `+` `-`_r_ `=` `0`
- _n_ の法が _n_ `\` `0`
  - _n_ `+` _n_ `\` `0` `=` _n_ `\` `0`

加法と乗法は局所体のレベルではつながっている．

  - `log` _x_ `=` `∑`<sub>_k_ `≥` `1`</sub> (`1` `−` `1` `/` _x_)<sup>_k_</sup> `/` _k_
  - `exp` _x_ `=` `∑`<sub>_k_ `≥` `0`</sub> _x_<sup>_k_</sup> `/` _k_`!`

局所体はチューブ状でsemver表示を持つ．

## 非アルキメディアンな場合
_p_ 進数はリトルエンディアンで表示する．
つまり，_p_ を _p_ 進で表示すると `0.1` となる．
また，非零な _x_ に対して

- _x_ `=` _p_<sup>`ord` _x_</sup> `sgn` _x_ `exp` `log` _x_

となるようにタイヒミュラー指標 `sgn` と対数 `log` を拡張しておく．
もちろん，常識的な定義域の範囲では
- `sgn` _x_ `=` `lim`<sub>_n_ → `∞`</sub> _x<sup>p<sup>n</sup></sup>_
- `log` _x_ `=` `∑`<sub>_n_ `≥` `1`</sub> (`1` `-` _x_<sup>`-1`</sup>)<sup>_n_</sup>/_n_

である．
- `ord` : `Gm`(__Q__<sub>_p_</sub>) → `Ga`(__Z__)
- `sgn` : `Gm`(__Q__<sub>_p_</sub>) → `Gm`(__Q__<sub>_p_</sub>)
- `exp` : `Ga`(__Q__<sub>_p_</sub>) → _p_ __Z__<sub>_p_</sub> → `1` + _p_ __Z__<sub>_p_</sub> → `Gm`(__Q__<sub>_p_</sub>)
- `log` : `Gm`(__Q__<sub>_p_</sub>) → `1` + _p_ __Z__<sub>_p_</sub> → _p_ __Z__<sub>_p_</sub> → `Ga`(__Q__<sub>_p_</sub>)

ここでレトラクション（準同型ではない）
- `Ga`(__Q__<sub>_p_</sub>) → _p_ __Z__<sub>_p_</sub>

を
`a.b` ↦ `0.b` つまり

- `∑` _c<sub>n</sub>p<sup>n</sup>_ ↦ `∑`<sub>_n_ `>` `0`</sub> _c<sub>n</sub>p<sup>n</sup>_

に選ぶ．
_p_ `=` `2` の場合は，さらに調整が必要．
もちろん常識的なところでは

- `exp` _x_ `=` `∑`<sub>n `≥` `0`</sub> _x<sup>n</sup>_ `/` _n_`!`

である．

ここまでは混標数．等標数の場合（有限体上のロラン級数体）もある．

## アルキメディアンな場合
実数や複素数はもちろんビッグエンディアンで表示する．

`τ` `=` `2πi` とする．
`0`, `1`, `e`, `τ`が複素数体における特別な元となっている．

- `abs` : `Gm`(__C__) → `Gm`(__C__)
- `sgn` : `Gm`(__C__) → `Gm`(__C__)
- `exp` : `Ga`(__C__) → `τ` `\` `Ga`(__C__) → `Gm`(__C__)
- `log` : `Gm`(__C__) → `τ` `\` `Ga`(__C__) → `Ga`(__C__)

ここで，セクション（準同型ではない）
- `τ` `\` `Ga`(__C__) → `Ga`(__C__)
は
- `τ` `\` `τ/2` ↦ `-τ/2`
に選んでおく．

`τ` `\` `Ga`(__C__) の元 _x_ を
_x_ `=` `a.b.c` `=` `a.b` `+` `τ` `×` `0.c`
のように書く．また，それが`exp`で移った先を
_x_ `X` `=` `exp` _x_
と書く．このように対数表示すれば，乗法・逆元・反元で誤差が発生せず，
- `e` `=` `1` `X`
- `-τ/2` `=` `0.0.5`
- `i` `=` `0.0.25` `X`

などとなる．
`a.b.c` `X`という表現では，
`a`がオーダー，`b`が精度，`c`が次元を表していると思える．
ちなみに`log`は
- `log` _x_ `=` `∫`<sub>`1`</sub><sup>_x_</sup> _ds_ `/` _s_

と定義されているものとする．

# 物理量・情報量

- `4π`_G_ `=` _c_ `=` ε<sub>0</sub> `=` μ<sub>0</sub> `=` _k_ `=` _h_ `/` `2πi` `=` `1`

とする．唐突に出てきた記号は
- __重力定数__
- __光速度__
- __真空の誘電率と透磁率__ （意味不明な名称）
- __ボルツマン定数__
- __プランク定数__

である．

普通は _h_ `=` `2π` とするが，それでは次元が退化しすぎる感じだし，
_pq_ - _qp_ `=` _h_ `/` `2πi` だけ見ても，
_h_ `=` `2πi` とみなしたくなる．

これらの量を慣用の単位系で表して
- _c_ `=` `299792458` `m` `s`<sup>`-1`</sup>
- _h_ `=` `6.626070040e-34` `kg` `m`<sup>`2`</sup> `s`<sup>`-1`</sup>
- _G_ `=` `6.67408e-11` `kg`<sup>`-1`</sup> `m`<sup>`3`</sup> `s`<sup>`-2`</sup>

とすれば， __C__ で解いて
- `kg` `=`  `18.908488.125` `X` `=` `exp`(`17.642958` `+` `2πi` `×` `0.125`)
- `m`  `=`  `78.844871.125` `X`
- `s`  `=`  `98.363472.125` `X`

となる．
ついでに
- _k_ `=` `1.3806488e-23` `J` `K`<sup>`-1`</sup> `=` `1`
- μ<sub>0</sub> `=` `4π` `×` `10`<sup>`-7`</sup> `N` `A`<sup>`-2`</sup> `=` `1`

とすれば
- `K`  `=` `-72.765617.125` `X`
- `A`  `=` `-56.280327` `X`

となる．
さらに情報量については
- `b` `=` `log` `2` `=` `0.693147` `=` `-0.366513` `X`
- `B` `=` `log` `2`<sup>`8`</sup> `=` `8` `log` `2` `=` `1.712929` `X`
- `KiB` `=` `2`<sup>`10`</sup> `B` `=` `8.644400` `X`
- `MiB` `=` `2`<sup>`20`</sup> `B` `=` `15.575872` `X`
- `GiB` `=` `2`<sup>`30`</sup> `B` `=` `22.507344` `X`

などとみなす．




ニュートン

- _F_ `=` _mM_ `/` `4π`_r_<sup>`2`</sup>
- _G_ `=` ν<sub>_G_</sub> `m`<sup>`3`</sup> `kg`<sup>`−1`</sup> `s`<sup>`−2`</sup> `=` `1` `/` `4π`
- `kg` `=` `4π`ν<sub>_G_</sub> `m`<sup>`3`</sup> `s`<sup>`−2`</sup>
- `N` `=` `kg` `m` `s`<sup>`−2`</sup> `=` ν<sub>_G_</sub> `m`<sup>`4`</sup> `s`<sup>`−4`</sup>
- `J` `=` `N` `m` `=` ν<sub>_G_</sub> `m`<sup>`5`</sup> `s`<sup>`−4`</sup>
- `W` `=` `J` `/` `s` `=` ν<sub>_G_</sub> `m`<sup>`5`</sup> `s`<sup>`−5`</sup>

マクスウェル

- _c_ `=` ν<sub>_c_</sub> `m` `s`<sup>`−1`</sup> `=` `1`
- `s` `=` ν<sub>_c_</sub> `m`
- `kg` `=` ν<sub>_G_</sub> ν<sub>_c_</sub><sup>`−2`</sup> `m`
- `N` `=` ν<sub>_G_</sub> `m`<sup>`4`</sup> `s`<sup>`−4`</sup> `=` ν<sub>_G_</sub>ν<sub>_c_</sub><sup>`−4`</sup>
- `J` `=` `N` `m` `=` ν<sub>_G_</sub> `m`<sup>`5`</sup> `s`<sup>`−4`</sup>
- `W` `=` `J` `/` `s` `=` ν<sub>_G_</sub> `m`<sup>`5`</sup> `s`<sup>`−5`</sup>
- _F_ `=` _qQ_ `/` `4π`_r_<sup>`2`</sup>

ボルツマン

- _k_ `=` ν<sub>_k_</sub> `J` `K`<sup>`−1`</sup> `=` `1`
- `K` `=` ν<sub>_k_</sub> `J`
