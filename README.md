# diagrama

```mermaid
sequenceDiagram
    usuario->>calculadora:ingresar(num1,num2,etc.)
    usuario->>calculadora:realizar operacion
    loop Healthcheck
        calculadora->>calculadora: validacior
    end
    calculadora->>usuario:mostrar resultado
    
    
```
