#二进制
0和1 比特 bit 位，是计算机系统中数据的原始单位
1 1 1 1 1 1 1 1
16 8 4 2
8个bit称为一个字节byte。
最小值 全是0，那么对应十进制 0
最大值 全是1，对应十进制 255
#二进制到文本
计算机只认识 0 和 1
我们只认识 a b c 中国 字符
编码系统用于将二进制转化为文本
ASCII 英文字母 数字 标识符号，一共128个 0-127
WEB上使用最多的utf-8，它可以表示世界上绝大多数的字符
#node.js如何处理二进制
js可以很好的处理unicode，不能处理二进制
- TCP发送和接收数据
- 对图片进行压缩传输
- 从文件里读取数据
- 从HTTP里读取客户端传过来的请求体
#buffer
缓存区，处理二进制的一种方式，是对原始内存的分配
buffer是由字节组成
11111111
255
