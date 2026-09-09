# Consumer ViaCEP API

Uma aplicação de console desenvolvida em C# e .NET para consumir a API pública do [ViaCEP](https://viacep.com.br/). O programa solicita que o usuário digite um CEP, realiza uma requisição HTTP assíncrona e desserializa o JSON retornado para exibir os dados de endereço (Rua, Cidade, etc.) diretamente no terminal.

Projeto prático desenvolvido na disciplina de Usabilidade, Dev. Web, Mobile e Jogos.

## Tecnologias Utilizadas
* C# 
* .NET (Console Application)
* `HttpClient` para requisições
* `System.Text.Json` para mapeamento e desserialização (`JsonPropertyName`)

## Como Executar

1. Clone este repositório:
   ```bash
   git clone [https://github.com/lucabar-r/consumer-via-cep.git](https://github.com/lucabar-r/consumer-via-cep.git)