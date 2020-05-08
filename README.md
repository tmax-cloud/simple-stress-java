# simple-stress-java

## 스레드 부하
http://localhost:8080/activeThread?num=10&sleep=99999
* num : number of threads
* sleep : sleep(millisec) per threads

## CPU 부하(암복호화)
http://localhost:8080/cpu?num=100&loop=1000&target=hellohellohellohello
* num : number of threads
* loop : loop
* target : 암복호화 할 target 문자열

## 스레드 카운트 바로 조회
http://localhost:8080/stat

## 빌드 및 실행방법
프로젝트 루트에서 
gradle jar
java -jar ./build/lib/StressTest.jar

