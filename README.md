# cjc101-05
# Docker 三大工具
1. docker machine
	跨多主機 安裝Docker
2. [[docker compose]]
	單主機多容器 cluster ------> Dockerfile
3. docker swarm (已經非常少用)  用這個倒不如去用k8s
	多主機多容器cluster

# Dockerfile
- 是文字檔
- 用來做映像檔

| Dockfile | 食譜                  | 備註       |
| -------- | ------------------- | -------- |
| From     | 料理類型                |          |
| Label    | 出版社、version         | 可有可無     |
| Run      | step1->step2->..... |          |
| CMD      | 用甚麼呈現               | (用甚麼盤子裝) |

