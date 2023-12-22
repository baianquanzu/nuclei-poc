以上漏洞poc均使用nuclei运行
基本命令：
nuclei -l mubiao.txt -t poc.yaml
单个目标
nuclei -u xxx.com:8888 -t poc.yaml
