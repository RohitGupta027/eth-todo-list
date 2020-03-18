# Blockchain Based ToDo Application

### 1. Create project 

Initialize the project with truffle using

`truffle init`

To compile the smart contracts

`truffle compile`

To deploy/migrate the smart contracts

`truffle migrate`

If ganache is already running then to replace the contract 

`truffle migrate --reset`

To play with ToDo List in Blockchain 

`truffle console`
`todoList = await TodoList.deployed()`

To retrieve the contract address

`todoList.address`

To retrieve the tasks from the contract

```task = await todoList.tasks(<id>)```</br>
```task```</br>
```task.id```</br>
```task.id.toNumber()```</br>

### 2. Configure Lite server using Browser Sync 
`bs-config.json` 

### 3. Start the server

`npm run dev`