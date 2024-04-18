# forma de commits 🍰
Baseado em:
- [Padrões de commits](https://github.com/iuricode/padroes-de-commits/tree/main)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)
- [Colinha commits semântico](https://github.com/AdrianaSaty/colinha-commit-semantico)
  
'Uma tentativa de criar uma "receita de bolo" para meus commits baseado no conceito de commits semanticos
uma maneira simples de padronização dos commits para tornar inteligível as alterações do codigo posteriormente.


## Orientações 📜
➢Tentar resumir o Titulo de maneira mais curta o possível.

➢Colocar emojis para facilitar a interpretação.

➢Se necessário maior detalhamento do commit, usar descrição para isto.

➢Todos os elemmentos (emoji,type e description) são Obrigatórios 

➢ usar o formato `<emoji> <type>: <description>`

# Type e description 💻

Para fazer commits bem estruturados dividimos o conteúdo escrito em duas partes `<type>` e `<description>`, onde type significa o proposito daquele commit e description e o conteudo alterado ou adicionado ao codigo.
## Tipos de type:

| Prefixo |emoji | Descrição           | Significado                                    |
|---------|-|--------------------|------------------------------------------------|
| feat    |✨|Features            | Uma nova funcionalidade                        |
| fix     |🐛|Correções de Erros  | Uma correção de bug                            |
| docs    |📚| Documentação        | Apenas mudanças na documentação               |
| style   |🖼️|Estilos             | Mudanças em relação a estilização              |
| refactor|♻️|Refatoração de Código | Uma alteração de código que não corrige um bug nem adiciona uma funcionalidade |
| perf    |⚡|Melhorias de Performance | Uma alteração de código que melhora o desempenho |
| test    |🧪|Testes              | Adição de testes em falta ou correção de testes existentes |
| build   |➕|Builds              | Mudanças que afetam o sistema de build ou dependências externas (exemplos de escopos: gulp, broccoli, npm) |
| ci      |🧱|Integrações Contínuas | Alterações em nossos arquivos e scripts de configuração de CI (exemplos de escopos: Travis, Circle, BrowserStack, SauceLabs) |
| chore   |🔧|Tarefas             | Outras mudanças que não modificam arquivos de código-fonte ou de teste |
| revert  |⏳|Reverter            | Reverte um commit anterior                    |

Exemplificação: Em um commit de correção de um bug na linha 20 sobre uma função que não funciona como deveria, o commit poderia ser:
|comando do git| Resultado no Github |
|--------------|---------------------|
|git commit -m ":bug: fix: Função ineficaz na linha 20"|🐛 fix: Função ineficaz na linha 20|

# Considerações finais 😁
Este repositório e uma maneira de resumir tudo que estudei sobre commits semânticos e como tornar mais eficaz a criação dos mesmos. Espero que possa ajudar outras pessoas a organizar os commits para si mesmo ou entre uma equipe utilizando esse padrão ou adaptando o para algo que condiza mais com a sua necesssidade, por exemplo, poderia quando for criar um arquivo Package.json em JS ao invés de colocar o emoji padrão de build defini-lo como 📦.
