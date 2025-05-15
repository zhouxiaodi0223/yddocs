# string_set
## 功能描述
设置指定 key 的值：传入一个redis连接实例，实现对该实例下的redis进行字符串格式的数据保存。（注意：将value字符串保存到redis的key中，key的命名方式建议大家遵从python的标识符命名规则）
## 使用说明
输入：
connection_pool:redis连接实例，是启动redis连接指令的返回值
key：用于查找value值的索引名称，建议使用python的标识符命名规则，格式为字
符串
value： 存储在key下的值，各种类型均可，该指令会对value进行一次json封装后再
set到redis中
## 应用场景
