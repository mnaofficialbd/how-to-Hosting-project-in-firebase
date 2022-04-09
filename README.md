## Steps of solving ReactDOM.render warning.
## step: 1 
### Go to project (index.js) file.
## step: 2 (Replace) 
- import ReactDOM from 'react-dom'; 
### ==> import {createRoot} from "react-dom/client"

## step: 3 (Replace)
- ReactDOM.render(
  <React.StrictMode>
    <App />
  </React.StrictMode>,
  document.getElementById('root')
);
# ==>
- const container=document.getElementById('root');
- const root=createRoot(container);
- root.render(<React.StrictMode>
-  App 
- </React.StrictMode>);