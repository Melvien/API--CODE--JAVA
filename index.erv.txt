import express from "express";
import bodyParser from "body-parser";

import routes from "./routes/uswer.js";
const app = express();
const PORT= 8000;

app.use(bodyParser.json());

app.get("/", (req, res) =>{
     res.send ("Hello World");
});

app.listen(PORT, () => console.log ("Server is running"));