# The-Book-of-programming

## O livro é um texto retirado do capítulo 6 do Eloquent Javascript (primeira edição)

"Era uma vez, vivendo nas profundas florestas montanhosas da Transilvânia, um recluso. Na maior parte do tempo, ele apenas vagava pela montanha, conversando com as árvores e rindo com os pássaros. Mas de vez em quando, quando a chuva torrencial o prendia em seu casinha, e o vento uivante fazia com que ele se sentisse insuportavelmente pequeno, o recluso sentiu vontade de escrever alguma coisa, quis colocar alguns pensamentos no papel, onde talvez pudessem ficar maiores do que ele próprio.

"Depois de falhar miseravelmente em poesia, ficção e filosofia, o recluso finalmente decidiu escrever um livro técnico. Em sua juventude, ele havia feito alguma programação de computadores e percebeu que se pudesse escrever um bom livro sobre isso, fama e o reconhecimento certamente se seguiria.

"Então ele escreveu. No começo ele usou fragmentos de casca de árvore, mas isso acabou não sendo muito prático. Ele foi até a aldeia mais próxima e comprou um laptop. Depois de alguns capítulos, ele percebeu que queria colocar o livro em formato HTML, para colocá-lo em sua página web...

"O recluso queria ter seu livro em formato HTML. No início, ele apenas escrevia todas as tags diretamente em seu manuscrito, mas digitar todos aqueles sinais de menor e maior que fazia seus dedos doerem, e ele constantemente se esquecia de escrever &amp; quando ele precisava de um &. Isso lhe deu dor de cabeça. Em seguida, ele tentou escrever o livro no Microsoft Word e salvá-lo como HTML. Mas o HTML resultante era quinze vezes maior e mais complicado do que o necessário. Além disso, o Microsoft Word lhe dava dor de cabeça.

"A solução que ele finalmente encontrou foi esta: ele escreveria o livro como texto simples, seguindo algumas regras simples sobre a forma como os parágrafos eram separados e a aparência dos títulos. Em seguida, ele escreveria um programa para converter esse texto em formato preciso. o HTML que ele queria.

"As regras são estas:
    *Os parágrafos são separados por linhas em branco.
    *Um parágrafo que começa com o símbolo '%' é um cabeçalho. Quanto mais símbolos '%', menor será o cabeçalho.
    *Dentro dos parágrafos, trechos de texto podem ser enfatizados colocando-os entre asteriscos.
    *As notas de rodapé são escritas entre colchetes.

"Depois de ter lutado dolorosamente com seu livro por seis meses, o recluso ainda havia terminado apenas alguns parágrafos. Nesse ponto, sua cabana foi atingida por um raio, matando-o e pondo de lado para sempre suas ambições de escrever. Dos restos carbonizados de seu laptop, consegui recuperar o seguinte arquivo:


