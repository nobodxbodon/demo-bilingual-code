<table>
<tr>
<th> English </th>
<th> Chinese </th>
</tr>
<tr>
<td>

```python
menu = [
  "Fried Cabbage",
  "Kung Pao Chicken",
  "Beef with Broccoli",
  "Sweet and Sour Pork",
  "Salted Fish Fillet"
]

def containsIngredient(dishName, ingredient):
  return ingredient in dishName

def findYummyFood(cuisine, preference):
  return list(filter(
    lambda dish:
      containsIngredient(dish, preference), cuisine))

findYummyFood(menu, 'Beef')
```

</td>
<td>

```python
菜单 = [
  "炒包菜",
  "宫保鸡丁",
  "西兰花牛肉",
  "咕咾肉",
  "椒盐鱼片"
]

def 有配料(菜名, 配料):
  return 配料 in 菜名

def 找好吃的(美食, 喜好):
  return list(filter(
    lambda 菜:
      有配料(菜, 喜好), 美食))

找好吃的(菜单, '牛')
```

</td>
</tr>
</table>