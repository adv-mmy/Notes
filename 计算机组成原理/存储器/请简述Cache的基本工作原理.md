书P110~P111

- 将主存和Cache都分成同样大小的若干块
- 将CPU近期要用到的程序提前存入Cache
- CPU访问主存某字时——
	- **CPU访问Cache命中**：所需的字在Cache中（*主存块与缓存块建立了对应关系*）
	- **CPU访问Cache不命中**：所需的字不在Cache中，需要将字所在的主存块调入Cache中
- Cache满时，按一定的算法将Cache中的块移回主存