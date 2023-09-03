# Saludos en Go

Este paquete proporciona una forma de obtener saludos personalizados en Go.

## instalacion
Ejecuta el siguiente comando para instalar el pquete:
```bash
go get -u github.com/Heinzsosa/greetings
```

## Uso
Aquí un ejemplo de como utilizar el paquete en tu código

```go
package main

import (
    "fmt"
    "github.com/Heinzsosa/greetings"
)

func main(){
    message, err := greetings.Hello("Alex")

    if err != nil{
        fmt.Println("Ocurrio un error: ", err)
        return
    }

    fmt.Println(message)
}

```
Este ejmplo importa el paquete github.com/Heinzsosa/greetings y llama a la funcion Hello()
saludo personalizado. Si ocurre un error, se imprime un mensaje de error.
