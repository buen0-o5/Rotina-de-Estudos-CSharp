<h1>Rotina de Estudos - Desenvolvedora Fullstack</h1>
<p>Tenho o objetivo de me tornar uma desenvolvedora fullstack e escolhi a linguagem C# como meu principal foco de aprendizado.</p>
<p>Estou empenhada em aprimorar minhas habilidades nessa linguagem, a fim de poder atuar tanto no desenvolvimento do lado do cliente quanto no servidor, proporcionando soluções completas aos projetos em que trabalharei.</p>
<p>Para alcançar esse objetivo, estou criando este repositório como uma forma de estabelecer uma rotina de estudos.</p>

<h2>Plano de Estudos</h2>
<ul>
<li>Introdução ao C# e ambiente de desenvolvimento</li>
<li>Sintaxe básica de C# (variáveis, tipos de dados, operadores)</li>
<li>Aprender sobre o desenvolvimento de aplicações web usando ASP.NET</li>
<li>Entrada e saída de dados</li>
<li>Condicionais (if/else)</li>
<li>Controle e Fluxo</li>
<li>Métodos e funções</li>
<li>Depuração de código</li>
<li>Classes e objetos</li>
<li>Programação Orientada a Objetos </li>
<li>SQL e Forms</li>
<li>ORM’s e Tasks </li>
</ul>

<h2>Introdução ao C# e ambiente de desenvolvimento</h2>

<p>C# (pronunciado "C sharp") é uma linguagem de programação moderna, orientada a objetos e fortemente tipada, desenvolvida pela Microsoft. Ela foi projetada para ser eficiente, segura e de fácil utilização, permitindo o desenvolvimento de uma ampla gama de aplicativos para diversas plataformas, como Windows, macOS, Linux, dispositivos móveis e a Web.

Ambiente de Desenvolvimento Integrado (IDE):
Para desenvolver aplicativos em C#, você precisará de um Ambiente de Desenvolvimento Integrado (IDE) adequado. A Microsoft oferece o Visual Studio como a IDE principal para desenvolvimento em C#. O Visual Studio é uma ferramenta poderosa que oferece recursos avançados de edição de código, depuração, compilação e gerenciamento de projetos. Ele está disponível em diferentes edições, incluindo a versão gratuita chamada Visual Studio Community, que é adequada para a maioria dos desenvolvedores.

Outra opção popular é o Visual Studio Code (VS Code), um editor de código-fonte leve e extensível, desenvolvido pela Microsoft e disponível gratuitamente. O VS Code possui suporte integrado para C# e uma grande variedade de extensões que podem aprimorar a produtividade durante o desenvolvimento.

Instalação:
Para começar a desenvolver em C#, você precisará instalar o ambiente de desenvolvimento adequado. A instalação do Visual Studio é bastante direta e você pode baixar a versão mais recente do site oficial da Microsoft (https://visualstudio.microsoft.com/). Durante a instalação, você poderá selecionar os componentes específicos que deseja instalar, incluindo o suporte para o desenvolvimento em C#.

Se você optar por usar o Visual Studio Code, precisará instalar a extensão do C# no editor. Abra o VS Code e vá até a seção de extensões, pesquise por "C#" e instale a extensão fornecida pela Microsoft.

Após a instalação do ambiente de desenvolvimento, você estará pronto para começar a escrever e executar programas em C#. O próximo passo é criar um novo projeto, escolher o tipo de aplicativo que deseja desenvolver (por exemplo, aplicativo de console, aplicativo para desktop ou aplicativo Web) e começar a escrever seu código-fonte.</p>

<h2>Sintaxe básica de C# (variáveis, tipos de dados, operadores)</h2>
<p></p>


## Definição de variável

> Em C#, uma variável é uma entidade que armazena um valor em um local específico na memória. Ela é usada para armazenar dados que serão usados mais tarde no programa e pode ter um tipo de dados específico que define o tipo de valor que pode ser armazenado na variável. Existem três componentes principais de uma variável em C#: o nome da variável, o tipo de dados e o valor da variável. O nome da variável é usado para identificá-la e acessá-la no código. O tipo de dados define o tipo de valor que pode ser armazenado na variável, como um número inteiro, um caractere, um booleano ou uma cadeia de caracteres. O valor da variável é o valor real armazenado na variável.

