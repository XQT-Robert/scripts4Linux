To save my scripts

待更新：
1、防护指令，用于指定开发板挂载目录，因为主系统和子系统均是linux目录结构相同，容易导致重大错误，因此仿照sudo，暂定名为board，使处于该命令状态下免受错误影响，比如board cp [文件目录] [文件目录]，其中某个目录可能是挂载目录而并非主机目录，设计一个指令确保这个过程正确，暂无具体设计。