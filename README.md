# SpringBoot-SpringDataJPA-CRUD-REST-API

Reference link: https://spring.io/guides/tutorials/rest/

Steps to Run Application
------------------------

1. Open Git Bash
2. git clone https://github.com/ajaynirankari/SpringBoot-SpringDataJPA-CRUD-REST-API.git
3. cd SpringBoot-SpringDataJPA-CRUD-REST-API/
4. ./mvnw clean spring-boot:run
            
             
Steps to Test Application
-------------------------
1. Open Git Bash
2. curl -v http://localhost:8080/empoyees | jq


Verify Response
---------------
*   Trying 127.0.0.1:8080...
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
  0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0* Connected to localhost (127.0.0.1) port 8080 (#0)
> GET /empoyees HTTP/1.1
> Host: localhost:8080
> User-Agent: curl/7.78.0
> Accept: */*
>
* Mark bundle as not supporting multiuse
< HTTP/1.1 200
< Content-Type: application/json
< Transfer-Encoding: chunked
< Date: Tue, 07 Nov 2023 07:25:29 GMT
<
{ [192 bytes data]
100   186    0   186    0     0  29717      0 --:--:-- --:--:-- --:--:-- 37200
* Connection #0 to host localhost left intact
[
  {
    "id": 1,
    "name": "Smith",
    "role": "Dev"
  },
  {
    "id": 2,
    "name": "Marry",
    "role": "IT"
  },
  {
    "id": 3,
    "name": "Paul",
    "role": "Tested"
  },
  {
    "id": 4,
    "name": "Zim",
    "role": "Doc"
  },
  {
    "id": 5,
    "name": "Kenith",
    "role": "Dev"
  }
]

             
