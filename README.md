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
<img width="918" height="397" alt="Screenshot 2026-11-13 005033" src="https://github.com/user-attachments/assets/dc7bb80b-40eb-4fe5-8ba8-12807eb47c2a" />
<img width="883" height="194" alt="Screenshot 2026-11-13 005051" src="https://github.com/user-attachments/assets/f0514142-d5cb-4b9b-9875-e73ba194f8bb" />


## RESULT
### The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.
