Q:  What does the code ``` [url path]``` do?

A:  返回url的相对路径，猜测是查找到第一个slash('/')返回该slash及其后面所有的字符串。

eg: "http://www.baidu.com/haha/gaga" -> "/haha/gaga"

Q: What does the code ```[url absoluteString]``` do?

A:  返回url的绝对路径。

eg: "http://www.baidu.com/haha/gaga" -> "http://www.baidu.com/haha/gaga"

Q:  What does the code ```[url URLByAppendingPathComponent:@""]``` do?

A:  保证路径最后一个字符含有slash('\')。

eg: "http://www.baidu.com/haha/gaga" -> "http://www.baidu.com/haha/gaga/"