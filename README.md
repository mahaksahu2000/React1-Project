#Nmaste Food
/**
 * Header
 * - Logo
 * - Nav var
 * Body
 * - Serach
 * - RestaurantContainer
 *    - RestaurantCard
 *    - Img
 *    - Name of Res, Star Rating, cuisine, delivery
 * Footer
 *  - Copyright
 *  - Links
 *  - Address
 *  - Contact
 */


 Two types of export/import


 - Default Export/Import

 export default Component;
 import Component from "path";


 - Named Export/Import

 export const component;
 import {component} from "path";


 # React Hooks
 (Normal Js utility funcation)

 - useState() - Superpowerful State Variable in React
                useState is to create a State variable, When you call this useState(); it will gives you statevariable const[]; inside a array. const [] = useState();

 - useEffect() - useEffect will be called, everytime my component render.
 - if no dependancy array => useEffect called on every render
 - if dependency array is empty = [] => useEffect is called on initial render (just one)
 - if dependency array is [btnNameReact] => called everytime btnNameReact is update


 # 2 type Routing in web apps
 - Client side Routing 
 - Server side Routing
 
 # async / await
 async is a keyword that is used to before a function and create a async function
 This async function is always return a promise

 await can only be used inside an async function 

 async and await combo is used to handle promise.

# tailwindcss install
 npm install -D tailwindcss postcss
npx tailwindcss init



# Redux Toolkit
 -  npm install @reduxjs/toolkit
 -  npm i react-redux
 - Built our store
 - Connect our store to our app
 - Slice (cartSlice)
 - dispatch(action)
 - Selector



hover:grid-flow-row

 hover:bg-gray-200





.header {
    display: flex;
    justify-content: space-between;
    border: 1px solid black;
    }
    
    .logo {
        width: 120px;
    }

    .nav-items > ul {
        font-size: 24px;
        display: flex;
        padding: 0px 20px;
        list-style-type: none;
    }
    
    .nav-items > ul > li {
        padding: 10px;
        margin: 10px
    }
    .res-container {
        display: flex;
        flex-wrap: wrap;
        margin: 4px;
    }
    
    .res-card{
        margin: 5px;
        background-color: #f0f0f0;
        width: 200px;
        height: 480px;
        padding: 5px;
       
    }
    .res-card:hover {
        cursor: pointer;
        border: 1px solid black;     
    }
    
    .search{
    
        padding: 10px;
    }

    .search-box {
        margin: 10px;
    }
    

    
    .res-logo{
        width: 190px;
        padding: 5px;
    }

    .filter-btn {
       margin: 10px;
       cursor: pointer;
    }
 

    .shimmer-container {
        display: flex;
        flex-wrap: wrap;
    }



    .shimmer-card {
        margin: 20px;
        padding: 20px;
        width: 200px;
        height: 400px;
        background: #f0f0f0;
    }

    .filter {
        display: flex;
    }

    .user-card {
        border: 1px solid black;
        padding: 10px;
    }

    
