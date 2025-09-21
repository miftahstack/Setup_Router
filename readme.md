<!-- Process of React Router DOM -->

<!-- Step 01 -->
npm i react-router

##Open in the terminal
<!-- Step 01 -->

<!-- Step 02 -->
Import this "BrowserRouter" to <main.js> file and wrap the app between BrowserRouter:

import { BrowserRouter } from "react-router"; 

  <BrowserRouter>
    <App />
  </BrowserRouter>

##Remember the BrowerRouter under the root.render-
<!-- Step 02 -->

<!-- Step 03 -->
Simply import Routes etc to <app.jsx> file and create Routes:

import { Routes, Route } from "react-router";

    <Routes>
      <Route path="/" element={<Page 01 />} /> 
      <Route path="/" element={<Page 02 />} /> 
    </Routes>

##Add pages/section on the element-prop and import the file.
<!-- Step 03 -->
