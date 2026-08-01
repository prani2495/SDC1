const express = require('express');
const path = require('path');
const bodyParser = require('body-parser');
const app = express();
const PORT = 3000;
app.use(bodyParser.urlencoded({ extended: true }));
app.get('/', (req, res) => {
res.sendFile(path.join(__dirname, 'index.html'));
});
app.post('/register', (req, res) => {
const { name, email, phone } = req.body;
console.log(`Registered: ${name}, ${email}, ${phone}`);
res.send(`<h2>Thanks for registering, ${name}!</h2><p>We'll contact you at
${email}.</p>`);
});
app.listen(PORT, () => {
console.log(`Server running on http://localhost:${PORT}`);
});
