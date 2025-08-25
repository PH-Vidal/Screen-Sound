## Screen Sound — Console App em C#

Aplicativo de console para cadastro e avaliação de bandas. Permite registrar bandas, listar todas as registradas, atribuir notas e calcular a média das avaliações.

### Funcionalidades
- Registrar novas bandas
- Listar bandas registradas
- Avaliar uma banda com notas inteiras
- Exibir a média de avaliações por banda
- Menu interativo no terminal

### Tecnologias
- C# (.NET)
- Aplicação de console

### Como executar
1. Instale o .NET SDK (versão atual recomendada): `https://dotnet.microsoft.com/`
2. No terminal, navegue até a pasta do projeto:
   - `cd fundamentos-csharp`
3. Execute:
   - `dotnet run`

### Estrutura do projeto
- `Program.cs`: lógica principal (menu, cadastro, avaliações, médias)
- `PrimeiroProjeto.csproj`: configuração do projeto

### Exemplo de uso
- Digite `1` para registrar uma banda (ex.: "Linkin Park")
- Digite `3` para avaliar uma banda (ex.: nota 10)
- Digite `4` para ver a média de notas da banda
- Digite `-1` para sair

### Próximos passos (ideias)
- Persistência em arquivo ou banco de dados
- Validações de entrada e tratamento de erros
- Limitar notas a uma faixa (ex.: 0–10)
- Interface de usuário mais rica (ex.: colorização, submenus)
