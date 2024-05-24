# division calculator - Python
---

### 1.Write a 'try' code that takes inputs a and b, which may cause exceptions, and stores the values ​​of a/b in c
```
try:
  a, b = map(int, input("숫자 두 개를 입력해주세요: ").split())
  c = a/ b
```

### 2.Create an exception statement when a non-numeric number is entered
```
except ValueError :
  print("숫자를 입력해주세요")
```

### 3.Exception statement when 0 is entered in the denominator
```
except ZeroDivisionError :  
  print("입력한 숫자를 확인해주세요")
```

### 4.Error-free input calculations
```
else :
  print(f'{a} / {b} = {c}')
```

### 5.Code that always runs together
```
finally:
  print("calculation completed")
```
