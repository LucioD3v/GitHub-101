# 05. Pull requests e revisão

## Criar uma solicitação de pull request

Para prosseguir com este passo, a primeira coisa que precisamos fazer é criar/adicionar um novo arquivo, já que estamos atualmente no ramo recém-criado. Vamos seguir estes passos:

1. Na aba **< > Code**, localizada no menu superior do repositório, certifique-se de que estamos no ramo que nomeamos de dev neste exemplo.

2. Em seguida, clique no menu suspenso "Add file" e selecione a opção "Create new file".
<br>

![Criar um novo arquivo](../../images/crear-nuevo-archivo.jpg)
3. Na nova visualização, você verá um campo vazio com um texto de placeholder dizendo "Name your file...". Isso indica que devemos fornecer um nome para o arquivo. Vamos chamá-lo de `LICENSE.md`.

**Observação**: `.md` é uma extensão de arquivo que cria um arquivo [Markdown](https://docs.github.com/en/get-started/quickstart/github-glossary#markdown). Para obter mais informações sobre Markdown, visite [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) na documentação do GitHub ou faça o curso [Communicate using Markdown](https://github.com/skills/communicate-using-markdown).

<br>

[Modelo de Licença](../../images/licencia-plantilla.jpg)

```
Aviso de Direitos Autorais.

Por meio deste, é concedida permissão, gratuitamente, a qualquer pessoa que obtenha uma cópia deste software e dos arquivos de documentação associados (o "Software"), para operar com o Software sem restrições, incluindo, sem limitação, os direitos de usar, copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias do Software, e permitir que pessoas a quem o Software seja fornecido façam o mesmo, sujeito às seguintes condições:

O aviso de direitos autorais acima e este aviso de permissão devem ser incluídos em todas as cópias ou partes substanciais do Software.

O SOFTWARE É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE QUALQUER TIPO, EXPRESSA OU IMPLÍCITA, INCLUINDO, MAS NÃO SE LIMITANDO A, AS GARANTIAS DE COMERCIALIZAÇÃO, ADEQUAÇÃO A UMA FINALIDADE ESPECÍFICA E NÃO VIOLAÇÃO. EM NENHUMA CIRCUNSTÂNCIA, OS AUTORES OU DETENTORES DOS DIREITOS AUTORAIS SERÃO RESPONSÁVEIS POR QUALQUER REIVINDICAÇÃO, DANOS OU OUTRA RESPONSABILIDADE, SEJA EM UMA AÇÃO DE CONTRATO, DELITO OU DE OUTRA FORMA, DECORRENTE DE, OU EM CONEXÃO COM O SOFTWARE OU O USO OU OUTRAS OPERAÇÕES COM O SOFTWARE.
```

![Texto da licença](../../images/licencia-texto.jpg)

5. Em seguida, clique no botão **Commit changes**. Semelhante ao passo anterior em que criamos o arquivo `README`, uma janela pop-up aparecerá pedindo uma breve mensagem de commit que descreva as alterações que fizemos. Lembre-se de que essa mensagem ajuda outras pessoas a entenderem o que estamos adicionando em nosso commit. Embora o GitHub forneça uma mensagem padrão simples, vamos personalizá-la um pouco para praticar.

<br>
Primeiro, no título, vamos escrever: "Adicionar arquivo LICENSE.md". Na descrição estendida, vamos digitar: "Criar um arquivo de Licença em formato markdown que expressa o aviso de direitos autorais."

6. Por fim, confirmamos as alterações clicando no botão **Commit changes**.

![licencia commit](../../images/licencia-commit.jpg)

Ótimo! Você já está dominando o processo de fazer commits. Não é simples?

Agora que você fez um commit na branch `dev`, abra um pull request: selecione **Compare & pull request** se essa opção aparecer ou acesse **Pull requests** > **New pull request**. Defina **base** como `main` e **compare** como `dev`, adicione um título e uma descrição e selecione **Create pull request**. Se você criou uma issue na lição anterior, inclua `Closes #<número>` na descrição para vinculá-la.

## Revisar um pull request

A revisão permite conversar sobre as alterações antes que sejam incorporadas ao projeto. Com o pull request aberto, peça a outra pessoa que o revise antes do merge.

### Atividade: revisar as alterações

1. Peça a outra pessoa com pelo menos acesso de leitura ao repositório para revisar seu pull request e abrir a aba **Files changed**.
2. Ela pode comentar em uma linha específica ou selecionar **Review changes** e enviar uma revisão como **Comment**, **Approve** ou **Request changes**.
3. Leia e responda aos comentários. Se forem solicitadas alterações, envie-as para o mesmo branch e peça uma nova revisão.
4. Quando a revisão estiver resolvida, continue para a próxima lição para aprender a mesclar o pull request. Se a descrição incluir `Closes #<número>`, a issue vinculada será fechada quando ele for mesclado no branch padrão.

Você não pode revisar o próprio pull request. Se estiver aprendendo sozinho, pode explorar as abas **Conversation** e **Files changed**, mas precisará de outra pessoa com pelo menos acesso de leitura para praticar uma revisão.

Consulte o guia oficial sobre [revisões de pull requests](https://docs.github.com/pt/pull-requests/reference/pull-request-reviews).

---

[Voltar ao índice do curso](README.md)
