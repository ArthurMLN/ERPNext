# ERPNext
* 先下载代码到本地，之后把 `compose.yaml` 用本地文件置换，主要是更改数据库文件到 `frappe_docker` 里面保存数据。
* 实质上是copy 这个frappe_docker 文件夹，然后运行就可以，数据在里面

```shell
git clone https://github.com/frappe/frappe_docker
cd frappe_docker
docker compose -f pwd.yml up -d
```
