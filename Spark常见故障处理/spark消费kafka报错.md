# java.io.IOException: Connection to 1 was disconnected before the response was read

解决办法：

重启 1 对应的kafka broker节点，单独消费这个topic发现消费不了，也不报错

类似的报错也有可能kafka broker的hostname解析有问题，加入到hosts里面就好了
