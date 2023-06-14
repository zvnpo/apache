# jackrabbit

: JCR 구현    



**JCR (java content repository)**  
: 레파지토리에 저장된 컨텐츠에 접근하기 위한 자바 인터페이스  
: 데이터 저장/수정/삭제/검색을 위한 인터페이스 제공  

레파지토리 = 파일 시스템, 관계형 데이터베이스, xml 문서 등  
컨텐츠 = 계층 구조로 저장된 데이터, 웹 컨텐츠    



```xml
    <dependency> 
        <groupId>javax.jcr</groupId> 
        <artifactId>jcr</artifactId> 
        <version>2.0</version> 
    </dependency> 

    <dependency> 
        <groupId>org.apache.jackrabbit</groupId> 
        <artifactId>jackrabbit-core</artifactId> 
        <version>2.12.1</version>
    </dependency> 
```