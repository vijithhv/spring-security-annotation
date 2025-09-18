So if you need to customizes the behaviour of spring security framework you have to declare similar kind of method of type Security filter chain


14 the method defaultSecurityFilterChain is creating a bean of type SecurityFilterChain and is also accepting HttpSecurity as the input

15 every endpoint is accessible

16 no end point is accessible

18 must be authenticated to access these endpoints

19 then endpoints can be accessed by anyone

20 form login

21 users can send credentials in headers by base 64 encoding

22

  <img width="1341" height="752" alt="image" src="https://github.com/user-attachments/assets/84f5b654-2ce6-4c94-8b4e-3309eda60fe2" />

