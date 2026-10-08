# Class

授業で使用するデータを置いています．

## student-por.csv

- 内容：ポルトガルの中等学校2校の生徒649名の学業成績と属性（Student Performance Data Set の「ポルトガル語」科目）．区切り文字はセミコロン（`;`）
- 出典：P. Cortez and A. Silva. "Using Data Mining to Predict Secondary School Student Performance." In A. Brito and J. Teixeira (Eds.), *Proceedings of 5th Future Business Technology Conference (FUBUTEC 2008)*, pp. 5-12, Porto, Portugal, April, 2008, EUROSIS.
- 配布元：[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/320/student+performance)
- ライセンス：[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)（配布元のデータを改変せずに掲載しています）

Python（pandas）での読み込み例：

```python
import pandas as pd
df = pd.read_csv(
    "https://raw.githubusercontent.com/kabajiro/Class/main/student-por.csv",
    sep=";"
)
```
