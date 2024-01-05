# Saludos en Go
Este paquete proporciona una fomra simple de obtener saludos personalizados en Go.

## Instalación
Ejecuta el siguiente comando para instalar el paquete:
```bash
go get -u github.com/Srianv/greetings
```

## Uso
Aqui tienes un ejemplo de cómo utilizar el paquete en tu código:

```go
package main

import (
	"fmt"

	"github.com/Srianv/greetings"
)

func main() {
	messages, err := greetings.Hello("Juan")

	if err != nil {
		fmt.Println("Ocurrio un error:", err)
	}

	fmt.Println(messages)
}
```
