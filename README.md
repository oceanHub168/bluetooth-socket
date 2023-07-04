# bluetooth-socket
基本bluetooth 经典蓝牙实现双向通信封装的jar包，可传输大数据

使用方法：

<b>注册服务</b>

        BluetoothUtilManager.getInstance().start()

<b>使用mac地址链接</b>

        BluetoothUtilManager.getInstance().connect("BT Macaddress")
  
<b>监听bluetooth的状态，implement BluetoothObserver 接口</b>

        BluetoothUtilManager.getInstance().addObserver(this)

<b>发送数据</b>

        BluetoothUtilManager.getInstance().sendData("Hello bluetooth")

<b> 注销服务<b>

        BluetoothUtilManager.getInstance().stop()  


下载地址：
链接: https://pan.baidu.com/s/1CQDmlKQoJVyvXTzWhqRnAA 提取码: efew
