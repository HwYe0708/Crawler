# GitHub
GitHub_base 

1. 创建文件 ---> 需要在仓库文件夹内
    创建 readme.txt 文本文件
        Git is a distributed version control system.
        Git is free software.
2. 同步(将目标文件添加至工作区缓存)
    git add readme.txt
3. 修改后同步且查看修改内容
    1. 将readme.txt修改为
        Git is a distributed version control system.
        Hello World
    2. 查看数据情况
        1. $ git status
        注意：如果显示modified表示目标文件已被修改,但尚未同步
        2. $ git diff readme.txt
        >>> 此处会显示修改内容
    3. 同步上传
        git add readme.txt
4. 总结
    1. git add 目标文件名 ----> 添加目标文件到缓存区
    2. git commit -m "注释" --->提交更改文件
