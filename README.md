# React Lab Exercise 3: State in React
## Name: Anwarsha E.M
## Roll no: 2305001002
## Department: CSE

## AIM
### To create a simple React application that demonstrates the use of State using the useState() Hook. 

## PROGRAM
### App.jsx 
```py
import { useState } from "react"; function App() { const [name, setName] = useState("Aravindan T"); const [newName, setNewName] = useState(""); 
return ( 
<div> 
<h1>Student Name Example</h1> 
<h2>Student Name: {name}</h2> 
<input type="text" placeholder="Enter new name" value={newName} 
onChange={(e) => setNewName(e.target.value)} 
/> 
<button onClick={() => setName(newName)}> 
Change Name 
</button> 
</div> 
);
}
export default App;

```
## OUTPUT
<img width="1125" height="442" alt="image" src="https://github.com/user-attachments/assets/521233d5-10ec-47c8-9d34-a764ea956719" />
<img width="1125" height="437" alt="image" src="https://github.com/user-attachments/assets/ddde35b7-623b-4be5-9284-dfd2c99bff5d" />

## RESULT
### The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.
