## 要求 
    
- 新建main.js文件，编写一个函数，实现以下功能：计算出一个字符串共有多少个单词组成。
   
   
   function getTextLength(txt) {
        for(var i=0;i<txt.length;i++)
            console.log(txt.charAt(i), txt.charCodeAt(i))

        return txt.length;
    }
