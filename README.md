# crispy-carnival

leader: Apiag joseph Rhaxemme G.
member: Robert klien brigoli
      : Joshua Ywayan
const express = require('express');
const bodyParser = require('body-parser');
const app = express();
const port = 3000;

app.use(bodyParser.json());

app.listen(port, () =>{
    console.log('Server is running on http://localhost:${port}');
});


const bcrypt = requiere ('bcrypt');
const saltRounds = 10;

app.post('/register',async(req, res))

application.post('/register', async (req, res){
 const { username, password } = req.body;
 
 const hashedPassword = await bcrypt.hash(paswword, saltRounds);
 Connection.query('INSERT INTO users (username, password) VALUES (?,?', [username, hashedPassword], (err, results)=>{


 });
})
