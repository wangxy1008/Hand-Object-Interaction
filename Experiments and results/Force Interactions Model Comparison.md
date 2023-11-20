

## 抓点

![Screenshot 2023_10_11 2_35_11](Screenshot 2023_10_11 2_35_11.png)

### 算法一

抓握副日志

```
Test AlgorithmType: [1] => finger1 : Name :Classic Hand (R)无名指[0], finger2: Name :Classic Hand (R)拇指[2], vi : (0.00, 1.00, -0.59), vj: (0.08, 1.04, -0.51), normal: (-0.20, 0.00, -0.98), angle: 37.9372, ALPHA: 65, angle < ALPHA: True && angle >= 0: True

Test AlgorithmType: [1] => finger1 : Name :Classic Hand (R)拇指[2], finger2: Name :Classic Hand (R)无名指[0], vi : (0.08, 1.04, -0.51), vj: (0.00, 1.00, -0.59), normal: (0.98, 0.00, -0.20), angle: 58.24045, ALPHA: 65, angle < ALPHA: True && angle >= 0: True

[18648] JudgmentCanGrab verification passed 
```

### 算法二

抓握副日志

```
[9734] JudgmentCanGrab verification failed 
```

### 算法三

抓握副日志

```
 Test AlgorithmType: [3] => finger1 : Name :Classic Hand (R)食指[0], finger2: Name :Classic Hand (R)拇指[2], vi : (0.05, 1.04, -0.60), vj: (0.08, 1.04, -0.51), normal: (0.00, 1.00, 0.00), angle: 87.93959, ALPHA: 65, angle < ALPHA: False && angle >= 0: True
 
  Test AlgorithmType: [3] => finger1 : Name :Classic Hand (R)食指[1], finger2: Name :Classic Hand (R)拇指[2], vi : (0.05, 1.04, -0.60), vj: (0.08, 1.04, -0.51), normal: (0.00, 1.00, 0.00), angle: 87.93959, ALPHA: 65, angle < ALPHA: False && angle >= 0: True
  
   Test AlgorithmType: [3] => finger1 : Name :Classic Hand (R)食指[2], finger2: Name :Classic Hand (R)拇指[2], vi : (0.05, 1.04, -0.60), vj: (0.08, 1.04, -0.51), normal: (0.98, 0.00, -0.20), angle: 93.44924, ALPHA: 65, angle < ALPHA: False && angle >= 0: True
   
    Test AlgorithmType: [3] => finger1 : Name :Classic Hand (R)食指[5], finger2: Name :Classic Hand (R)拇指[2], vi : (0.05, 1.04, -0.60), vj: (0.08, 1.04, -0.51), normal: (0.00, 1.00, 0.00), angle: 87.93959, ALPHA: 65, angle < ALPHA: False && angle >= 0: True
    
     Test AlgorithmType: [3] => finger1 : Name :Classic Hand (R)食指[6], finger2: Name :Classic Hand (R)拇指[2], vi : (0.05, 1.04, -0.60), vj: (0.08, 1.04, -0.51), normal: (0.00, 1.00, 0.00), angle: 87.93959, ALPHA: 65, angle < ALPHA: False && angle >= 0: True
     
[18648] JudgmentCanGrab verification passed 
```

## 抓棱



<img src="image-20231011032846898.png" alt="image-20231011032846898" style="zoom:50%;" /><img src="image-20231011032850209.png" alt="image-20231011032850209" style="zoom:50%;" />

### 算法一

抓握副日志

```
 Test AlgorithmType: [1] => finger1 : Name :Classic Hand (R)中指[3], finger2: Name :Classic Hand (R)拇指[6], vi : (0.03, 1.04, -0.57), vj: (0.05, 1.01, -0.50), normal: (0.00, 1.00, 0.00), angle: 64.75794, ALPHA: 65, angle < ALPHA: True && angle >= 0: True

 Test AlgorithmType: [1] => finger1 : Name :Classic Hand (R)拇指[6], finger2: Name :Classic Hand (R)中指[3], vi : (0.05, 1.01, -0.50), vj: (0.03, 1.04, -0.57), normal: (-0.07, 0.00, 1.00), angle: 31.16945, ALPHA: 65, angle < ALPHA: True && angle >= 0: True
 
 [18648] JudgmentCanGrab verification passed 
```

### 算法二

抓握副日志

```
 Test AlgorithmType: [1] => finger1 : Name :Classic Hand (R)中指[3], finger2: Name :Classic Hand (R)拇指[6], vi : (0.03, 1.04, -0.57), vj: (0.05, 1.01, -0.50), normal: (0.00, 1.00, 0.00), angle: 64.75794, ALPHA: 65, angle < ALPHA: True && angle >= 0: True

 Test AlgorithmType: [1] => finger1 : Name :Classic Hand (R)拇指[6], finger2: Name :Classic Hand (R)中指[3], vi : (0.05, 1.01, -0.50), vj: (0.03, 1.04, -0.57), normal: (-0.07, 0.00, 1.00), angle: 31.16945, ALPHA: 65, angle < ALPHA: True && angle >= 0: True
 
 [18648] JudgmentCanGrab verification passed 
```

### 算法三

抓握副日志

```
 [9734] JudgmentCanGrab verification failed 
```

## 抓面



<img src="image-20231011031628365.png" alt="image-20231011031628365" style="zoom:50%;" /><img src="image-20231011031714433.png" alt="image-20231011031714433" style="zoom:50%;" />

### 算法一

抓握副日志

```
 Test AlgorithmType: [1] => finger1 : Name :Classic Hand (R)无名指[0], finger2: Name :Classic Hand (R)食指[2], vi : (0.09, 1.00, -0.63), vj: (0.10, 1.04, -0.62), normal: (-0.70, 0.00, -0.71), angle: 64.41351, ALPHA: 65, angle < ALPHA: True && angle >= 0: True
 
  Test AlgorithmType: [1] => finger1 : Name :Classic Hand (R)食指[2], finger2: Name :Classic Hand (R)无名指[0], vi : (0.10, 1.04, -0.62), vj: (0.09, 1.00, -0.63), normal: (0.00, 1.00, 0.00), angle: 25.68797, ALPHA: 65, angle < ALPHA: True && angle >= 0: True
  
  [18648] JudgmentCanGrab verification passed 
```

### 算法二

抓握副日志

```
 Test AlgorithmType: [2] => finger1 : Name :Classic Hand (R)小手指[0], finger2: Name :Classic Hand (R)拇指[0], vi : (0.08, 0.98, -0.62), vj: (0.11, 1.04, -0.58), normal: (-0.70, 0.00, -0.71), angle: 50.99549, ALPHA: 65, angle < ALPHA: True && angle >= 0: True
 
  Test AlgorithmType: [2] => finger1 : Name :Classic Hand (R)拇指[0], finger2: Name :Classic Hand (R)小手指[0], vi : (0.11, 1.04, -0.58), vj: (0.08, 0.98, -0.62), normal: (0.00, 1.00, 0.00), angle: 39.71954, ALPHA: 65, angle < ALPHA: True && angle >= 0: True
  
  [18648] JudgmentCanGrab verification passed 
```

### 算法三

抓握副日志

```
[16392] JudgmentCanGrab verification failed 
```

### 