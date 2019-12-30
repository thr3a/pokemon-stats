# Pokemon stats

ポケモンソードシールド(剣盾)に出てくるポケモンの種族値とタイプの一覧

# Columns

- name 名前
- h HP
- a	攻撃
- b	防御
- c	特攻
- d	特防
- s	すばやさ
- sum	h〜sの合計値
- type1	タイプ1
- type2 タイプ２

タイプが１種類しかないポケモンはtype2は空(NaN)になる

# sample

```python
import pandas as pd
url = 'https://raw.githubusercontent.com/thr3a/pokemon-stats/master/pokemon.csv'
df = pd.read_csv(url, index_col=0)
df.head()
```
