FROM python:3.6
ADD flaskapp.py /root
RUN pip install jinja2 -i https://mirrors.aliyun.com/pypi/simple
RUN pip install flask -i https://mirrors.aliyun.com/pypi/simple
EXPOSE 8080
CMD ["python","/root/flaskapp.py"]
