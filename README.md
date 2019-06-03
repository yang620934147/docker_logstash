# docker_logstash
容器中运行logstash,同步mysql数据到elasticsearch

# 启动命令
docker run -d --name logstashmysql -v /home/docker/logstash/:/some/config-dir/ my-logstash
