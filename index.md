kode awal index.js
```js
import express from "express";
import cors from "cors";

const app = express();
app.use(cors());
app.use(express.json());
app.listen(5000,()=>console.log("SERVER UP"));
```

jalankan dengan cmd dengan mengetikan
```console
nodemon index
```
