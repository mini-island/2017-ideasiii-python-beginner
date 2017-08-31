* [回上層../](../)

## sample codes

```python
# 執行時自行註解掉不需要的段落

# 自動型別
var = 'Hello World'  # string
print(var)
var = 100            # int
print(var+10)
print('-----')

# 沒有 overflow
var = 17**3000  # 17的3000次方
print(var)
print('-----')

# swap
a=1
b=2
c=3
print(a,b,c)
c,a,b=b,c,a
print(a,b,c)
print('-----')

# string index
var1 = 'Hello World'
var2 = "Python Programming"
print(var1[0]) # H, 從0開始
print(var2[1:5]) # "ytho", 1到小於5
print('-----')
```
* [下載 sample.py](sample.py)
* [Run it online](https://repl.it/K701/latest)

## 參考資訊
* [內建的 data type](https://docs.python.org/3/library/stdtypes.html)
