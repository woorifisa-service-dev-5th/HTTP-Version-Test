# HTTP-Version-Test
HTTP 버전 별 차이점을 비교해보는 레포지토리

## 사용법
1. git clone https://github.com/HTTP-LAB/HTTP-Version-Test.git
2. cd docker
3. Docker 설치
4. Docker-Compose 설치
5. `sudo docker-compose -f docker-compose.yml up --buld -d` 실행

## URL
### HTTP/1.1
- 기본 페이지 : https://www.httplab.shop:10443/default-template/index.html
- 최적회된 페이지 : https://www.httplab.shop:10443/optimization-http1/index.html
### HTTP/2/0
- 기본 페이지 : https://www.httplab.shop:20443/default-template/index.html
- 최적화된 페이지 : https://www.httplab.shop:20443/optimization-http2/index.html
### HTTP/3.0
- 기본 페이지 : https://www.httplab.shop:30443/default-template/index.html
- 최적화된 페이지 : https://www.httplab.shop:30443/optimization-http2/index.html
