### Q1: node的内存管理

node把整个内存空间分为新生代和老生代，新生代采用Scavarge算法，消耗资源较大，该算法把新生代的空间分为from-space和to-space

