

* { box-sizing: border-box; }

body {
  margin: 0;
  font-family: Arial, sans-serif;
  background: #f4f7fb;
  color: #222;
}

.container {
  width: min(900px, 92%);
  margin: 40px auto;
  background: white;
  padding: 30px;
  border-radius: 14px;
  box-shadow: 0 8px 30px rgba(0,0,0,.08);
}

h1 { margin-bottom: 5px; }
.subtitle { margin-top: 0; color: #666; }

label {
  display: block;
  margin-top: 20px;
  margin-bottom: 8px;
  font-weight: bold;
}

select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccd3dd;
  border-radius: 8px;
  font-size: 15px;
}

textarea { resize: vertical; }

button {
  margin-top: 18px;
  padding: 12px 24px;
  border: 0;
  border-radius: 8px;
  cursor: pointer;
  font-size: 16px;
}

#status {
  margin-top: 15px;
  font-weight: bold;
}

.result {
  margin-top: 18px;
  padding: 18px;
  background: #f8fafc;
  border-radius: 8px;
  white-space: pre-wrap;
  min-height: 80px;
}

@media (max-width: 600px) {
  .container { padding: 20px; margin: 20px auto; }
}
