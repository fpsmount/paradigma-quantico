# ⚙️ Computação e Paradigma Quântico

## 📜 Descrição
Este repositório contém o conteúdo desenvolvido dentro do seminário de Paradigmas de Linguagens de Programação no 6º Semestre de Ciência da Computação no UDF.  
Nosso grupo ficou responsável pelo Paradigma Quântico, e nossa linguagem utilizada foi Q#.

## 👥 Participantes
- 👩‍🏫 Profesora Kadidja Valéria
- 👤 Dimitri Monteiro | RGM: 29601380
- 👤 Gabrielly Silva | RGM: 30511640
- 👤 Augusto Liberato | RGM: 30238722
- 👤 Saulo Silva | RGM: 30372607
- 👤 Julio | RGM: 32156308

## 📅 Data da Apresentação
- Paradigma Quântico (Grupo Rosa Claro): 11/11/2024

## 📘 Paradigma Quântico
- 📖 **Definição**: Programação quântica é um paradigma de computação que se baseia nos princípios da mecânica quântica, como superposição e emaranhamento, para resolver problemas de forma que computadores clássicos não conseguem. Este paradigma é ideal para problemas que exigem processamento em grande escala, como fatoraçãõ de números grandes e simulação de sistemas complexos.
- 🔄 **Evolução**: A computação quântica começou a ganhar forma na década de 1980 com as ideias de Richard Feynman e David Deutsch. Peter Shor, nos anos 1990, demonstrou que um computador quântico poderia fatoraizar números de forma eficiente, marcando um ponto de virada na pesquisa com o algoritmo de Shor.
- 🔑 **Características**:
    - **Superposição**: Qubits podem representar 0 e 1 simultaneamente, permitindo computação paralela.
    - **Emaranhamento**: Estado de qubits que permanecem correlacionados de tal maneira que a medição de um afeta o estado do outro instantaneamente.
    - **Interferência Quântica**: Utilizada para otimizar a probabilidade de soluções corretas em algoritmos quânticos.
- ⚖️ **Vantagens e Desvantagens**:
    - *Vantagens*: Possibilidade de resolver problemas complexos de forma exponencialmente mais rápida, avanços em criptografia, e simulações de fenômenos quânticos.
    - *Desvantagens*: Tecnologia ainda em desenvolvimento, desafios de estabilidade e correção de erros, além de alto custo e necessidade de infraestrutura especializada.
- 📌 **Casos de Uso**: Algoritmos de otimização, simulação de moléculas e sistemas físicos, criptografia e segurança, e aprendizado de máquina.

## 💻 Q#
- 📜 **História**: Q# é uma linguagem de programação desenvolvida pela Microsoft, lançada em 2017 como parte do Microsoft Quantum Development Kit, para facilitar o desenvolvimento de algoritmos quânticos e simulações.
- 👨‍🔬 **Criadores**: Criada pela equipe da Microsoft Quantum, com o objetivo de tornar a programação quântica mais acessível a desenvolvedores e pesquisadores.
- 🖼️ **Logotipo**: Geralmente representado com o símbolo 'Q#' e elementos que refletem a interseção da computação e da física quântica.
- 🛠️ **Estrutura de Programas**: Q# é uma linguagem projetada para descrever operações e funções quânticas. Ela se integra bem com linguagens de controle clássicas, como Python e C#, para criar aplicações híbridas que combinam a computação clássica e quântica.
- 🔍 **Casos de Uso Típicos**:
    - *Desenvolvimento de Algoritmos Quânticos*: Implementação de algoritmos como o de Shor para fatoração e o de Grover para busca em grandes bases de dados.
    - *Simulação de Fenômenos Quânticos*: Utilizado para simulações de comportamento quântico em experimentos.
    - *Educação e Aprendizado*: Serve como ferramenta de ensino e exploração de conceitos de mecânica quântica em um contexto computacional.

## 📝 Sintaxe e Semântica de Programas em Q#
- **Portas Quânticas**: Operações como `H` (Hadamard), `CNOT`, e `Rz` são utilizadas para manipulação de qubits em superposição e emaranhamento.
- **Medidas**: Q# permite medir qubits para colapsar seus estados em `0` ou `1` e registrar esses valores para processamento posterior.
- **Estruturas de Controle**: Inclui loops e condicionais que permitem a execução de operações quânticas controladas de acordo com os resultados de medições.
- **Funções e Operações**: O código em Q# é dividido em funções clássicas (sem efeitos quânticos) e operações (que atuam sobre qubits).

