 ## 📣 Hey!!

---

### Este repositório conterá minhas anotações dos conhecimentos obtidos sobre Python através da plataforma Descomplica.

---

#### PRIMEIROS PASSOS

O Python surgiu na década de 1990 e, embora já seja uma linguagem com bastante maturidade, ela só começou a ganhar notoriedade da década de 2010 em diante - momento em que a Inteligência Artificial (I.A.) começou a se tornar cada vez mais presente nas mais diversas aplicações, sejam elas web, mobile ou desktop.

Como o Python, desde sua concepção já trazia uma estrutura robusta voltada à I.A. e aprendizado de máquina por meio de bibliotecas específicas, a linguagem acabou por atender perfeitamente às necessidades de programadores que precisavam desenvolver aplicações inteligentes.

A linguagem é muito conhecida também por sua velocidade de execução - principalmente quando processada em ambiente local.

---

#### Em suma, mas não exclusivamente, Python é amplamente utilizada para:

Criação de aplicações baseadas em Inteligência Artificial;
Criação de aplicações que requeiram aprendizado de máquina, ou seja, softwares que aprendam padrões com o passar do tempo, de forma a tomar decisões guiadas por decisões assertivas do passado;
Ciência e Análise de dados, provendo cenários preditivos para tomada de decisão a nível corporativo ou governamental;
Sites, lojas virtuais, sistemas que funcionem no padrão SAAS (Software As A Service) e qualquer outro tipo de aplicação que seja executada em browser (navegador);
Sistemas de automação residencial e/ou industrial;
Softwares embarcados, ou seja, aplicações que interajam diretamente com o hardware - os sistemas de automação são um bom exemplo disso;
Aplicativos Mobile (embora não seja a linguagem mais adequada para isso e, portanto, requeira alguns frameworks e camadas adicionais para funcionar da maneira esperada).

---

### Instalação e configuração do ambiente

Para se utilizar o Python em uma máquina local, é necessário preparar o ambiente de trabalho; isso consiste em seguir alguns passos:

Instalar o Python localmente em seu computador
Instalar uma IDE (Integrated Development Environment)
Configurar a IDE para reconhecer a sintaxe do Python e executá-la
Para fins didáticos, utilizaremos o ambiente com o Sistema Operacional (S.O.) Windows na versão 10, mas a mesma lógica se aplica a outras versões do SO ou ainda outros Sistemas Operacionais como Linux, Mac, Solaris, etc.

---

### Fazendo o download do Python

Você deverá acessar o site oficial, https://www.python.org, e acessar a guia de downloads. Recomendo que você verifique a versão atual e procure sempre instalar a versão “stable” (estável). Como a linguagem está em constante atualização, novas funções, recursos, bibliotecas, patches de segurança e outras manutenções, são adicionadas periodicamente.

---

Recomendo sempre que você utilize uma versão estável, ou seja, que já tenha sido validada e passado no “crivo” dos desenvolvedores, resolvendo todos os problemas (ou a maioria, ao menos) que aquela versão tenha.

Escolher uma versão em desenvolvimento, ainda que ela ofereça algumas vantagens como novos recursos e até mesmo a resolução de erros de versões anteriores, é um passo arriscado, uma vez que a versão em desenvolvimento pode gerar uma série de incompatibilidades que acabarão sendo mais danosas que o uso de uma versão com menos recursos. Em suma: use sempre a versão estável se quiser diminuir a dor de cabeça!

Ao fazer o download do Python, o processo de instalação é bem simples, mas atente para deixar assinalada a opção de “adicionar python.exe ao Path do sistema” conforme demonstra a Figura 1.

---

Para confirmar se a instalação ocorreu da forma esperada, você pode acessar o seu prompt de comando (Iniciar > Executar > [digite CMD e pressione ENTER]) e digitar o seguinte comando: py –version

---

### Instalando uma IDE

(IDE - AMBIENTE INTEGRADO DE DESENVOLVIMENTO)

O próximo passo é instalar a IDE que será seu ambiente de desenvolvimento. Você pode optar pela IDE de sua preferência, mas recomendo utilizar o VSCode (Visual Studio Code) da Microsoft que possui, além da integração com o Python mediante configuração, uma vastidão de extensões que auxiliarão ainda mais o processo de programação de suas aplicações.

O próximo passo é instalar a IDE que será seu ambiente de desenvolvimento. Você pode optar pela IDE de sua preferência, mas recomendo utilizar o VSCode (Visual Studio Code), que possui, além da integração com o Python mediante configuração, uma vastidão de extensões que auxiliarão ainda mais o processo de programação de suas aplicações.

Para instalar o VSCode, acesse https://code.visualstudio.com/ e clique no botão de download. A instalação é bastante trivial e, de forma similar ao Python, você precisará apenas ir avançando as etapas até a finalização.

Atente apenas ao peso do programa, pois o VSCode, embora seja mais leve que outras IDE’s, requer uma configuração mínima para que funcione de maneira adequada. Essas exigências podem ser verificadas no site oficial do software, no seguinte link: https://code.visualstudio.com/docs/supporting/requirements. 

