### 编写可接受任意数量参数的函数

```python
def avg(first, *rest):
    return (first + sum(rest)) / (1 + len(rest))
```
