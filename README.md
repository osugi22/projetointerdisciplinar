# README.md

## 1. Descrição do Projeto
O **Sistema de Carteira de Investimentos** é uma aplicação desenvolvida em linguagem C estruturada em múltiplos arquivos, voltada para o gerenciamento e acompanhamento financeiro de ativos. O sistema permite ao usuário cadastrar investimentos, visualizar a carteira completa, acompanhar a rentabilidade individual de cada ativo, calcular o valor total acumulado e a rentabilidade geral da carteira, mantendo a persistência automática dos dados em disco por meio de arquivos de texto.

## 2. Público-Alvo
* Estudantes de programação e algoritmos que buscam compreender a estruturação de projetos em C com múltiplos módulos.
* Investidores iniciantes que desejam uma ferramenta leve, executável via terminal/console, para monitorar ativos e rentabilidades de forma prática.

## 3. Funcionalidades
* **Cadastrar Ativo:** Permite registrar um novo ativo informando nome, categoria, quantidade de cotas/unidades, preço de compra e preço atual.
* **Listar Carteira:** Exibe todos os ativos cadastrados, detalhando suas informações, o valor atual investido por ativo e a rentabilidade individual percentual.
* **Valor Total da Carteira:** Calcula e exibe o montante financeiro total atual acumulado com base nos preços de mercado atuais.
* **Rentabilidade Geral:** Apresenta o ganho ou perda percentual geral de toda a carteira em relação ao custo total de aquisição.
* **Persistência de Dados (Carregar e Salvar):** O sistema salva automaticamente as informações em um arquivo de texto (`data/carteira.txt`) a cada novo cadastro e as recupera ao iniciar.

## 4. Tecnologias Utilizadas
* Linguagem C (padrão C99)
* Compilador GCC / Dev-C++
* Manipulação de Arquivos e Ponteiros em C

## 5. Requisitos Mínimos
* Um computador com sistema operacional Windows (ou ambiente compatível com compilação GCC).
* IDE ou ambiente de desenvolvimento compatível com C (como Dev-C++, Code::Blocks ou VS Code com MinGW).
* O diretório do projeto deve conter a estrutura de pastas adequada (como a pasta `data/` para armazenamento do arquivo de salvamento).

## 6. Instruções para Execução
1. Abra o arquivo de projeto do ambiente (`Carteira de Investimentosv2.dev`) no Dev-C++ ou abra a pasta no seu ambiente de preferência.
2. Certifique-se de que os arquivos fontes (`main.c`, `funcoes.c`, `modulo.c`, `funcoes.h` e `modulo.h`) estão no diretório de compilação.
3. Compile e execute o projeto utilizando o Makefile integrado ou acionando a compilação diretamente pela IDE.
4. Interaja com o menu exibido no console escolhendo as opções numéricas de 1 a 5.

## 7. Desenvolvedores
* Arthur Osugi
* Erik Dias
* Ruan Pablo
* Michel Zaghi
