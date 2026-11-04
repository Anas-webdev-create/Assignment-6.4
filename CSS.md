* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Arial, sans-serif;
  color: #243247;
  background: #f3f6fa;
}

.hero {
  padding: 48px 20px;
  text-align: center;
  color: white;
  background: #315f91;
}

.hero h1 {
  margin: 0 0 8px;
}

.hero p {
  margin: 0;
}

.navbar {
  position: sticky;
  top: 0;
  z-index: 10;
  display: flex;
  justify-content: center;
  gap: 28px;
  padding: 15px;
  background: #203b59;
}

.navbar a {
  color: white;
  font-weight: bold;
  text-decoration: none;
}

.navbar a:hover {
  text-decoration: underline;
}

.section {
  min-height: 430px;
  padding: 56px 24px;
  text-align: center;
}

.section:nth-child(even) {
  background: white;
}

.card {
  position: relative;
  max-width: 360px;
  margin: 30px auto;
  padding: 34px 24px 24px;
  border: 2px solid #b9c9d9;
  border-radius: 12px;
  background: #fff;
  box-shadow: 0 8px 20px #203b5918;
  text-align: left;
}

.badge {
  position: absolute;
  top: -12px;
  right: 18px;
  z-index: 2;
  padding: 6px 12px;
  border-radius: 20px;
  color: white;
  background: #d45b42;
  font-size: 0.8rem;
  font-weight: bold;
}

.help-button {
  position: fixed;
  right: 24px;
  bottom: 24px;
  z-index: 20;
  padding: 14px 22px;
  border-radius: 30px;
  color: white;
  background: #d45b42;
  box-shadow: 0 4px 12px #0003;
  font-weight: bold;
  text-decoration: none;
}

.help-button:hover {
  background: #b9432d;
}

    
11:45