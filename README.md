# hello-world-xunit

Projeto simples que demonstra testes unitários em C# com xUnit.

## Solução

- `MeuPrimeiroTeste.App`: aplicação de console com a classe `OlaMundo`, cujo método `ObterMensagem()` retorna `"Hello, World!"`.
- `MeuPrimeiroTeste.Tests`: projeto de testes com `OlaMundoTeste`, que valida o retorno do método usando `Assert.Equal()`.

## Tecnologias

- .NET 10
- xUnit

## Como executar

Rodar a aplicação:

```
dotnet run --project MeuPrimeiroTeste.App
```

Rodar os testes:

```
dotnet test
```

## Licença

MIT
