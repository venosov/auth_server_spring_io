http://localhost:8080/oauth2/authorize?response_type=code&client_id=client&scope=openid&redirect_uri=http://spring.io/auth

curl --location --request POST 'http://localhost:8080/oauth2/token?client_id=client&redirect_uri=http://spring.io/auth&grant_type=authorization_code&code=vYt8LROL76GgmymKbUUUPYITf3rEo0SgZUnebJK5o38HVdYbVzFxTTZ0wPa7EMJYbOJzXLbU2Qp-9QL_ktB6PNUU7Vwj3m4fIeWJhuMao4Qv85jB6H7fijpcookS9Ik7' \
--header 'Authorization: Basic Y2xpZW50OnNlY3JldA=='
