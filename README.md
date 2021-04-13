# To start

## Start Docker with postgre DB
docker run -d --name express-db -p 5432:5432 -e 'POSTGRES_PASSWORD=1234' postgres
npm run initdb

### To start with development
```
npm run dev
npm start 
```

### production
```
npm install
npm run build
```

To access on development server go to: http://0.0.0.0:8080/

### Note
You may need to register a okta account for the authentication process