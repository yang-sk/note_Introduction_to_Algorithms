## 算法基础
### 插入排序
```
for j=2 to A.length
  key=A[j]
  // insert A[j] into right place
  i=j-1
  while i>0 and A[i]>key
    A[i+1]=A[i]
    i=i-1
  A[i+1]=key
```
