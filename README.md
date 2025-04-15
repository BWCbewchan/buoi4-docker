# Bài Tập Docker

## Thông tin
- Môn học: Kiến trúc và Thiết kế phần mềm
- Lớp: [DHKTPM17CTT]
- Sinh viên: [Trần Chí Bảo]
- MSSV: [21080741]

## Nội dung bài tập
Bài tập gồm 2 phần chính:

### Phần 1: Các lệnh cơ bản thao tác với Docker
Tổng hợp các lệnh Docker cơ bản và kết quả thực thi:

```bash
# 1. Kiểm tra phiên bản Docker
docker --version

# 2. Chạy container hello-world
docker run hello-world

# 3. Tải image nginx
docker pull nginx

# 4. Liệt kê các images
docker images

# 5. Chạy nginx container
docker run -d nginx

# ... các lệnh khác
```

## Minh chứng thực hiện

### Phần 1: Các lệnh Docker cơ bản

#### Kiểm tra cài đặt Docker
![Docker Version](minhchung/docker-version.png)

#### Chạy container Hello World
![Hello World](minhchung/hello-world.png)

#### Quản lý Images và Containers
![Docker Images](minhchung/docker-images.png)
![Docker PS](minhchung/docker-ps.png)

### Phần 2: Thực hành với Dockerfile

#### Bài 1: Node.js Application
![Node.js Build](minhchung/nodejs-build.png)
![Node.js Running](minhchung/nodejs-running.png)

#### Bài 2: Python Flask Application
![Flask Build](minhchung/flask-build.png)
![Flask Running](minhchung/flask-running.png)

#### Bài 3: React Application
![React Build](minhchung/react-build.png)
![React Running](minhchung/react-running.png)

#### Bài 4: Static Website với Nginx
![Nginx Build](minhchung/nginx-build.png)
![Nginx Running](minhchung/nginx-running.png)

#### Bài 5: Go Application
![Go Build](minhchung/go-build.png)
![Go Running](minhchung/go-running.png)

#### Bài 6: Multi-stage Build
![Multi-stage Build](minhchung/multistage-build.png)
![Multi-stage Running](minhchung/multistage-running.png)

#### Bài 7: Environment Variables
![Env Build](minhchung/env-build.png)
![Env Running](minhchung/env-running.png)

#### Bài 8: PostgreSQL
![PostgreSQL Build](minhchung/postgres-build.png)
![PostgreSQL Running](minhchung/postgres-running.png)

#### Bài 9: Redis
![Redis Build](minhchung/redis-build.png)
![Redis Running](minhchung/redis-running.png)

#### Bài 10: PHP với Apache
![PHP Build](minhchung/php-build.png)
![PHP Running](minhchung/php-running.png)