Com isso, Q# se destaca como uma ferramenta poderosa para explorar a programação e simulação quântica, facilitando a criação de soluções para problemas complexos e avançando o desenvolvimento de algoritmos quânticos.

## 🔗 Links Úteis

- **Apresentação:** [Genially](https://view.genially.com/672d42046bbaf38bf84741da/presentation-computacao-quantica)
- **Kahoot:** [Kahoot](https://create.kahoot.it/share/haskell-e-paradigma-funcional/fdbaa161-a72e-4975-949f-c62c493b43f6)
- **Livro de Computação Quântica:** [Site](https://profmcruz.wordpress.com/wp-content/uploads/2017/08/quantum-computation-and-quantum-information-nielsen-chuang.pdf)

## 📚 Referências sobre o Paradigma Quântico
- [Quantum Computing for Computer Scientists - Noson S. Yanofsky, Mirco A. Mannucci](https://www.cambridge.org/core/books/quantum-computing-for-computer-scientists/0C0EDE7FC75AF9249A292317FC6C2D14)
- [IBM Quantum Experience](https://quantum-computing.ibm.com/) - Plataforma de programação quântica com tutoriais e exemplos práticos.
- [Microsoft Quantum Development Kit e Q#](https://learn.microsoft.com/en-us/azure/quantum/overview-what-is-qsharp-and-qdk) - Documentação oficial sobre a linguagem Q# e o kit de desenvolvimento quântico da Microsoft.
- [Quantum Computing Report](https://quantumcomputingreport.com/) - Notícias e análises sobre avanços em computação quântica e empresas da área.
- [Nature - Quantum Computing](https://www.nature.com/subjects/quantum-computing) - Artigos acadêmicos e revisões sobre computação quântica publicados na revista científica *Nature*.
- [Quanta Magazine - Quantum Computing](https://www.quantamagazine.org/tag/quantum-computing/) - Artigos e reportagens detalhadas sobre avanços e conceitos em computação quântica.
- [Peter Shor e Algoritmo de Fatoração Quântica](https://doi.org/10.1137/S0097539795293172) - Publicação original de Peter Shor sobre seu algoritmo de fatoração eficiente em computadores quânticos.
- [Qiskit - Abertura de Código IBM](https://qiskit.org/) - Framework de código aberto para o desenvolvimento de programas quânticos.
- [Quantum Computing: A Gentle Introduction](https://dl.acm.org/doi/10.5555/1207375) - Livro que oferece uma introdução acessível aos conceitos fundamentais da computação quântica.
- [Exploring Quantum Algorithms with Q#](https://learn.microsoft.com/en-us/samples/browse/?products=qsharp) - Exemplos de algoritmos implementados em Q# para entender a lógica de programação quântica.
- [Quantum Programming with Q#](https://arxiv.org/abs/1803.00652) - Artigo sobre a linguagem Q# e sua aplicação em programas quânticos.
- [Simulação de Algoritmos Quânticos - MIT OpenCourseWare](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-890-algorithms-for-quantum-computation-fall-2010/) - Materiais didáticos de um curso sobre algoritmos quânticos.
- [Superposição e Computação Quântica - Scientific American](https://www.scientificamerican.com/article/quantum-computing-explained/) - Explicação de conceitos como superposição e emaranhamento.
- [Quantum Computing Primer - Caltech](http://www.theory.caltech.edu/people/preskill/ph229/) - Curso online de John Preskill sobre fundamentos de computação quântica.
- [Quantum Computing and Quantum Information - Michael Nielsen e Isaac Chuang](https://www.cambridge.org/core/books/quantum-computation-and-quantum-information/3E5B4E6316B28C0D54E25AFBC5C8E889) - Considerado um dos livros mais completos sobre computação quântica e teoria de informação.
- [Blog da Microsoft sobre Computação Quântica](https://cloudblogs.microsoft.com/quantum/) - Atualizações e artigos sobre as iniciativas da Microsoft em computação quântica.
- [Quantum Algorithm Zoo - Stephen Jordan](https://quantumalgorithmzoo.org/) - Repositório abrangente de algoritmos quânticos categorizados por tipo e aplicação.
- [Simulador Quântico - Azure Quantum](https://azure.microsoft.com/en-us/products/quantum/) - Ferramentas para simulação e execução de programas quânticos na plataforma Azure.
