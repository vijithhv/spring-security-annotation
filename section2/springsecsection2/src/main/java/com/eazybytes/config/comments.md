So if you need to customizes the behaviour of spring security framework you have to declare similar kind of method of type Security filter chain


14 the method defaultSecurityFilterChain is creating a bean of type SecurityFilterChain and is also accepting HttpSecurity as the input

15 every endpoint is accessible

16 no end point is accessible

18 must be authenticated to access these endpoints

19 these endpoints can be accessed by anyone => make sure you add the error page to it

20 form login        =>         username password form

21 how to disable form login

22 how to disable basic login

23 users can send credentials in headers by base 64 encoding it   (used by organization for api invocation not ui)    Basic e68yu234wko729j23p376tyyuiu
