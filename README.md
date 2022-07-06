# Masscan2Httpx2Nuclei
masscan全端口扫描==>httpx探测WEB服务==>nuclei漏洞扫描
`解放双手`
# 环境准备 
- 自备nuclei httpx 放脚本同目录(文件名不变)
- 自备masscan python3
- pip3 install -r requirement.txt
- 将要扫描的资产放在ip.txt里面
- python3 Masscan2Httpx2Nuclei.py -i ip.txt -p 1-65535 --rate 2000
- **睡一觉**
## 没啥技术含量的脚本，能用就行
![image](https://user-images.githubusercontent.com/62868358/177557080-c4c89b89-d826-4e07-a6e7-6b2e9e600721.png)


# ToDo
`联动xray`
# 关于
* **[masscan](https://github.com/robertdavidgraham/masscan)**
* **[httpx](https://github.com/projectdiscovery/httpx/releases/)**
* **[nuclei](https://github.com/projectdiscovery/nuclei/releases)**

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=mbskter/Masscan2Httpx2Nuclei&type=Date)](https://star-history.com/#mbskter/Masscan2Httpx2Nuclei&Date)
