## Intro.
> Convert chinese written string to read string. 将中文书面字符串转换为口语字符串。


## Usage
```python
from cntn import w2s

print(w2s("小王的身高是153.5cm,梦想是打篮球!我觉得有0.1%的可能性。"))
# 小王的身高是一百五十三点五厘米,梦想是打篮球!我觉得有百分之零点一的可能性。
print(w2s("小王的钱包有1116$，可以买个iphone7s。"))
# 小王的钱包有一千一百一十六$，可以买个IPHONE七S。
```


## Install
```bash
# from source
git clone https://github.com/Free-D/cn-text-normalizer-free.git
cd cn-text-normalizer
python setup install
# or
pip install https://github.com/Free-D/cn-text-normalizer-free
```


## Config

