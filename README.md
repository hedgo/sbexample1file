# sbexample1file

[SpringBoot 1.5.9]

Szybki przyklad zainspirowany przez wideo Josh Longa na glownej stronie spring.io https://youtu.be/8RPdOmKtur0
W jednej klasie jest: rest, repo jpa, sprign security. 5 minut i dziala....

http://127.0.0.1:8080/customers
[{"id":1,"name":"Jane"},{"id":2,"name":"Onsi"},{"id":3,"name":"Dave"},{"id":4,"name":"Mia"}]

http://127.0.0.1:8080/trace
[...]

http://127.0.0.1:8080/health
{"status":"UP","customerHealthIndication":{"status":"I <3 Production!"},"diskSpace":{"status":"UP","total":498361954304,"free":335319601152,"threshold":10485760},"db":{"status":"UP","database":"H2","hello":1}}
