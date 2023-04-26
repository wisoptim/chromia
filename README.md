# Tech assignment
Features of the project
1. Register user
2. Mint token
3. Transfer token
4. Create Collection of tokens
5. Add/remove token, collections to Favorite

Features of Rell used:
1. Splitting the code into modules
2. Entities are widely used
3. Operations and queries are used to interact with the node.

Status:
1. The code is compilable using: `chr build`
2. Tests fail because of the error: `No database connection`. The command `chr test` is used.
3. Test starts with this command `docker-compose -f docker_compose_test.yml up --abort-on-container-exit --exit-code-from postchain`

