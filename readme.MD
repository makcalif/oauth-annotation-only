How to get JWT token: 

curl authService:authServiceSecret@localhost:8090/oauth/token -dgrant_type=client_credentials -dscope=any
