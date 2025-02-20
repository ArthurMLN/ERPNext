# ERPNext
* 先下载code 到本地，之后把compose.yaml 用本地文件置换，主要是更改数据库文件到frappe_docker 里面保存数据。


'''
git clone https://github.com/frappe/frappe_docker
cd frappe_docker
docker compose -f pwd.yml up -d
'''
