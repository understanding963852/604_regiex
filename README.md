# 정규표현식
# /regiex/  ==> Regular expression의 약자

# 언제 사용하는가?
 - 텍스트에서 우리가 원하는 특정한 패턴을 찾을때 (전화번호형태의 패턴, 웹사이트주소형태의 패턴,이메일형식의 패턴을 찾을때 등등)
 - 사용자가 입력한 텍스트가 이메일이나 패스워드와 같이 특정한 패턴에 부합하는지 유효성검사흘 할때도 사용할수 있다
 - 정규식은 문자를 검사하고자할때 사용하는 식이다.

# 정규식은 /로 시작하여 "나는 정규표현식"임을 나타낸다
- /우리가 찾고자하는 패턴/

- /regex/i
- i는 어떤 옵션에 따라 검색할건지 플래그를 활용할수 있다.

# 문법
 1) Groups anf ranges
   - |   : 또는
   - ()  : 그룹
   - []  : 문자셋, 괄호안의 어떤 문자든
   - [^] : 부정 문자셋, 괄호안의 어떤 문자가 아닐때
   - (?) : 찾지만 기억하지는 않음 



![image](https://github.com/understanding963852/604_regiex/assets/60366769/2efc7d18-872e-4750-9f08-0f52552bba49)

![image](https://github.com/understanding963852/604_regiex/assets/60366769/aff12b22-5705-4be9-ba39-592336feca70)

# gr로 시작하고 중간글자가  e 또는 a 가 되고  y로 끝나는것을 찾음
![image](https://github.com/understanding963852/604_regiex/assets/60366769/9d54dcca-ffcd-4356-89f1-c43fc5a24122)




