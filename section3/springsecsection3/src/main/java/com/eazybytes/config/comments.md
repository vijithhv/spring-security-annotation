this one is to create a list of login credentials in memeory

34  we are creating user with name user and a password and then an authority lets call it role or permission of read       {noop} means i dont want any password encoders

35  we are creating user with name admin and a password and then an authority lets call it role or permission of admin/write

36

37

38  we are passing the users created to it.. we can pass any number of users liek 5 10 etc





43   PasswordEncoderFactories class has a createDelegationPasswordEncoder class   =>   this class uses the springframework decided standard password encoder (currently Bcrypt) in the future is spring team changes to a more powerful password encoder that will be used    


51   we are creating a bean that returns an object of Comnpromized password checker

52   have i been pawned (remember the website)     throws error for 12345 or password and other weak passwords
