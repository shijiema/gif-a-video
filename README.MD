# My Spring Boot learning project
A service that
* accepts video upload
* make a animation gif for a time range in video

# Often used commands in development
## using curl before having an UI
* curl -F -file=@f.mp4 -F start=0 -F end=10 -F speed=1 -F repeat=0 localhost:8080/upload

# Miscellaneous

* use spring-boot-devtools to enable web server to automatically pick up new changes

