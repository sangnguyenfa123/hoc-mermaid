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
5 / 14
buoi 03 mermaid-guide.md
    User <|-- Admin : Kế thừa
```
