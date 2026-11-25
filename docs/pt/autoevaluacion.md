# Autoavaliação: fundamentos do GitHub

Estas são perguntas originais para revisar os conceitos do curso. Não são perguntas oficiais e não representam um exame de certificação. Quando uma certificação-alvo for escolhida, cada pergunta poderá ser relacionada aos objetivos públicos dela.

Tente responder antes de abrir cada explicação.

## Git e GitHub

### 1. Qual afirmação descreve melhor a relação entre Git e GitHub?

- A. Git é uma plataforma de hospedagem de sites, e GitHub é um formato de arquivo.
- B. Git é um sistema de controle de versão; GitHub é uma plataforma para hospedar repositórios Git e colaborar.
- C. Git e GitHub são dois nomes para o mesmo aplicativo.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: B.** Git registra e gerencia o histórico de alterações. GitHub oferece serviços para hospedar repositórios Git e colaborar neles.

</details>

## Repositórios, commits e branches

### 2. O que um repositório geralmente contém?

- A. Os arquivos do projeto e o histórico de alterações.
- B. Apenas a versão mais recente de cada arquivo, sem histórico.
- C. Somente pull requests.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: A.** Um repositório reúne os arquivos do projeto e o histórico de alterações registrado pelo Git.

</details>

### 3. Qual é a finalidade de criar um branch?

- A. Trabalhar em alterações de forma isolada antes de propô-las para outro branch.
- B. Apagar o histórico do branch padrão.
- C. Transformar uma issue em arquivo.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: A.** Um branch permite desenvolver alterações sem modificar diretamente o branch de destino, como `main`.

</details>

### 4. O que um commit representa?

- A. Uma conversa sobre uma tarefa.
- B. Um conjunto registrado de alterações no histórico do repositório.
- C. Uma cópia independente do repositório em outra conta.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: B.** Um commit salva alterações no histórico do Git e normalmente inclui uma mensagem que as descreve.

</details>

## Issues e pull requests

### 5. Quando é adequado criar uma issue?

- A. Para documentar ou discutir uma tarefa, um problema ou uma melhoria.
- B. Para mesclar um branch automaticamente.
- C. Para salvar uma versão do projeto sem histórico.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: A.** Issues ajudam a organizar o trabalho e discutir problemas ou propostas; por si só, não alteram os arquivos.

</details>

### 6. O que um pull request permite fazer?

- A. Propor alterações de um branch para revisão e discussão antes de integrá-las.
- B. Alterar a senha de todas as pessoas colaboradoras.
- C. Criar uma cópia local do repositório no navegador.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: A.** Um pull request compara alterações entre branches e facilita a revisão e a discussão antes do merge.

</details>

### 7. O que significa selecionar **Request changes** em uma revisão?

- A. A pessoa revisora solicita alterações antes que o pull request seja integrado.
- B. O pull request é mesclado imediatamente.
- C. A issue relacionada é excluída.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: A.** A revisão comunica que são esperadas alterações antes da aprovação. A pessoa autora pode responder e enviar commits para o mesmo branch.

</details>

### 8. O que `Closes #12` na descrição de um pull request faz?

- A. Fecha a issue quando o pull request é mesclado no branch padrão.
- B. Fecha o repositório para novas contribuições.
- C. Cria automaticamente um branch chamado `12`.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: A.** Palavras-chave como `Closes` vinculam o pull request a uma issue e a fecham quando a alteração é mesclada no branch padrão.

</details>

## Mesclar alterações

### 9. O que acontece quando um pull request é mesclado?

- A. As alterações propostas são integradas ao branch de destino.
- B. Todo o histórico do repositório é excluído.
- C. O repositório é convertido em uma issue.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: A.** O merge integra as alterações do branch de origem ao branch de destino. O método pode variar conforme as configurações do repositório.

</details>

### 10. Quem pode enviar uma revisão formal do seu pull request?

- A. A pessoa autora deve aprovar o próprio pull request.
- B. Outra pessoa com pelo menos acesso de leitura ao repositório.
- C. Qualquer visitante, independentemente das permissões.

<details>
<summary>Ver resposta e explicação</summary>

**Resposta: B.** Qualquer pessoa com acesso de leitura pode revisar e comentar as alterações propostas. A pessoa autora não pode revisar o próprio pull request.

</details>

---

[Voltar ao índice do curso](README.md)
