ObrAÍ: Sua Obra Sob Controle. E o Leão Também.



💡 Sobre o Projeto

O Obraí é uma solução que utiliza IA para simplificar o gerenciamento de obras residenciais. Ele auxilia no acompanhamento dos gastos por categoria e identifica os valores que podem ser deduzidos no Imposto de Renda.



🎯 Problema 

Reformar um imóvel pode ser um processo complexo e desafiador. Proprietários frequentemente enfrentam dificuldades para:

Acompanhar os gastos de forma organizada.
Saber exatamente onde o dinheiro está sendo investido.
Aproveitar os benefícios fiscais da reforma, como a dedução no Imposto de Renda, devido à falta de organização das notas fiscais.


🚀 Solução 

O ObrAÍ oferece uma maneira fácil de gerenciar os gastos da sua obra. O serviço funcionará via WhatsApp. O fluxo será:

1. Adicionar o ObrAÍ como contato.

2. Enviar fotos ou subir arquivos das notas fiscais.

3. Receber a análise dos gastos, com classificação por categoria e indicação dos itens dedutíveis no IR.



A IA do ObrAÍ irá:

Interpretar as notas fiscais.
Classificar os itens nas seguintes categorias:
Alvenaria
Hidráulica
Elétrica
Marcenaria
Móveis
Pintura
Eletrodomésticos
Outras despesas
Determinar se cada item é incorporável ou não ao IR.
Armazenar os dados e fornecer relatórios sobre os gastos totais por categoria e o valor dedutível.


⚙️ Funcionalidades Atuais (Desafio Alura/Google)

Para esta entrega inicial do desafio, o Obraí oferece as seguintes funcionalidades:

Análise de Notas Fiscais: A IA analisa imagens de notas fiscais (fornecidas via arquivos no GitHub).
Classificação de Itens: Os itens são classificados por categoria (Alvenaria, Hidráulica, etc.).
Identificação para o IR: A IA indica se um item é incorporável ou não ao Imposto de Renda.
Saída em JSON: Os resultados da análise são gerados em formato JSON.


Observação: Esta versão não inclui integração com o WhatsApp, upload direto de imagens ou cálculos de totais.



💡 Próximos Passos 

O ObrAÍ está em desenvolvimento, e os próximos passos incluem:

Integração com a API do WhatsApp.
Implementação do upload de fotos de notas fiscais.
Cálculo automático dos gastos totais e do valor dedutível.


🎯 Público-Alvo

Primário: Proprietários de imóveis que estão realizando reformas.
Secundário: Arquitetos e empreiteiros que oferecem serviços de acompanhamento de obras.


🛠️ Como Usar (Versão Desafio) 

Para executar esta versão do ObrAÍ, siga estas etapas:

1. Clone este repositório do GitHub.

2. Certifique-se de ter o Python 3.x instalado.

3. Instale as dependências necessárias (se houver) usando `pip install -r requirements.txt` (se aplicável).

4. Coloque as imagens das notas fiscais na pasta `data/notas_fiscais` (crie a pasta, se necessário).

5. Execute o script principal: `obrAI.ipynb` (ou o nome do script que você usa para executar o código).

6. O resultado da análise estará em um texto compatível com um arquivo JSON.



📄 Exemplo de Saída (JSON)

```json { "nota_fiscal_1.jpg": [ { "item": "Saco de cimento 50kg", "categoria": "Alvenaria", "incorporavel_ir": true }, { "item": "Torneira cromada", "categoria": "Hidráulica", "incorporavel_ir": false } ], "nota_fiscal_2.png": [ // Outros itens e notas fiscais ] } 
