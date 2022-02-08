# Writing a lambda

## Syntax

```python
lambda parameters: expression
```

## Examples

### Single argument

```python
double = lambda num : num * 2
print(double(10))
```

### Multiple arguments

```python
add = lambda val1, val2 : val1 + val2
print(add(10, 20))
```

### Conditions on expression

```python
compare = lambda val1, val2 : val1 if val1>val2 else val2
print(compare(10, 20))
```