Para analisar se a instalação do VSCode funcionou corretamente, basta abrir a aplicação em seu SO. Se o programa abrir corretamente então a instalação funcionou e você poderá partir para a configuração das extensões necessárias para iniciar a programação com Python.

---

Um Framework é formado por um conjunto classes implementadas em uma determinada linguagem de programação, que fornece recursos comuns já prontos, validados e testados, os quais podem ser usados para auxiliar o desenvolvimento de software, viabilizando maior eficiência na resolução dos problemas, otimização de recursos, e detecção de erros.

---

### Instalando as extensões

Uma extensão é um recurso extra, não-nativo, de uma aplicação. Por padrão, a IDE não saberá que sua intenção é trabalhar com Python a menos que você a informe disso; o primeiro passo é “avisá-la” que ela precisa compreender a linguagem Python e sua sintaxe.

Quando for criar um arquivo, sempre colocar .py no final (teste.py)

---

### Entendendo a arquitetura do Python

O Python é uma linguagem fracamente tipada (tipagem dinâmica) e interpretada. Esses dois termos se referem à forma como a linguagem é lida pelo processador (ou interpretador) de uma máquina. A “tipagem” se refere aos tipos de dados que uma variável pode assumir; já o termo “interpretada”, significa que a linguagem, via de regra, será executada por uma aplicação que interprete o código - motivo pelo qual ela tende a ser mais rápida que outras linguagens, ao menos com processos triviais que não requeiram loops altos.

---

### Explorando as variáveis

Variáveis, em programação, nada mais são que espaços na memória que podem ou não alocar determinados valores. Este “ou não”, refere-se a linguagens de tipagem forte, como o C, por exemplo. Ao se trabalhar com uma linguagem fortemente tipada, é necessário informar à memória que uma determinada variável terá um tipo específico (texto, número inteiro, número decimal, etc). A esse processo dá-se o nome de “declaração de variável”.

Essa declaração de variáveis, faz com que um espaço seja reservado na memória, possibilitando, em momento propício, alocar um dado no espaço reservado. Um detalhe importante sobre linguagens fortemente tipadas como o C, é a restrição de modificação de tipos. Se uma variável foi definida como sendo do tipo “inteiro”, ela será deste tipo até a finalização do programa.

Já com linguagens como o Python, fracamente tipadas, não há necessidade de se reservar um espaço na memória, ou seja, a declaração de variáveis é desnecessária. Por possuir uma tipagem dinâmica, uma mesma variável pode armazenar dados diversos, por exemplo, textos em um momento e números em outro momento, conforme demonstrado a seguir:

valor = “Python”

valor = 10

---

### Explorando as constantes

Constante é algo que não muda o seu valor ou seja é um elemento que assume um valor no ínicio e se mantem até a execução final de um algoritmo.

Geralmente utilizamos para conseguir apontar alguns tipos de dados específicos dentro da programação. 

EXEMPLO: MAIORIDADE = 18

Diferente de outras linguagens, o Python, por ter uma tipagem dinâmica, não utiliza o conceito de constantes, ou seja, ao se determinar uma variável é possível modificar seu valor a qualquer momento. É importante salientar que isso é válido até a versão atual da linguagem e que a qualquer momento essa informação pode ser modificada, caso a comunidade de desenvolvedores lance uma versão que contraponha essa regra.

Caso você opte por determinar uma variável cujo valor NUNCA deva ser alterado, você pode escrevê-la em maiúsculo. Isso não impedirá sua modificação, mas dará um alerta visual a quem estiver manipulando o código, sinalizando que aquela variável é diferente das demais.

---

### Regras básicas de variáveis

Basicamente, as variáveis são elementos capazes de armazenar valores e podem ter o nome que você desejar. Algumas regras, entretanto, devem ser respeitas, como:

Variáveis não podem iniciar com números
Variáveis não podem ter espaço
Variáveis não podem ter caracteres especiais (!, @, #, $, etc) TODOS OS CARACTÉRES QUE NÃO SÃO LETRAS OU NÚMEROS SÃO CARACTÉRES ESPECIAIS (EXCETO ESPAÇO, ELE É APENAS ESPAÇO).
Para nomes de variáveis que contenham, conceitualmente, duas ou mais palavras, utilizamos o conceito de Camel Case, escrevendo as iniciais, a partir da segunda palavra, em maiúsculo, por exemplo, uma variável para armazenar um nome do usuário, poderia ser descrita como: nomeDoUsuario

---

Acessando a documentação oficial você obtém respostas diretamente da fonte e consegue esclarecer as principais dúvidas sobre sintaxe, semântica, estruturas, funções, etc.

A documentação oficial do Python fica disponível no seguinte link: https://www.python.org e a parte legal: é gratuita e você pode acessar de qualquer lugar.

Códigos utilizados na disciplina no link a seguir: https://github.com/FaculdadeDescomplica/Python
