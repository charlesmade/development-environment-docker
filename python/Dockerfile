FROM python:3.7.1-stretch

WORKDIR /usr/src/app

COPY requirements.txt ./
RUN pip install -i https://pypi.tuna.tsinghua.edu.cn/simple --no-cache-dir -r requirements.txt

COPY . .

CMD [ "python3", "server.py" ]