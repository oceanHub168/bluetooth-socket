# bluetooth-socket
基本bluetooth 经典蓝牙实现双向通信封装的jar包，可传输大数据

使用方法：
服务器端：
/**
* 注册服务
**/
BluetoothUtilManager.getInstance().start()

客户端：
/**
* 使用mac地址链接
**/
BluetoothUtilManager.getInstance().connect("BT Macaddress")
  
/**
* 监听bluetooth的状态，implement BluetoothObserver 接口
**/
BluetoothUtilManager.getInstance().addObserver(this)

/**
* 发送数据
**/
BluetoothUtilManager.getInstance().sendData("Hello bluetooth")

/**
* 注销服务
**/
BluetoothUtilManager.getInstance().stop()  


下载地址：
链接: https://pan.baidu.com/s/1CQDmlKQoJVyvXTzWhqRnAA 提取码: efew
