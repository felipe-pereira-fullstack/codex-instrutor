# Codex Instrutor

Use o Codex como instrutor de programação para desenvolver raciocínio técnico e autonomia. Com o `AGENTS.md`, você define instruções para a IA orientar seu aprendizado com perguntas, pistas e revisão das suas decisões.

## Como configurar

### 1. Adicione o AGENTS.md

Escolha onde deseja aplicar as instruções e copie para o arquivo o conteúdo de [GUIDELINES.md](GUIDELINES.md).

**Em um projeto:** crie o `AGENTS.md` na raiz do projeto.

**Em todos os projetos:** crie o `AGENTS.md` na pasta de configuração do Codex.

- **Windows:** `C:\Users\SEU_USUARIO\.codex\AGENTS.md`
- **macOS e Linux:** `~/.codex/AGENTS.md`

Crie a pasta `.codex` se necessário. Se o arquivo já existir, acrescente as instruções ao conteúdo atual. Se você configurou `CODEX_HOME`, use a pasta indicada por essa variável.

### 2. Personalize a regra 4

No `AGENTS.md` que você acabou de configurar, **edite manualmente a regra 4**, substituindo `[SUA DIFICULDADE]` e `[SUA ZONA DE CONFORTO]` conforme o que você quer praticar.

| Minha dificuldade | Minha zona de conforto |
| --- | --- |
| Escrever testes automatizados | Validar tudo manualmente |
| Construir consultas SQL com JOIN | Carregar os dados e cruzar as listas em C# |
| Modelar regras de negócio | Começar direto pelas telas e pelo CRUD |

Escolha um exemplo que represente seu momento ou escreva o seu próprio.

Depois de salvar, abra uma nova sessão do Codex no projeto e comece a conversa. Por exemplo, “Quero implementar paginação. Me ajude a pensar no comportamento esperado, uma pergunta por vez.”

## Inspiração

Este projeto foi inspirado no [mentor-prompt, de guithepc](https://github.com/guithepc/mentor-prompt), com instruções adaptadas para uso no Codex.
