FROM python:3.7-alpine
# 把当前目录拷贝到镜像的 "/code"下
ADD . /code
# 设置工作目录
WORKDIR /code
# 安装软件
RUN pip install -r requirements.txt
# 启动容器的时候执行"python app.py"
CMD [ "python", "app.py"]
