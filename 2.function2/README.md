## 要求 
    
- 新建main.js文件，编写一个函数，实现以下功能：判断一个字符串是否是回文串。（回文，一个字符串从前面读和从后面读都一样，例如：abcba就是回文串。）

function palindRome(str){
    var len = str.length;
    var str1 = "";
    for(var i=len-1; i>=0;i--){
        str1+=str[i];
    }
    console.log(str1 == str)
}
palindRome("abcba");//true
palindRome("abcbac");//false
