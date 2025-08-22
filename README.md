 # Test Mermaid trên GitHub 
## Biểu đồ đầu tiên của tôi 
```mermaid 
classDiagram 
    class User { 
        -String id 
        -String email 
        +login() 
        +logout() 
    } 
    class Admin { 
        -String role 
        +deleteUser() 
    } 
    User <|-- Admin : Kế thừa
```
