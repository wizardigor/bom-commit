# Como escrever uma boa mensagem de commit

Uma mensagem de confirmação é uma breve descrição das mudanças que você fez em um arquivo adicionado antes de confirmar as mudanças.

Boas mensagens de commit são importantes não apenas para outros com quem você possa estar colaborando no projeto, mas também para você, para manter o controle de todos os seus commits e saber exatamente quais mudanças podem ocorrer durante aquele commit em particular.

Mesmo se você estiver trabalhando em um projeto pessoal, eu recomendo que você comece a adquirir o hábito de escrever boas mensagens de commit.

Este é o formato que eu uso na maioria das vezes (isso pode mudar dependendo da sua preferência ou organização para a qual você trabalha):


>* type: subject
>* body (optional)
>* footer (optional)


## 1. Type
* **feat -** um novo recurso
* **fix -** uma correção de bug
* **docs -** mudanças na documentação
* **style -** tudo relacionado a estilo
* **refactor -** mudanças de código que não corrigem um bug ou adicionam um recurso
* **test -** tudo relacionado ao teste
* **chore -** atualização de tarefas de construção, configurações do gerenciador de pacotes, etc

## 2. Assunto
Contém uma breve descrição das mudanças feitas. Não deve ter mais de 50 caracteres, deve começar com uma letra maiúscula e escrito no imperativo, ex. **Adicione** em vez de *Adicionado* ou *Adiciona*.

## 3. Corpo
O corpo é usado para explicar quais mudanças você fez e por que você as fez. Nem todos os commits são complexos o suficiente para precisar de um corpo, especialmente se você estiver trabalhando em um projeto pessoal sozinho e, como tal, escrever um corpo é opcional.

É necessária uma linha em branco entre o corpo e o assunto e cada linha deve ter no máximo 72 caracteres.

## 4. Rodapé
O rodapé também é opcional e usado principalmente quando você usa um rastreador de problemas para fazer referência ao ID do problema.

---
Exemplo de uma boa mensagem de confirmação usada pelo aluno Udacity Guia de estilo de mensagem de confirmação Git da Udacity.

> feat: Resuma as mudanças em cerca de 50 caracteres ou menos
> 
> Texto explicativo mais detalhado, se necessário. Envolva-o em cerca de 72 caracteres ou mais. Em alguns contextos, a primeira linha é tratada como o assunto do commit e o resto do texto como o corpo. A linha em branco que separa o resumo do corpo é crítica (a menos que você omita totalmente o corpo); várias ferramentas como *log*, *shortlog* e *rebase* pode ficar confuso se você executar os dois juntos.
> 
> Explique o problema que este commit está resolvendo. Concentre-se em por que você está fazendo essa alteração, e não em como (o código explica isso). Existem efeitos colaterais ou outras consequências não intuitivas dessa mudança? Aqui está o lugar para explicar a eles.
> 
> Outros parágrafos vêm depois de linhas em branco.
> 
> * Os marcadores também estão bem
> * Normalmente, um hífen ou asterisco é usado para o marcador, precedido por um único espaço, com linhas em branco no meio, mas as convenções variam aqui
> 
> Se você usar um rastreador de problemas, coloque referências a eles na parte inferior, como este:
> 
> Resolve: #123  
> Veja também: #456, #789



Um exemplo mais prático:  
docs: Corrigir erro de digitação no README.md
