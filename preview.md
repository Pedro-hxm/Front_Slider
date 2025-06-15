## Hierarquia no Git/GitHub

No Git/GitHub, a hierarquia de branches (ramificações) ajuda a organizar o desenvolvimento do projeto. Normalmente, existe uma branch principal chamada `main`, que representa a versão estável do projeto. Outras branches, como `preview`, são usadas para testar novas funcionalidades ou alterações antes de integrá-las ao `main`.

### Exemplo no seu projeto

No seu projeto, você possui duas branches principais:

- `main`: contém a versão estável e oficial do projeto.
- `preview`: serve para testar e revisar alterações antes de serem aplicadas ao `main`.

O fluxo de trabalho recomendado é:

1. **Fazer alterações na branch `preview`**: Todas as novas funcionalidades ou correções devem ser feitas primeiro na branch `preview`.
2. **Testar e revisar**: As alterações são testadas e revisadas na branch `preview` para garantir que não causem problemas.
3. **Aprovação para o `main`**: Somente após a validação, as alterações podem ser integradas à branch `main`.

> **Importante:** Apenas você, Pedro Henrique, tem permissão para decidir o que será integrado à branch `main`. Isso evita problemas e garante a qualidade do projeto.

Esse processo ajuda a manter o projeto organizado e seguro, evitando que alterações não testadas afetem a versão principal.
