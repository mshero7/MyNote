특징
HashMap이 가진 삽입/삭제/조회를 빠르게하면서 캐쉬 친화적인 특징을 가진 자료구조.
순서는 보장되지 않음. 메모리를 많이 사용함.
Dense와 Sparse 자료구조를 둘다 사용함으로 캐쉬 친화적을 만든다.
ㄴ hashMap 장점(Get, Add, Remove 속도가 빠르다는 장점 O(1)) + sortedMap 장점(Dense한 자료구조) 을 합쳐 캐쉬친화적으로 만들어냈다.


목적



hashMap 장점 + 


단점
메모리를 많이 먹는다
순서가 보장되지 않는다
캐쉬 비친화적이다!!
ㄴ 구멍이 많이 뚫려있는 자료구조라 순회할때 효율적이지가 않다.

Dense하다
ㄴ 배열에 연속적으로 빈구멍없이 쌓인다. 순회 캐쉬 친화적이다.

hashmap