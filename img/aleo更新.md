![image](https://user-images.githubusercontent.com/53888545/237594478-655195eb-d5f5-41ef-be36-d38b62a8163d.png)

Aleo对Mapping所支持的操作做了重构，原先只支持`increment` `decrement`，现在可以支持`get get_or_init set`的操作。（要注意的是对Mapping的操作只能定义在合约的Finalize中）

这意味着我们可以在`Finalize`中读取和修改`Mapping`中的值，这对于开发一些dapp来说是必不可少的。

 