<h3 align="center">
    <a href="https://github.com/tareqhassan2014/express-ts-ecommerce-app">
       Express Typescript E-Commerce Application
    </a>
</h3>

# Typescript Server Skeleton

### 1) Initialize a git repository

```ch
git init
```

### 2) Initialize node

```ch
npm init -y
```

### 3) initialize typescript

```ch
npx tsc --init
```

### 4) Make directories

```ch
mkdir src src/library src/middleware src/resources src/resources/auth src/resources/product src/utility
```

### 5) Make files

```ch
touch .gitignore types.d.ts .env .env.example src/app.ts src/service.ts src/library/jwt.ts src/middleware/error.ts src/resources/ src/resources/auth/auth.model.ts src/resources/auth/auth.controller.ts src/resources/auth/auth.service.ts src/resources/product/product.model.ts src/resources/product/product.controller.ts src/resources/product/product.service.ts src/utility/responseGenerator.ts
```

### 6) Add dependance

```ch
yarn add express dotenv mongoose helmet morgan cors compression  jsonwebtoken bcrypt
```

### 7) Add dev dependence

```ch
yarn add -D typescript nodemon ts-node @types/express @types/node @types/dotenv @types/compression @types/cors @types/morgan @types/helmet @types/jsonwebtoken @types/bcrypt
```

### 8) Alternate all in all command

```ch
git init
npm init -y
mkdir src src/library src/middleware src/resources src/resources/auth src/resources/product src/utility
npx tsc --init
touch .gitignore types.d.ts .env .env.example src/app.ts src/service.ts src/library/jwt.ts src/middleware/error.ts src/resources/ src/resources/auth/auth.model.ts src/resources/auth/auth.controller.ts src/resources/auth/auth.service.ts src/resources/product/product.model.ts src/resources/product/product.controller.ts src/resources/product/product.service.ts src/utility/responseGenerator.ts
yarn add express dotenv mongoose helmet morgan cors compression  jsonwebtoken bcrypt
yarn add -D typescript nodemon ts-node @types/express @types/node @types/dotenv @types/compression @types/cors @types/morgan @types/helmet @types/jsonwebtoken @types/bcrypt
git init
```


### Core Packages

You need to install the below Packages:

-   express
-   typescript
-   mongoose
-   jsonwebtoken
-   bcrypt
-   and some small packages ....................

### 1. Run the script on your project terminal

```sh
git init
npm init -y
touch .gitignore
tsc --init
yarn add express dotenv mongoose helmet morgan cors compression envalid joi jsonwebtoken bcrypt
yarn add -D typescript nodemon ts-node @types/express @types/node @types/dotenv @types/compression @types/cors @types/morgan @types/helmet @types/jsonwebtoken @types/bcrypt

```

### 2. Script

```json

 "scripts": {
        "start": "node build/server.js",
        "debug": "ndb build/server.js",
        "build": "tsc",
        "dev": "nodemon src/server.ts",
        "postinstall": "npm run build"
    },

```

### 3. Edit tsconfig.json

edit `tsconfig.json` file in the project root and enter the below contents:

```json
{
    "compilerOptions": {
        "target": "ESNext",
        "module": "Commonjs",
        "rootDir": "./src",
        "moduleResolution": "node",
        "outDir": "./build",
        "esModuleInterop": true,
        "forceConsistentCasingInFileNames": true,
        "strict": true,
        "skipLibCheck": true
    }
}
```


