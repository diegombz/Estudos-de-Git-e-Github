# **Conceitos fundamentais do Git** :book:

### Repositórios

Um **repositório** é como uma pasta ou diretório que contém todos os arquivos e o histórico de um projeto.

---

### Commits

Já o termo **commit** pode ter como tradução literal “compromisso”, que seria uma ação em que você faz uma alteração no projeto, se compromete e salva suas alterações no histórico do projeto.
Ou seja, cada commit é uma entrada no histórico que contém informações sobre as alterações feitas.

---

### Árvores (Trees)

Árvores representam a estrutura do diretório e arquivos em um commit específico, que tem como função registrar a organização do projeto ao longo do histórico de desenvolvimento.

---

### Ramificações (Branches) e fusões (Merges)

Branches são linhas independentes de desenvolvimento dentro de um repositório Git. Elas permitem implementar recursos, correções ou refatorações sem interferir na branch principal (`main`). Após as modificações estarem finalizadas e validadas, utiliza-se o comando `git merge` para integrar as alterações ao fluxo principal do projeto.