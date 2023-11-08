# Algorithmic_Trading_YL
Algorithmic Trading – Machine Learning & Quant Strategies Course with Python

Youtube lecture: https://www.youtube.com/watch?v=9Y3yaoi9rUQ

Using Python

get Error List
 <li> df['bb_low'] = df['bb_low'] = df.groupby(level=1)['adj close'].transform(lambda x: pandas_ta.bbands(close=np.log1p(x), length=20).iloc[:, 0]) </li> --> Solved
 <li> df['atr'] = df.groupby(level=1, group_keys=False).apply(compute_atr) </li>
