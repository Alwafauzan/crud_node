# crud_node
## instalasi
- node
1. link "https://nodejs.org/en/download/package-manager"
2. install seperti biasa, jangan lupa path
3. cek di cmd `node -v` dan `npm -v`
- package
1. ketik di cmd "npm init -y"
2. buat script `"type": "module",` di file package.json untuk akses es6  
- nodemon
1. ketik `npm install -g nodemon` di cmd untuk menginstall nodemon 
- library
1. ketik `npm install express mysql2 sequelize cors` di cmd untuk menginstall library
- kode package.json
```json
{
  "name": "backend",
  "version": "1.0.0",
  "main": "index.js",
  "type": "module",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "keywords": [],
  "author": "",
  "license": "ISC",
  "description": "",
  "dependencies": {
    "cors": "^2.8.5",
    "express": "^4.19.2",
    "mysql2": "^3.10.2",
    "sequelize": "^6.37.3"
  }
}
```
