#ADBshell命令集合
 >1.自动化测试传递参数
 >
 adb shell am instrument -w -e username admin -e password admin com.alibaba.mqc.test/com.alibaba.mqc.test.MqcTestRunner