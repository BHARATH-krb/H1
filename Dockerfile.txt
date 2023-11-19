FROM ubuntu
COPY . .
RUN apt update
RUN apt install python
CMD ["python", "abc.py"]