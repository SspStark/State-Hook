# State Hook

- State Hook
  - Adding Multiple State variables
- Initializing State
  - Object as a Value
  - Array as a Value
- Updating State
  - Using Callback function

## Declaring Multiple state variables
We can declare multiple state variables by calling useState multiple times.
- `const [var1, setVar1] = useState(initialValue)`
- `const [var2, setVar2] = useState(initialValue)`
- `const [var3, setVar3] = useState(initialValue)`

## Initializing State
Syntax: `const [currentState, setterFun] = useState(initialValue)`
The initial value provided to the useState() can be of any data type.

## Providing Object as an initial value
As a best practice, we can provide Object as an initial value when we want to store values that tend to change together.
- `const [comment, setComment] = useState({ name: "", commentText: "" })`

## Providing Array as an initial value
We can provide the array as an initial value to **useState()**.
- `const [commentsList, setCommentsList] = useState([])`
