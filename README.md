# moggle-preview-being0606

# AI융합학과 학술동아리 Moggle 사전미션을 위한 레포지터리입니다.

## 타이타닉 데이터셋 불러오기 및 head 확인

```python
import pandas as pd

# 데이터셋 불러오기
titanic = pd.read_csv('titanic.csv')

# 데이터셋의 상위 5개 행 확인
print(titanic.head())
