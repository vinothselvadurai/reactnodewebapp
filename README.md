# HOW TO CREATE REACT APP FROM SCRATCH WITHOUT npx create-react-app
1. $ npm init -> give app name and proceed with enter button
2. create public/index.html with following code
<!-- <html>
    <head>
        My First React App
    </head>
    <body>
        <div id="app"> </div>
    </body>
</html> -->

3.create src/index.js with following code
import ReactDOM from 'react-dom'
import React from 'react'

<!-- const App = () => {
    return <h1>Entering the React World!!!</h1>
}
 -->
ReactDOM.render(<App/>, document.getElementById('app'))
4.npm install react-dom react react-scripts
5 in Package.json under scripts add this line  "start": "react-scripts start"
6 npm start
7 now hit the browser with **localhost:3000**


Javascript Engine Architecture


<img width="756" alt="Screenshot 2022-05-14 at 7 51 23 PM" src="https://user-images.githubusercontent.com/71251375/168429878-456842bf-7e63-4291-83eb-651c16188e51.png">



<img width="626" alt="Screenshot 2022-05-14 at 7 55 27 PM" src="https://user-images.githubusercontent.com/71251375/168429917-a41b23bc-6931-4036-af68-14410b67c610.png">


<img width="655" alt="Screenshot 2022-05-14 at 7 55 57 PM" src="https://user-images.githubusercontent.com/71251375/168429941-eaec41cb-d769-41fb-b20c-641e9e02fdec.png">



