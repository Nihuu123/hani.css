
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background: #f4f4f9;
  color: #333;
}

header {
  background: #4CAF50;
  padding: 15px 0;
  position: sticky;
  top: 0;
  z-index: 100;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  max-width: 1100px;
  margin: auto;
  padding: 0 20px;
}

.logo {
  color: white;
}

.nav-links {
  list-style: none;
  display: flex;
}

.nav-links li {
  margin: 0 15px;
}

.nav-links a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.nav-links a:hover {
  text-decoration: underline;
}

.hero {
  background: linear-gradient(to right, #4CAF50, #2e7d32);
  color: white;
  text-align: center;
  padding: 100px 20px;
}

.hero h2 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.btn {
  display: inline-block;
  background: white;
  color: #4CAF50;
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
  font-weight: bold;
}

.btn:hover {
  background: #f4f4f9;
}

.section {
  max-width: 900px;
  margin: auto;
  padding: 50px 20px;
  text-align: center;
}

.section h2 {
  color: #4CAF50;
  margin-bottom: 20px;
}

.card {
  background: white;
  padding: 20px;
  margin: 15px 0;
  border-radius: 10px;
  box-shadow: 0px 2px 6px rgba(0,0,0,0.1);
}

.skills {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}

.skills li {
  background: #4CAF50;
  color: white;
  padding: 10px 15px;
  margin: 10px;
  border-radius: 8px;
  list-style: none;
}

form {
  display: flex;
  flex-direction: column;
  align-items: center;
}

form input, form textarea {
  width: 80%;
  padding: 10px;
  margin: 10px 0;
  border: 1px solid #ddd;
  border-radius: 5px;
}

form button {
  cursor: pointer;
}

#formMessage {
  margin-top: 15px;
  font-weight: bold;
  color: green;
}

footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 15px;
}
