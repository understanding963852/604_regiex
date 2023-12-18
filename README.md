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
   - (?:) : 찾지만 기억하지는 않음 



![image](https://github.com/understanding963852/604_regiex/assets/60366769/2efc7d18-872e-4750-9f08-0f52552bba49)

![image](https://github.com/understanding963852/604_regiex/assets/60366769/aff12b22-5705-4be9-ba39-592336feca70)

# gr로 시작하고 중간글자가  e 또는 a 가 되고  y로 끝나는것을 찾음
![image](https://github.com/understanding963852/604_regiex/assets/60366769/9d54dcca-ffcd-4356-89f1-c43fc5a24122)

# 찾아는 지지만 그룹으로 만들고 싶지 않다면 사용   
![image](https://github.com/understanding963852/604_regiex/assets/60366769/b0330007-df73-4950-b376-e16bb13e9f91)


# gr로 시작하고 a또는 e 또는 d 가 있고 y로 끝남
# [aed]  --> 대괄호안에 있는 글자중 하나라도 만족하는것을 찾아라는 의미 
![image](https://github.com/understanding963852/604_regiex/assets/60366769/f9f241d8-8285-435f-a584-8692f7ff50f4)

![image](https://github.com/understanding963852/604_regiex/assets/60366769/2d28193c-416a-4f1b-a96f-8fc57b7e49d4)


# 아래 두 이미지는 gr로 시작하고 a~g사이의 글자중 하나라도 포함되고 y로 끝나는 것을 찾음
![image](https://github.com/understanding963852/604_regiex/assets/60366769/81b911a6-9879-4a3a-ae04-ed042aba73a9)

![image](https://github.com/understanding963852/604_regiex/assets/60366769/79687923-4c92-4c7d-b7ab-01f7ca06c3ab)




