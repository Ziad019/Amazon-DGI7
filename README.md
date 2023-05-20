npx create-react-app amplifyapp
cd amplifyapp
npm start
git init
git add .
git commit -m "initial commit"
git remote add origin git@github.com:username/reponame.git
git branch -M main
git push -u origin main
import React from 'react';
import logo from './logo.svg';
import './App.css';


unction App() {
  return (
    <div className="App">
      <header className="App-header">
        <img src={logo} className="App-logo" alt="logo" />
        <h1>Hello from V2</h1>
      </header>
    </div>
  );
}

export default App;
git add .
git commit -m “changes for v2”
git push origin main
