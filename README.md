# Elevador Digital de 3 Andares

### Projeto de Circuitos Digitais | UFMA | 2026.2

![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)
![Plataforma](https://img.shields.io/badge/Simulador-Logisim-blue)
![Disciplina](https://img.shields.io/badge/Disciplina-Circuitos%20Digitais-green)
![Instituição](https://img.shields.io/badge/Institui%C3%A7%C3%A3o-UFMA-red)

## 1. Sobre o projeto

Este repositório apresenta o desenvolvimento de um **sistema digital de controle de elevador de três andares**, elaborado como projeto acadêmico da disciplina **EECP0002 - Circuitos Digitais**, da Universidade Federal do Maranhão (UFMA), no semestre 2026.2.

O projeto tem como finalidade aplicar conceitos de lógica combinacional e sequencial na construção de um sistema capaz de representar o funcionamento de um elevador, utilizando o simulador **Logisim**.

A proposta contempla o desenvolvimento da lógica de controle, a representação dos estados do sistema, a simulação dos circuitos e a realização de testes para verificar seu funcionamento.

## 2. Objetivos

### Objetivo geral

Projetar e simular um sistema digital de controle de elevador de três andares, aplicando os fundamentos de circuitos digitais estudados durante a disciplina.

### Objetivos específicos

- Desenvolver a lógica de controle do elevador.
- Representar digitalmente os três andares.
- Implementar o processamento das solicitações de deslocamento.
- Estudar e aplicar portas lógicas, circuitos combinacionais e sequenciais.
- Utilizar elementos de memória para representar os estados do sistema.
- Simular e testar o funcionamento do circuito no Logisim.
- Documentar as etapas de desenvolvimento e os resultados obtidos.

## 3. Funcionamento proposto

O sistema deverá representar um elevador que opera entre três andares:

- **Andar 0:** térreo.
- **Andar 1:** primeiro andar.
- **Andar 2:** segundo andar.

O controle digital deverá permitir a seleção de um andar de destino e determinar o deslocamento necessário a partir da posição atual.

A lógica deverá considerar as seguintes situações:

1. Recebimento de uma solicitação de andar.
2. Identificação da posição atual do elevador.
3. Determinação da direção do deslocamento.
4. Atualização do estado do elevador.
5. Identificação da chegada ao andar solicitado.
6. Interrupção do movimento ao atingir o destino.

O comportamento será desenvolvido e validado progressivamente durante as simulações.

## 4. Fundamentos teóricos

O projeto utiliza conceitos abordados na disciplina de Circuitos Digitais, incluindo:

| Conceito | Aplicação no projeto |
|---|---|
| Álgebra de Boole | Definição das condições de controle |
| Portas lógicas | Implementação das operações lógicas |
| Circuitos combinacionais | Processamento das entradas e decisões |
| Flip-flops | Armazenamento de informações de estado |
| Circuitos sequenciais | Controle das mudanças de estado |
| Codificação binária | Representação dos andares |
| Máquinas de estados | Modelagem do funcionamento do elevador |

A implementação efetiva de cada elemento será documentada conforme o desenvolvimento do circuito.

## 5. Ferramentas utilizadas

- **Logisim:** desenvolvimento e simulação de circuitos digitais.
- **GitHub:** versionamento, armazenamento e colaboração.
- **Git:** controle de versões do projeto.
- **Documentação técnica:** registro dos requisitos, testes e resultados.

## 6. Estrutura do repositório

```text
elevador-digital-3-andares/
|
|-- circuito/
|   |-- elevador.circ
|
|-- documentacao/
|   |-- TAP.pdf
|   |-- relatorio-execucao.pdf
|
|-- cronograma/
|
|-- imagens/
|
|-- testes/
|
|-- README.md
```

A estrutura representa a organização planejada. Os arquivos serão adicionados conforme sua elaboração e validação.

## 7. Como executar a simulação

1. Instale uma versão compatível do Logisim.
2. Faça o download do arquivo `.circ` disponível na pasta `circuito`.
3. Abra o Logisim.
4. Selecione **File > Open**.
5. Escolha o arquivo do circuito.
6. Utilize as entradas disponíveis para testar as solicitações de andares.
7. Observe o comportamento das saídas e dos estados do sistema.

**Observação:** as instruções específicas de operação serão atualizadas após a conclusão da implementação.

## 8. Etapas de desenvolvimento

O projeto está organizado nas seguintes macroetapas:

- **Iniciação:** definição do tema, escopo e elaboração do Termo de Abertura do Projeto (TAP).
- **Planejamento:** levantamento dos requisitos, estudo da lógica digital e organização das atividades.
- **Execução:** elaboração dos circuitos, implementação no Logisim e preparação dos componentes físicos, quando aplicável.
- **Monitoramento e controle:** acompanhamento do desenvolvimento, realização de testes e correções.
- **Encerramento:** validação final, organização da documentação e apresentação do projeto.

**Período previsto de desenvolvimento:** agosto a dezembro de 2026.

**Data prevista de conclusão:** 01/12/2026.

## 9. Equipe de desenvolvimento

Projeto desenvolvido por estudantes da Universidade Federal do Maranhão (UFMA).

| Integrante | Instituição |
|---|---|
| Ana Patrícia Braga Garros | UFMA |
| Ana Julia Morais Ribeiro Alencar | UFMA |
| Samara Santos Viegas | UFMA |
| Pedro Luís dos Santos Souza | UFMA |
| João Marcelo Privado Simas | UFMA |

**Professor orientador:** Luiz Henrique Neves Rodrigues.

**Disciplina:** EECP0002 - Circuitos Digitais.

**Semestre:** 2026.2.

## 10. Referências

TOCCI, Ronald J.; WIDMER, Neal S.; MOSS, Gregory L. **Sistemas Digitais: Princípios e Aplicações**. 11. ed. São Paulo: Pearson, 2011.

IDOETA, Ivan V.; CAPUANO, Francisco G. **Elementos de Eletrônica Digital**. 41. ed. São Paulo: Érica, 2012.

FLOYD, Thomas L. **Sistemas Digitais: Fundamentos e Aplicações**. 9. ed. Porto Alegre: Bookman, 2007.

## 11. Considerações finais

O desenvolvimento do elevador digital de três andares busca integrar conhecimentos teóricos e práticos de circuitos digitais por meio da construção de um sistema de controle.

A utilização do Logisim permite representar e analisar o comportamento dos circuitos, enquanto o GitHub possibilita documentar a evolução do projeto e organizar o trabalho colaborativo.

Os resultados finais, limitações e melhorias identificadas serão registrados após a conclusão dos testes.

---

**Universidade Federal do Maranhão (UFMA)**

**Circuitos Digitais | Semestre 2026.2**

**Projeto acadêmico para fins educacionais.**
