# 🧠 Perceptron – Atividade de Redes Neurais

Este projeto apresenta uma **implementação manual e didática** do algoritmo do **Perceptron**, respeitando as restrições de não utilizar bibliotecas de machine learning automáticas. O trabalho foi desenvolvido em **Python** com apoio de `numpy` (para arrays) e `matplotlib` (para visualização).

## 📚 Conteúdo Abordado

O notebook (`perceptron.ipynb`) contempla os seguintes tópicos:

### ## Estrutura Básica do Perceptron
- Conceitos de entradas, pesos, bias, função somatória e função de ativação
- Representação gráfica da estrutura do neurônio

### ## Implementação Manual
- Multiplicação vetorial sem `np.dot()` (uso de `for` explicitamente)
- Função de ativação: degrau unitário
- Cálculo de erro absoluto
- Atualização manual dos pesos e bias com base no erro
- Controle de taxa de aprendizado

### ## Funcionamento do Algoritmo
- Inicialização dos pesos
- Treinamento por épocas
- Critério de parada por erro ou número de épocas

### ## Aplicações Práticas
- Problemas lógicos **AND** e **OR**
- Treinamento completo com visualizações gráficas
- Fronteiras de decisão explicadas e desenhadas

### ## Limitações: O Caso XOR
- Demonstração gráfica e experimental da **incapacidade do Perceptron** de resolver o problema XOR
- Discussão teórica sobre a limitação de modelos lineares
- Contextualização histórica do surgimento de redes multicamadas (MLP)

## 🛠 Ambiente

O projeto pode ser executado em um ambiente Conda. Use o arquivo `environment.yml` para criar o ambiente:

```bash
conda env create -f environment.yml
conda activate perceptron
```


Reconhecimentos e Direitos Autorais
@autor: João Pedro de Alcântara Lima
@contato: joao.alcantara@discente.ufma.br
@data última versão: 15/04/2025
@versão: 1.0
@Agradecimentos: Universidade Federal do Maranhão (UFMA), Professor Doutor
Thales Levi Azevedo Valente, e colegas de curso.
Copyright/License
Este material é resultado de um trabalho acadêmico para a disciplina
INTELIGÊNCIA ARTIFICIAL, sob a orientação do professor Dr. THALES LEVI
AZEVEDO VALENTE, semestre letivo 2024.2, curso Engenharia da Computação,
na Universidade Federal do Maranhão (UFMA). Todo o material sob esta licença é
software livre: pode ser usado para fins acadêmicos e comerciais sem nenhum custo.
Não há papelada, nem royalties, nem restrições de "copyleft" do tipo GNU. Ele é
licenciado sob os termos da Licença MIT, conforme descrito abaixo, e, portanto, é
compatível com a GPL e também se qualifica como software de código aberto. É de
domínio público. Os detalhes legais estão abaixo. O espírito desta licença é que você
é livre para usar este material para qualquer finalidade, sem nenhum custo. O único
requisito é que, se você usá-los, nos dê crédito.
Licenciado sob a Licença MIT. Permissão é concedida, gratuitamente, a qualquer
pessoa que obtenha uma cópia deste software e dos arquivos de documentação
associados (o "Software"), para lidar no Software sem restrição, incluindo sem
limitação os direitos de usar, copiar, modificar, mesclar, publicar, distribuir,
sublicenciar e/ou vender cópias do Software, e permitir pessoas a quem o Software
é fornecido a fazê-lo, sujeito às seguintes condições:
Este aviso de direitos autorais e este aviso de permissão devem ser incluídos em todas
as cópias ou partes substanciais do Software.
O SOFTWARE É FORNECIDO "COMO ESTÁ", SEM GARANTIA DE
QUALQUER TIPO, EXPRESSA OU IMPLÍCITA, INCLUINDO MAS NÃO SE
LIMITANDO ÀS GARANTIAS DE COMERCIALIZAÇÃO, ADEQUAÇÃO A UM
DETERMINADO FIM E NÃO INFRINGÊNCIA. EM NENHUM CASO OS
AUTORES OU DETENTORES DE DIREITOS AUTORAIS SERÃO
RESPONSÁVEIS POR QUALQUER RECLAMAÇÃO, DANOS OU OUTRA
RESPONSABILIDADE, SEJA EM AÇÃO DE CONTRATO, TORT OU OUTRA
FORMA, DECORRENTE DE, FORA DE OU EM CONEXÃO COM O
SOFTWARE OU O USO OU OUTRAS NEGOCIAÇÕES NO SOFTWARE.
Para mais informações sobre a Licença MIT: https://opensource.org/licenses/MIT
