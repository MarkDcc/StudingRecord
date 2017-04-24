exchanger是一款汇率换算的app,目前只支持RMB和JPY(日元)之间的换算

### 一. 主要功能
1. 点击对应数字按钮和小数点按钮会在输入栏中显示对应的结果
输入框中的数只能允许存在一个小数点
2. 删除按钮会将最后一位数字删除
如果最后一位数是小数点,则小数点也会被清除
3. 显示当前汇率
使用`Alamofire`异步获取汇率api,然后采用`swiftJSON`解析json数据并展示
4. 清除按钮
会将输入栏和结果栏的数据全部置0
5. 切换按钮
可以切换RMB和JPY(日元)的实时汇率和换算功能. 

### 二.使用技术
1. 整个功能采用swift3.0.2实现
2. pod 1.2.1 管理依赖
3. 网络框架`Alamofire`4.4 获取api数据
4. 使用`swiftJSON`3.1.4对获取的json数据进行解析
5. 使用`SnapKit`3.2.0做自动布局(暂未实现)

### 三.截图
![](http://image.xiaomo.info/swift/exchanger-icon.png)
![](http://image.xiaomo.info/swift/exchanger-ui.png)

### 四. 功能演示
![](http://image.xiaomo.info/swift/exchanger.gif)


### 五. 做此app的动机
1. 最近在学swift,这是个不错的练手项目
2. 打算去日本,所以做个app装到自己手机上用,即方便又有成就感,哈哈哈
