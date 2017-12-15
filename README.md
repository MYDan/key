# key

mydan agent 公钥自动更新请求的地址样例

https://raw.githubusercontent.com/MYDan/key/master/keyupdate


使用过程:
    
    1. 用ssh-keygen命令生成一对公私钥。
    2. 把公钥放到这个项目中
    3. 编辑keyupdate文件,格式为 md5:url
    4. 提交git

    5. 把私钥加上后缀 .key
    6. 把私钥放到 mydan/etc/agent/auth 下

    7. 等待agent自动过来更新公钥

