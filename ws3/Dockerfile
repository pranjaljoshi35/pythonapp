FROM centos
RUN yum install python3 -y
CMD python3
ADD hello.py /home/hello.py
CMD ["/home/hello.py"]
ENTRYPOINT ["python3"]