"% O Livro da Programação

    %% Os dois aspectos

       'Abaixo da superfície da máquina, o programa se move. Sem esforço,
        ele se expande e contrai. Em grande harmonia, os elétrons se dispersam e
        reagrupar. As formas no monitor são apenas ondulações na água. O
        a essência permanece invisível abaixo.

       'Quando os criadores construíram a máquina, eles colocaram o processador e a
        memória. Destes surgem os dois aspectos do programa.

       'O aspecto do processador é a substância ativa. É chamado
        controle. O aspecto da memória é a substância passiva. Isso é
        chamado Dados.
    
       'Os dados são feitos apenas de bits, mas assumem formas complexas. O controle
        consiste apenas em instruções simples, mas executa tarefas difíceis. 
        Do pequeno e trivial surge o grande e o complexo.
    
       'A fonte do programa é Data. O controle surge disso. O controle
        prossegue para criar novos dados. Um nasce do outro, o
        outro é inútil sem aquele. Este é o ciclo harmonioso de
        Dados e Controle.
    
       'Por si só, Dados e Controle não têm estrutura. Os programadores
        antigamente moldavam os seus programas a partir desta matéria-prima. 
        Ao longo do tempo, os dados amorfos cristalizaram-se em tipos de dados.
        O controle foi restrito a estruturas e funções de controle.
    
    %% Provérbios curtos
    
       'Quando um aluno perguntou a Fu-Tzu sobre a natureza do ciclo de Dados e
        Controle, Fu-Tzu respondeu: 'Pense em um compilador, compilando-se sozinho.'
    
       'Um aluno perguntou: 'Os programadores de antigamente usavam apenas máquinas simples e
        sem linguagens de programação, mas eles criaram belos programas. Por que nós
        usamos máquinas e linguagens de programação complicadas?'. Fu-Tzu respondeu
        'Os construtores de antigamente usavam apenas paus e barro, mas eles fizeram
        lindas cabanas.
    
       'Um eremita passou dez anos escrevendo um programa. 'Meu programa pode calcular
        o movimento das estrelas em um computador 286 rodando MS DOS', ele orgulhosamente
        anunciado. 'Ninguém mais possui um computador 286 ou usa MS DOS.',
        Fu-Tzu respondeu.
    
       'Fu-Tzu escreveu um pequeno programa cheio de estado global e
        atalhos duvidosos. Ao lê-lo, um aluno perguntou: 'Você nos alertou contra
        essas técnicas, mas eu as encontro em seu programa. Como isso pode ser?'
        Fu-Tzu disse: 'Não há necessidade de buscar uma mangueira de água quando a casa está
        não está pegando fogo.'{Isso não deve ser lido como um incentivo ao desleixo
        programação, mas sim como um alerta contra a adesão neurótica a
        regras de ouro.}
    
    %% Sabedoria
    
       'Um estudante estava reclamando de números digitais. 'Quando eu tiro a raiz
        de dois e depois elevá-lo novamente ao quadrado, o resultado fica impreciso!'.
        Ao ouvi-lo, Fu-Tzu riu. 'Aqui está uma folha de papel. Escreva
        o valor preciso da raiz quadrada de dois para mim.'
    
       'Fu-Tzu disse 'Quando você corta contra a fibra da madeira, muita força
        é preciso. Quando você programa na contramão de um problema, muito código
        é preciso.'
        
       'Tzu-li e Tzu-ssu estavam se gabando do tamanho de seu último
        programas. 'Duzentas mil linhas', disse Tzu-li, 'sem contar
        comentários!'. 'Psah', disse Tzu-ssu, 'o meu tem quase um *milhão* de linhas
        já.' Fu-Tzu disse: 'Meu melhor programa tem quinhentas linhas'.
        Ao ouvir isso, Tzu-li e Tzu-ssu foram iluminados.
        
       'Um estudante estava sentado imóvel atrás de seu computador há horas,
        franzindo a testa sombriamente. Ele estava tentando escrever uma bela solução para um
        problema difícil, mas não consegui encontrar a abordagem correta. Fu-Tzu o golpeou na
        parte de trás da cabeça e gritou '*Digite alguma coisa!*' O aluno
        comecei a escrever uma solução feia. Depois que ele terminou, ele de repente
        entendeu a bela solução.
        
    %% Progressão
    
       'Um programador iniciante escreve seus programas como uma formiga constrói seus
        morro, um pedaço de cada vez, sem pensar na estrutura maior.
        Seus programas serão como areia solta. Eles podem ficar parados por um tempo, mas
        crescendo muito, eles desmoronam{Referindo-se ao perigo de problemas internos
        inconsistência e estrutura duplicada em código não organizado.}.
    
       'Percebendo esse problema, o programador começará a gastar muito
        tempo pensando em estrutura. Seus programas serão rigidamente
        estruturados, como esculturas rupestres. Eles são sólidos, mas quando precisam
        mudança, a violência deve ser feita contra eles{Referindo-se ao fato de que
        a estrutura tende a colocar restrições na evolução de um programa.}.
        
       'O programador mestre sabe quando aplicar estrutura e quando sair
        coisas em sua forma simples. Seus programas são como argila, sólidos, mas
        maleáveis.
    
    %% Linguagem
        
        'Quando uma linguagem de programação é criada, ela recebe sintaxe e
        semântica. A sintaxe descreve a forma do programa, a semântica
        descreva a função. Quando a sintaxe é bonita e a semântica
        são claros, o programa será como uma árvore imponente. Quando a sintaxe é
        desajeitada e a semântica confusa, o programa será como um arbusto.

        'Tzu-ssu foi convidado a escrever um programa na linguagem chamada Java,
        que adota uma abordagem muito primitiva para funções. Todas as manhãs,
        ele se sentou na frente do computador e começou a reclamar. O dia todo
        ele praguejou, culpando a língua por tudo que deu errado. Fu-Tzu
        ouviu por um tempo e depois o repreendeu, dizendo: 'Toda língua
        tem seu próprio caminho. Siga sua forma, não tente programar como se você
        estivesse usando outro idioma.' '".
    
## Leia mais sobre em : https://eloquentjavascript.net/1st_edition/chapter6.html#p72845d53f6f05268