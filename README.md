### docker-compose template ###

# Services

| Service   | Note |
| :---      | :--- |
| http://localhost:6081/stats | haproxy stats page ( stats:Password123 ) |
| https://localhost:6091 | proxysql01 web interface ( stats:admin ) |
| https://localhost:6092 | proxysql02 web interface ( stats:admin ) |
| http://localhost:8081 | adminer web interface |
| | |
| tcp://localhost:3306 | haproxy -> proxysql cluster |
| | |
| tcp://localhost:6032 | proxysql01 admin interface |
| tcp://localhost:6033 | proxysql02 admin interface |
| | |
| tcp://localhost:3307 | db01 mysql |
| tcp://localhost:3308 | db02 mysql |
| tcp://localhost:3309 | db03 mysql |
