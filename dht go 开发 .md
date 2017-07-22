dht 例子分析
======

# mainline dht 介绍
https://en.wikipedia.org/wiki/Mainline_DHT
# 参考代码地址
https://github.com/shiyanhui/dht

# krpc
  Queries, or KRPC message dictionaries with a "y" value of "q", contain two additional keys; "q" and "a". 
  Key "q" has a string value co    ntaining the method name of the query. Key "a" has a dictionary value containing named arguments to the query.
  如果有别人来查询节点，自己就是得到了query,定义了以下4种查询
  const (
	pingType         = "ping"
	findNodeType     = "find_node"
	getPeersType     = "get_peers"
	announcePeerType = "announce_peer"
)  


# peermanager
	 
