# guia-de-revisao-git

Mini guia de revisão de Versionamento e Colaboração.

## Integrantes
- Aluno A: Lucas
- Aluno B: Joao

## O que tem aqui
- glossario.md: oito termos de versionamento
- github-flow.md: os seis passos do fluxo
- combinados.md: o dia de estudo da dupla

## Nossas respostas

### 1. O diff
No commit de ajuste, o que estava em vermelho representava as linhas que foram removidas ou substituídas. Já o verde mostrava as linhas novas que foram adicionadas. Assim, conseguimos comparar as alterações sem precisar ler o arquivo inteiro.

### 2. O conflito
Um conflito acontece quando duas pessoas fazem alterações diferentes na mesma parte de um arquivo, e o Git não consegue decidir automaticamente qual versão deve permanecer.

Os três marcadores significam:
- `<<<<<<<`: indica o início da primeira versão do texto.
- `=======`: separa as duas versões em conflito.
- `>>>>>>>`: indica o final da outra versão.

O texto final foi escolhido depois de comparar as duas sugestões e decidir qual fazia mais sentido para o projeto. Depois, removemos os marcadores e deixamos apenas a versão escolhida.

### 3. A revisão
O comentário de revisão recebido foi:

"Na parte sobre commits, acho que seria legal acrescentar que cada commit deve ter uma mensagem explicando as alterações feitas, para facilitar a identificação do que foi modificado."

O comentário foi específico, sugeriu uma solução e ajudou a melhorar o trabalho. Também houve reconhecimento dos pontos positivos, principalmente na explicação da diferença entre Git e GitHub.

Antes do ajuste, foi utilizada a opção de comentar e sugerir melhorias. Depois das alterações, o conteúdo foi revisado novamente para verificar se as sugestões tinham sido atendidas.

### 4. Segurança
Não. Mesmo que alguém apague um telefone no commit seguinte, a informação ainda pode continuar aparecendo no histórico de versões do Git. Por isso, apagar uma informação não significa que ela foi completamente removida do histórico.

Dois exemplos de informações que nunca devem ser publicadas são:
- Senhas de contas e sistemas.
- Dados de cartões de crédito.

Essas informações são privadas e podem ser utilizadas indevidamente por outras pessoas.
