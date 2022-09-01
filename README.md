# diagrama

```mermaid
sequenceDiagram
    usuario->>calculadora:ingresar(num1,num2,etc.)
    usuario->>calculadora:realizar operacion
    loop
        calculadora->>calculadora: validar
    end
    calculadora->>usuario:mostrar resultado
    
    
```
