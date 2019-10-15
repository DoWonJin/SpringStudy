Portable Service Abstraction

잘 만들어진 인터페이스를 이용해 코드를 만들면 유지보수하기 편리함.

Spring에서 제공하는 API 대부분(90%)이 PSA이다.


Spring Doc.
Core: Events(퍼블리싱, subscribe), Resource(파일시스템, 클래스path, http),i18n(메세지를 localized된 메세지로 바꿀 것인가)
    ,Balidation, Data Binding, Type Conversion, SpEL(추상화라하기 애매함)
Data: Transaction, DAO support, JDBC(low레벨로 사용하지 않기 때문),ORM, Marshalling XML.

