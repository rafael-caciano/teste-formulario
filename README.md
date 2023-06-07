# teste-formulario
 Treino de formulário e estilização

O que terá no projeto:

Ele será composto por um formulário que conterá

input de: Nome
input de: email
input de: idade
input de: status de estudante (dando diferentes opçoes como: ensino incompleto, cursando, ensino completo)

um
input de: se recomendaria ou nao o site "radio" do tipo que de mais de uma opção mas que só possa marcar uma (obs: dar mesmo name para todas as opçoes no html se nao ele nao desmarca)
input de: com varias opções com caixas a serem marcadas e podendo marcar mais de uma
input de: de comentário onde possa escrever um preve texto.



Design:

um background com a imagem que preferir com uma mascara roxa transparente 

o formulário com um transparente mais escuro destacando no centro da tela com um width de 60% (+/- veja conforme faz o projeto)
com um H1 fora do formulário

//  OBSERVAÇÕES PARA A CONCLUSÃO 

o input NOME, EMAIL, E DATA DE NASCIMENTO, foram bem facies pois já tinha o basic para executar essa parte.

O campo de ESCOLARIDADE, tive que relenbrar como criar um input com varias opçoes, como está no projeto a forma de faze-lo é usando um <select></slect> que por sua vez é composta pos <option></option> esses "options" vao conter dentro deles a opção correspondente, tive duvida em como criar oq no input podemos usar o "PLACEHOLDER" no select nao funciona, entao vimos que para criar uma instrução dentro da caixa do formulario no primeiro "option" atribuimos um "desable select hidden" (<option value="" disable select hidden>....</option>) assim como o exemplificado.

Já o campo LINGUAGENS, foi necessário criar varios inputs com o type="checkbox", é um tipo de input expecifico para essa função de marcar opções, é só organizar tudo dentro de uma div e cada input dentro de uma outra div.

O campo RECOMENDA, relembramos que é necessário criar varios input:radio porém todos eles com o mesmo (name="") para que somente uma opção seja marcada.

No ultimo campo de texto, vimos uma nova tag, a <textarea></textarea> ela cria uma area que texto como o proprio nome sugere, colocando paremetros dentro da tag para estiputar numero de linhas e colunas <textarea cols="10" rows="20"> como e exemplificado.


Para a transparencia a cor no BODY usamos um atributo chamado "backgruond-blend-mode:" asossiado a um "background-color" também.