```csharp
ex:
int idade = 30;
```

## Definição de constante

> Em C#, uma constante é uma variável cujo valor não pode ser alterado após ser definido. Isso significa que uma vez que uma constante é definida, seu valor é fixo e não pode ser alterado durante a execução do programa.
> 
> 
> As constantes são úteis quando você tem valores que precisam ser usados em vários lugares do seu código, mas não devem ser alterados. Por exemplo, o valor de pi é uma constante que pode ser usada em várias partes do seu código, mas não deve ser alterada.
> 
> Para declarar uma constante em C#, use a palavra-chave "const" seguida do tipo de dados e do nome da constante, seguido do valor constante que não pode ser alterado.
>
```csharp
ex:
const double pi = 3.14159;
```

## Definição de Object

Object é um tipo de dados que pode armazenar qualquer tipo de valor, incluindo valores de tipos de dados primitivos, objetos personalizados, matrizes e assim por diante. Isso significa que você pode declarar uma variável do tipo "object" e atribuir a ela qualquer valor, independentemente do tipo de dados.

```jsx
object valorObjeto = 123; // declara uma variável do tipo object e atribui o valor de 123 a ela
Console.WriteLine("O tipo de dados da variável valorObjeto é: " + valorObjeto.GetType()); // imprime o tipo de dados da variável no console
```
## Tipos primitivos
```csharp
int:
 é um tipo inteiro usado para representar números inteiros, 
como 1, 2, 3, -4, -5, etc.
EX:
int soma = 1;
```

```csharp
Double é um tipo de ponto flutuante usado para
representar números decimais, como 3,14, 2,7, etc.
EX:
double a = 3.14;
```

```csharp
float: é outro tipo de ponto flutuante, mas
é menos preciso que o tipo double. Ele é usado para 
representar valores com casas decimais, como 3,14. para
declarar uma variável do tipo "float", você deve adicionar
o sufixo "f" ao valor atribuído.
EX:
float y = 2.71828f;
```

```csharp
decimal: é um tipo de ponto flutuante de alta precisão usado para
representar números decimais com muitas casas decimais, como em 
cálculos financeiros.
ex:
decimal preco = 10.99m; // declara uma variável do tipo decimal e atribui o valor de 10.99 a ela
decimal desconto = 0.15m; // declara uma variável do tipo decimal e atribui o valor de 15% de desconto a ela
decimal precoFinal = preco - (preco * desconto); // calcula o preço final com desconto e atribui o resultado à variável precoFinal
Console.WriteLine("Preço final: " + precoFinal.ToString("C")); // imprime o preço final em formato de moeda
```

```csharp
bool: é um tipo booleano que representa valores lógicos verdadeiro ou falso.
EX:
bool isSunny = true; 
bool isRainy = false;
```

```csharp
char: é um tipo de caractere usado para representar 
um único caractere, como 'a', 'b', 'c', etc.
```

```csharp
string: é um tipo de cadeia de caracteres usado para
representar uma sequência de caracteres, como "Olá mundo!".
```

```csharp
byte: é um tipo inteiro sem sinal que varia de 0 a 255. É usado para representar
 valores pequenos, como dados binários ou bytes de arquivos.
```

```csharp
short: é um tipo inteiro que varia de -32.768 a 32.767. É usado para 
representar números inteiros menores que o tipo int.
short valorCurto = 1234;
```



```csharp
long: é um tipo inteiro que varia de -9.223.372.036.854.775.808 
a 9.223.372.036.854.775.807. É usado para representar números inteiros
maiores que o tipo int.
long numeroLongo = 1234567890L; // declara uma variável do tipo long e atribui o valor de 1234567890 a ela
```

## operadores aritméticos:

- Adição (+): usado para somar dois valores
- Subtração (-): usado para subtrair um valor de outro
- Multiplicação (*): usado para multiplicar dois valores
- Divisão (/): usado para dividir um valor por outro
- Módulo (%): usado para obter o resto da divisão entre dois valores

## operadores comparação

