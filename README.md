
1. 打开教学评价网页，先按CTRL + SHIFT + I 
2. 再按下CTRL + SHIFT + C
3. 随便勾一个单元格，然后再在CONSOLE下输入以下内容回车即可
4. 注意最后要自己点确认
5. 可以给所有老师满分
```javascript
var tables = document.getElementsByTagName('table');

for (let i = 0; i < (tables.length) / 2; i++) {
    for(let j = 0; j < 5; j++){
        document.getElementById(`id_x${i}_${j}_1`).click();
    }
    for (let k = 0; k < 10; k++) {
    document.getElementById(`id_z${i}_${k}_1`).click();
    }
}
```
