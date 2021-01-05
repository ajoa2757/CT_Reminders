# CT_Reminders
basic strategies for CTs (algorithm &amp; data structures)

주로 자료구조들의 메서드에 대한 정리

vector<> : linear 배열 "삽입과 삭제가 불리", 선입후출
vector<> v(n) : n개 공간 할당, 기본값 NULL
vector<> v(n,m) : n개 공간에 m을 넣어서 할당
vector<> v1(v2) : v2를 카피한 v1 생성 

v.back() : 마지막 원소
v.front() : v[0]

v.push_back(a) : a를 맨 뒤에 삽입.
v.pop_back() : 맨 뒤 원소를 제거. 



quque : 선입선출 방식. 

Q.push(n) : n을 맨 뒤에 입력
Q.pop() : 맨 뒤 원소를 제거.
생성자는 vector와 동일

priority queue : 우선순위가 존재하는 큐. 선언시에 자료형과 함께 비교함수를 템플릿 괄호 안에 넣을 수 있다.

priority_queue<T,vector<T>,compare> Q : 기본형 생성자이다. T,vector<T>를 기본적으로 건네준다.
 
 
compare 함수는 operator() 를 재정의 하여 사용자가 원하는 비교 결과에 따라 true/false 를 반환하는 함수의 양식을 갖추어 작성해야 한다.
실사용에 대해 공부가 필요함. 


이 비교함수의 논리대로 큐가 정렬되는데, 이때 거리는 시간은 log n 이며, 비교함수를 사용자가 직접 만들어 원하는대로 정렬할 수 있다. 
우선순위의 기본값은 내림차순.









