# 2020
## Sun, 24th May   
VScode ``Run Python File in Terminal`` 시 발생하는 에러   
   
```shell
SyntaxError: invalid syntax
>>> /opt/anaconda3/bin/python /Users/../...py
  File "<stdin>", line 1
    /opt/anaconda3/bin/python /Users/../...py
    ^
```   
    
VScode의 버그이다.   
터미널 창에서 ``exit()``후에 다시 ``Run Python File in Terminal`` 하면 정상적으로 실행된다.   
   
<sub><sup>Written by </sup><sup>@DeepxHyeon</sup></sub>   
   