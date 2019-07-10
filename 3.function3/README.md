## 要求 
    
- 新建main.js文件，编写一个函数，实现以下功能：按字母表顺序输出传入的参数字符串。

<script type="text/javascript">  
    let arr = ['abc', 'aba', 'aef', 'Def', 'BoC', 'FED'];  
    let arrSort = arr.sort(function(s, t) {  
        let a = s.toLowerCase();  
        let b = t.toLowerCase();  
        if (a < b) return -1;  
        if (a > b) return 1;  
        return 0;  
    })
