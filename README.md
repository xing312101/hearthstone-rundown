# hearthstone-rundown
Generate hearthstone rundown json easily

## Input Type
### 1. click
```
  {
    "type": "click",
    "x": 123,
    "y": 321
  }
```

### 2. drag
```
  {
    "type": "drag",
    "xFrom": 123,
    "yFrom": 321,
    "xTo": 123,
    "yTo": 321
  }
```

### 3. MF2MTX

Multiple F drag to multiple T only x axis

```
  {
    "type": "MF2MTX",
    "xFrom": 123,
    "yFrom": 321,
    "fromInterval": 2,
    "fromDistance": 5,
    "xTo": 123,
    "yTo": 321,
    "toInterval": 2,
    "toDistance": 10
  }
```
