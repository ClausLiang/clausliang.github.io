# el-input输入框限制输入数字
```
for (var i = 0; i < 4; i++) {
    setTimeout(() => {
        console.log(i)
    }, 0)
}
```
```
for (let j = 0; j < 4; j++) {
    setTimeout(() => {
        console.log(j)
    }, 0)
}
```
**第一段的输出结果是4444**<br>
**第二段的输出结果是0123**<br>

let是块级作用域，所以会导致结果不一样