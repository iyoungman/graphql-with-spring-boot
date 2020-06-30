## REST vs GraphQL
* GraphQL
    * Client 측에서 필요한 정보를 가져올 수 있다.
    * 장점
        * HTTP 요청 횟수를 줄일 수 있다.
        * HTTP 응답 Size를 줄일 수 있다.
     * 단점
        * File 전송등 Text 이외의 처리는 복잡하다.
        * 고정된 요청과 응답만 필요할 경우 Query로 인해 요청 크기가 Restful보다 커진다.
        
* 언제 사용할까?
    * GraphQL
        * 다양한 요청과 응답이 필요할 때
        * CRUD 요청
    * RESTful
        * 고정된 요청과 응답이 필요할 때
        * 파일 전송과 같은 
        
***

## 용어
* Query : 읽기작업을 하는 GraphQL문
    * GraphQLQueryResolver
    
* Mutation : 데이터 수정작업을 하는 GraphQL문
    * GraphQLMutationResolver
    
***
    
## 화면
![image](https://user-images.githubusercontent.com/25604495/86092290-43bf2200-bae8-11ea-8e26-9f3f1795e76d.png)

***

## Reference
* https://dzone.com/articles/a-beginners-guide-to-graphql-with-spring-boot
* https://www.holaxprogramming.com/2018/01/20/graphql-vs-restful-api/
* https://vomvoru.github.io/blog/about-GraphQL/
