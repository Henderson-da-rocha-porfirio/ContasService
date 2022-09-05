# @ComponentScan - usado no main.
## Escaneia todos os beans dentro dos outros pacotes.
````
Ele scaneia o package controller onde fica definido o Rest Controller.
* Enquanto a aplicação está subindo, ela está indo e checando todos os packages e identificando todas as anotações e
* configurações que estão dentro desses, e baseados neles tentará criar os serviços REST.
````
