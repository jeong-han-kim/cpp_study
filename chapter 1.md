# 1장

### C++전처리기와 ios stream

#include 는 전처리 지시자를 의미한다. 이는 소스코드에 텍스트를 추가하거나 텍스트를 대체하는 것이 전처리기가 수행하는 기본적인 역할이다.

iostream이란 i는 입력, o는 출력을 나타낸다. C++의 몇가지 입출력 기능이 정의되어있다. 

### 헤더파일

헤더파일 C에서는 헤더파일을 .h를 붙여 사용했으나, C++은 이 규칙을 따르지 않아 사용한다. 그래서 iostream과 같이 사용된다. 

#### using namespace std

쉽게 말하면 std는 한 namespace(이름공간)를 의미한다. 

ex)

micorfolp :: wanda

piscine :: wanda 

이 두가지와 namespace안에 wanda라는 것이 들어가있다.

이 때문에 iostream안에 정의 되어있는 cout이라는 변수가 실제로 std::cout으로 호출된다.

그러나 매번하는 것은 번거롭기 때문에 using namespace std;를 사용하여, 우리는 std라는 namespace를 사용한것을 선언해준다. 

그렇기에 iostream에 들어있는 다른이름들을 사용하기 위해서는 using 리스트에 개별적으로 추가해야한다. 

### cout, cin

- cout은 뒤에 나오는 연산자 << 를 사용하여 여러 문자열을 받아 출력한다.  
- << 에서 화살표의 방향은 정보의 흐름을 상징한다. 
- cin은 뒤에 나오는 연산자 >> 를 사용하여 외부에서 받아온 데이터를 변수에 저장해준다. 