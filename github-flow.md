O que eu aprendi sobre o GitHub Flow
Criar uma branch nova a partir da main, com um nome que mostra o que você vai fazer.
Fazer as mudanças nessa branch e ir salvando com commits.
Abrir um pull request pra mostrar o que você mudou.
Os outros olham, comentam e se precisar você arruma alguma coisa.
Quando tá tudo certo, faz o merge, que é juntar a branch na main.
Apagar a branch, porque ela não serve mais pra nada.

A gente não edita direto na main porque ela é a versão principal do projeto, e todo mundo usa ela. Se alguém mexer direto e errar alguma coisa, o erro já vai pra todo mundo e pode estragar o projeto. Usando uma branch, dá pra testar e errar sem medo, porque nada muda na main até alguém olhar e aprovar. É tipo fazer um rascunho antes de passar a limpo.

No diff, o vermelho mostra as linhas que foram tiradas e o verde mostra as linhas que foram colocadas. Quando você muda só uma linha, aparece a antiga em vermelho e a nova em verde embaixo. Isso ajuda a ver rapidinho o que mudou sem ter que ler o arquivo todo.
