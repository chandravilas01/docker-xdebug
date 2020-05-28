# docker-xdebug
docker xdebug image

### steps
1. vi /etc/hosts
  ```
  127.0.0.1 www.chandravilas-demp-xdebug.com
  ```
2. cd docker-xdebug
3. docker-compose build && docker-compose up -d
4. docker-compose up -d
5. docker-compose ps
6. using PHPStorm to open 'docker-for-mac-with-PhpStorm-xdebug' project
7. click index.php
8. set a breakpoint in the source code
9. start listening for PHP debug connections
10. open your browser, with link 'www.chandravilas-demp-xdebug.com'