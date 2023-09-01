# HUIWEN
汇文图书馆书目检索系统信息泄露  POC

# 漏洞描述  

汇文 图书馆书目检索系统 /include/config.properties 文件中包含敏感信息，攻击者可以直接访问获取信息

# 漏洞影响  

汇文v5.6  

# fofa搜索 

app="汇文软件-书目检索系统"  

#  Usage:
  python3 huiwen.py -h  
  python3 huiwen.py -u http://www.example.com  
  python3 huiwen.py -f url.txt  
# 提示
运行脚本后会在目录自动生成存在漏洞的valuable.txt  

# 免责声明
由于传播、利用此文所提供的信息而造成的任何直接或者间接的后果及损失，均由使用者本人负责，作者不为此承担任何责任。
