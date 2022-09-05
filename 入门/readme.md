### internal & external
internal只能由合约内部调用，external可以通过外部调用

### payable
能给合约支付eth的函数

### returns & return

### 数据储存
storge：状态变量默认，储存在链上
memory:不上链
calldata:不上链 不能修改

### mapping



### constant immutable
只有数值变量可以声明constant immutable string和bytes可以声明为constant,但不能为immutable
让变量保持不变可以节省gas

###constructor
constructor每个合约可以定义一个，在部署合约的时候自动运行一次，初始化合约的参数

利用modifier定义onlyowner，再定义一个只有onlyowner可以调用的函数

### inheritance
加上virtual，父合约的函数可以在子合约重写
子合约重写了父合约的函数需要加上override
子合约调用父合约的函数有两种方法：直接调用；super调用

###异常
error require assert error 消耗gas最少
