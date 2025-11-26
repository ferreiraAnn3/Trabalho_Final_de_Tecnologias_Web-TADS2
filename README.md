# Trabalho Final de Tecnologias Web-TADS2 | Por Anne Beatriz Valle Ferreira

**Projeto Natal Solidário | Instituto Federal do Paraná - Campus Telêmaco Borba (Instituição Educacional).**

O site foi desenvolvido para uma campanha solidária e comunitária para facilitar a arrecadação de doações e procura por voluntários para sua realização.


## 1. Processo de Desenvolvimento e Customizações
O projeto foi desenvolvido a partir do template *Agency* do Start Bootstrap. O objetivo foi transformar o layout  em uma página funcional e acolhedora para uma campanha comunitária de Natal.

# *Customizações Realizadas*
*Substituição das cores*: As cores originais foram todas substiruídas por uma paleta natalina (Vermelho, Verde, Creme).

*Estrutura:* Alteração das seções anteriores originais por:
    * *Cartinhas* ;
    * *Fábrica de Sorrisos*;
    * *Nossa História*.
**Estilização:** No uso do CSS a IA me ensinou a usar o (`!important`) para forçar estilos nos botões e nas cores de fundo, sem ter que mexer e perder muito tempo no código nativo do template, além da troca de ícones pela biblioteca Bootstrap Icons.

## 2. Uso de Formulários
Houve a implementação de dois formulários funcionais com validação de JavaScript:

1.  **Formulário "Doe Agora":**
    * Para arrecadação das doações de itens materiais (Roupas, Alimentos, Brinquedos).
    * Campos solicitados: Nome, Telefone, Bairro, Tipo de Doação e Mensagem (para especificação da doação).
    * 
2.  **Formulário "Seja um Herói":**
    * Para Inscrição de voluntários para ajudar com as doações e no dia da campanha.
    * Interatividade: Ele só é ativado qunado o usuário  clicar nos botões dos modais ("Quero Participar").

Os dois formulários possuem validação que impede o envio de campos vazios e verifica se o número do telefone possui o tamanho correto pré-definido no JS.*

## 3. Apoio da Inteligência Artificial
A IA Gemini foi utilizada como ferramenta e tutora durante o desenvolvimento :
**Correção de Sintaxe:** Identificação de erros no HTML (no caminho dos botões).
**Lógica JavaScript:** Explicação do script que conecta os botões dos Modais aos formulário de inscrição (seleção automática).
**Design:** Sugestões para a paleta de cores e icones.

## 4. Tecnologias e Créditos
* **Base:** [Agency - Start Bootstrap](https://startbootstrap.com/theme/agency)
* **Framework:** Bootstrap 5
* **Imagens:** Google Imagens (uso educacional) e Bootstrap Icons.
