众多的git merge可视工具中，还是Intellij Idea的最好用，但是Tower中无法直接选中Intellij Idea作为diff或者merge工具，执行这个脚本之后就可以了。

用法为clone工程后直接运行`install.sh`即可：

```shell
cd /tmp
git clone git@github.com:suclogger/tower-idea-shim.git
cd tower-idea-shim
sh install.sh
```

**默认支持版本为Tower 3，其他版本请修改shell中的目录地址**