# HOW TO CREATE REACT APP FROM SCRATCH WITHOUT npx create-react-app
1. $ npm init -> give app name and proceed with enter button
2. create public/index.html with following code
<html>
    <head>
        My First React App
    </head>
    <body>
        <div id="app"> </div>
    </body>
</html>

3.create src/index.js with following code
import ReactDOM from 'react-dom'
import React from 'react'

const App = () => {
    return <h1>Entering the React World!!!</h1>
}

ReactDOM.render(<App/>, document.getElementById('app'))
4.npm install react-dom react react-scripts
5 in Package.json under scripts add this line  "start": "react-scripts start"
6 npm start
7 now hit the browser with **localhost:3000**


