# Learning
As a mobile engineer focused in building out pixel-perfect applications, I'd like to get a deeper understanding in the nuances of backend development.
This personal project is meant to get hands-on development in:
- Postgres, SQLC Docker, TablePlus
- Golang
- HTTP JSON API using GIN, JWTs, PASETO
- Deployment to Kubernetes + AWS ECR, RDS 
- gRPC

# simple_bank
The service that I'm building to build is a simple bank. It will provide APIs for the frontend to do following things:
1. Create and manage bank accounts, which are composed of owner’s name, balance, and currency.
2. Record all balance changes to each of the account. So every time some money is added to or subtracted from the account, an account entry record will be created.
3. Perform a money transfer between 2 accounts. This should happen within a transaction, so that either both accounts’ balance are updated successfully or none of them are.
