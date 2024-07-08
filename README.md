# build

## mvn clean install -pl w-api -am -DskipTests

## core 모듈은 무시해 주시고 g-api, pingback, w-api 만 봐주시면 됩니다.
## 위의 3개 프로젝트는 웹서버가 동작하게 됩니다. (8080)
### 서버가 구동되면 http://localhost:8080/ 에서 확인이 가능합니다. 


### 최상위 디렉토리에서 빌드시 위의 예제처럼 -pl, -am 옵션을 추가해 주시면 됩니다.
### -DskipTests 옵션은 테스트를 스킵하고 빌드하는 옵션입니다.