- Igualdade (==): retorna verdadeiro se os valores comparados forem iguais
- Desigualdade (!=): retorna verdadeiro se os valores comparados forem diferentes
- Maior que (>): retorna verdadeiro se o valor da esquerda for maior que o valor da direita
- Maior ou igual que (>=): retorna verdadeiro se o valor da esquerda for maior ou igual ao valor da direita
- Menor que (<): retorna verdadeiro se o valor da esquerda for menor que o valor da direita
- Menor ou igual que (<=): retorna verdadeiro se o valor da esquerda for menor ou igual ao valor da direita

## operadores atribuição

| Operador | Descrição |
| --- | --- |
| = | Atribui o valor da direita à variável da esquerda. |
| += | Atribui a soma da variável da esquerda e o valor da direita à variável da esquerda. |
| -= | Atribui a diferença da variável da esquerda e o valor da direita à variável da esquerda. |
| *= | Atribui o produto da variável da esquerda e o valor da direita à variável da esquerda. |
| /= | Atribui o quociente da variável da esquerda e o valor da direita à variável da esquerda. |
| %= | Atribui o resto da divisão da variável da esquerda e o valor da direita à variável da esquerda. |
| <<= | Desloca a variável da esquerda para a esquerda pelo número de posições especificado na variável da direita e atribui o resultado à variável da esquerda. |
| >>= | Desloca a variável da esquerda para a direita pelo número de posições especificado na variável da direita e atribui o resultado à variável da esquerda. |
| &= | Atribui o resultado da operação AND (E lógico) entre a variável da esquerda e o valor da direita à variável da esquerda. |
| ^= | Atribui o resultado da operação XOR (OU exclusivo) entre a variável da esquerda e o valor da direita à variável da esquerda. |
| |= | Atribui o resultado da operação OR (OU lógico) entre a variável da esquerda e o valor da direita à variável da esquerda. |

## operadores lógico

1. && (E lógico): Retorna verdadeiro se ambas as expressões forem verdadeiras.
2. || (OU lógico): Retorna verdadeiro se pelo menos uma das expressões for verdadeira.
3. ! (Negação lógica): Retorna verdadeiro se a expressão for falsa.

## Tipos de conversões 

## conversão implícita

 Em C# é uma forma automática de converter um tipo de dados em outro tipo compatível sem a necessidade de realizar uma conversão explícita. Isso pode ajudar a simplificar o código e melhorar a legibilidade, mas é importante estar ciente dos possíveis problemas de perda de dados.

```jsx
int meuInt = 10;
long meuLong = meuInt; // conversão implícita de int para long
```

## conversão  explícitas

C# é uma forma manual de converter um tipo de dados em outro tipo compatível, quando a conversão implícita não é possível. Isso é feito usando o operador de conversão explícita "(tipo de dados de destino)valor" para realizar a conversão. É importante estar ciente dos possíveis problemas de perda de dados e precisão ao realizar conversões explícitas.

```csharp
double meuDouble = 123.45;
int meuInt = (int) meuDouble; // conversão explícita de double para int
```

## método Parse()

Em C# é um método que permite converter uma string em um valor numérico, como int, double, float, long, entre outros. Esse método é especialmente útil quando você precisa extrair valores de entrada do usuário em forma de string e convertê-los para tipos numéricos para manipulação dentro do programa.

```csharp

tipoDeDado valorConvertido = tipoDeDado.Parse(string valorOriginal);
```

## O método TryParse()

é um método em C# que permite converter uma string em um valor numérico, sem lançar uma exceção em caso de falha na conversão. Em vez disso, ele retorna um valor booleano indicando se a conversão foi bem-sucedida ou não, e armazena o valor convertido em uma variável de saída se a conversão for bem-sucedida.

```jsx
string minhaString = "123";
int meuInteiro;
bool sucesso = int.TryParse(minhaString, out meuInteiro);
```

## O método Convert()

é uma função de conversão de dados em C#. Ela é usada para converter um tipo de dados em outro tipo de dados. O método é capaz de converter tipos de dados primitivos, tipos de dados personalizados e tipos de dados enumerados. É menos flexível do que o método Parse() ou TryParse(), pois não pode lidar com exceções ou retornar valores nulos.

```csharp
Convert.ToTipoDeDado(valorOriginal);
```
