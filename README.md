
＃A whole bunch of training date.
which comes in the form of a bunch of different images of handwritten digits along with labels for what they're supposed to end.

1.輸入：一個演算法必須有零個或以上輸入量。

2.輸出：一個演算法應有一個或以上輸出量，輸出量是演算法計算的結果。

3.明確性：演算法的描述必須無歧義，以保證演算法的實際執行結果是精確地符合要求或期望，通常要求實際執行結果是確定的。

4.有限性：依據圖靈的定義，一個演算法是能夠被任何圖靈完備系統類比的一串運算，而圖靈機只有有限個狀態、有限個輸入符號和有限個轉移函式（指令）。而一些定義更規定演算法必須在有限個步驟內完成任務。

5.有效性：又稱可行性。能夠實現，演算法中描述的操作都是可以通過已經實現的基本運算執行有限次來實現。


```
int max(int*array, int size)
{
    int mval = *array;
    int i;
    for(i = 1; i < size; i++)
     if(array[i] > mval)
      mval = array[i];
    rturn mval;  
}
```

```
void swapi(int *X, int *y)
{
    int tmp = *X;
    *x = *y;
    *y = tmp;
}

int gcd(int m, int n)
{
    int r;
    do
    {
     if(m < n)
       swapi(&m, &n);
    r = m % n;
    m = n;
    n = r;
    } while (r);
    return m;
}
```

```
int gcd(int a,int b)
{
    if(a%b)
     return gcd(b,a%b);
    return b; 
}
```


