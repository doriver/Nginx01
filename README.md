## Nginx에서 설정파일들 변경한거 남기려고
* 로드밸런싱   
upstream블록 + proxy_pass 로 구현      

* 헤더설정   
proxy_set_header 로 구현

* 캐싱   
proxy_cache 설정 , Cache-Control 헤더 설정

* 무중단 배포    
reload명령어
