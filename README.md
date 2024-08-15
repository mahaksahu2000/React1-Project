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

    .user-card {
        border: 1px solid black;
        padding: 10px;
    }

    
