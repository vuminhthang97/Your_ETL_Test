FROM python:3.9.1

# cài đặt thư viện
RUN pip install pandas

# thư mục làm việc
WORKDIR /app

# copy file từ local vào thư mục trong docker
COPY pipeline.py pipeline.py

# các biến khi chạy file docker
ENTRYPOINT [ "python", "pipeline.py" ]