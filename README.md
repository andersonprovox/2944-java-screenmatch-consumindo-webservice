![thumbnail-Formação Java (4)](https://user-images.githubusercontent.com/66698429/226751112-f79aaa28-16c9-4561-8a15-0ac62ec9cb44.png)


# Java: consumindo uma API, gravando arquivos e lidando com erros

Projeto desenvolvido no quarto curso da formação Java da Alura


## 🔨 Objetivos do projeto

- Aprender a consumir uma API HTTP em Java;
- Entender como receber e converter dados no formato JSON; 
- Utilizar a biblioteca externa GSON para fazer serialização e desserialização de dados;
- Lidar com erros e tratar exceções;
- Conhecer o pacote java.io para manipulação de arquivos.

## Observações

Para rodar o projeto é necessário apresentar o código gerado ao se inscrever na API da Omdb, portanto esta chave está omitida.
Portanto na classe `PrincipalComBuscas.java` deverá inserir a sua Apikey na linha 35:
```java
String endereco = "https://www.omdbapi.com/?t=" + busca + "&apikey<insira aqui";
```
