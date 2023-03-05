# todo

- ## Frameworks and Language used
  - #### Spring Boot Framework
  - #### Java language
- ## Data Flow
  - ### TodoController
     - ##### _addTodo( )_   
     - ##### _findTodoById( )_
     - ##### _findAllTodos( )_   
     - ##### _updateTodo( )_  
     - ##### _deleteTodo( )_
    
    
  - ### TodoService
     - ##### _findAll( )_      
     - ##### _findById( )_      
     - ##### _addTodo( )_     
     - ##### _deleteTodo( )_    
     - ##### _updateTodo( )_
  
    
   - ### TodoRepository
     - ##### _findAll( )_   
     - ##### _findById( )_    
     - ##### _save( )_     
     - ##### _deleteById( )_   
    
     
- ## Database Used
  - #### H2 Console :  tododb
  
- ## Project Summary
  In this project we have created a model namely; Todo. We have provided some endpoints and also in this section below we have given our API. Using this API we can perform the CRUD operations accordingly.
  
  
  > http://localhost:8080/api/v1/todo-app
  
  End Points:
    - ##### /add-todo
    
    - ##### /find-todo/id/{id}

    - ##### /find-all 

    - ##### /update-todo/id/{id}  
    
    - ##### /delete-todo/id/{id} 
