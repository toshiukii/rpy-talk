
PyCon JP 2017でのToshiyuki Takedaのトーク「[PythonとRを行ったり来たり](https://pycon.jp/2017/ja/schedule/presentation/18/)」の資料です。

rpy_pyconjp17.ipynbがトークの資料で、使われるデータtips.csvは、以下の方法で作成しました。

import seaborn as sns
tips = sns.load_dataset("tips")
tips.to_csv('tips.csv', index=False)

