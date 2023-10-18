# PIZZA API

### ERD:

![drawSQL-pizza](https://github.com/axel-ac/pizzaAPI/assets/102467587/b2fcbd8d-947f-437d-8dbf-f5a5004764f9)

### Folder/File Structure:

```
    .env
    .gitignore
    index.js
    readme.md
    logs/
    src/
        configs/
            dbConnection.js
        controllers/
            auth.js
            pizza.js
            order.js
            topping.js
            user.js
        helpers/
            passwordEncrypt.js
            setToken.js
            sync.js
        middlewares/
            authentication.js
            errorHandler.js
            findSearchSortPage.js
            logger.js
            permissions.js
        models/
            pizza.js
            order.js
            topping.js
            user.js
        routes/
            auth.js
            pizza.js
            order.js
            topping.js
            user.js
```
