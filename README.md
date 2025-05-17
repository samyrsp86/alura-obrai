ObrAÍ: Sua Obra Sob Controle. E o Leão Também.



💡 Sobre o Projeto

O Obraí é uma solução que utiliza IA para simplificar o gerenciamento de obras residenciais. Ele auxilia no acompanhamento dos gastos por categoria e identifica os valores que podem ser incorporados ao valor do imóvel no Imposto de Renda.



🎯 Problema 

Reformar um imóvel pode ser um processo complexo e desafiador. Proprietários frequentemente enfrentam dificuldades para:

Acompanhar os gastos de forma organizada.
Saber exatamente onde o dinheiro está sendo investido.
Aproveitar os benefícios fiscais da reforma, como a incorporação do valor empenhado em obras e benfeitorias no imóvel quando da declaração anual de Imposto de Renda, devido à falta de organização das notas fiscais.


🚀 Solução 

O ObrAÍ oferecerá uma maneira fácil de gerenciar os gastos da sua obra. Inicialmente, o aplicativo funcionará através de uma conversa com um agente de Inteligência Artificial do Gemini. O fluxo será:

1. Enviar a URL da Nota Fiscal. 

2. Receber a análise dos gastos, com classificação por categoria e indicação dos itens dedutíveis no IR.

3. Confirmar se os dados estão corretos.



⚙️ Funcionalidades Atuais (Desafio Alura/Google)

1. Interpretar as notas fiscais (fornecidas via arquivos no GitHub)
2. Classificar os itens nas seguintes categorias:
Alvenaria
Hidráulica
Elétrica
Marcenaria
Móveis
Pintura
Eletrodomésticos
Outras despesas
3. Determinar se cada item é incorporável ou não ao IR.
4. Pedir a confirmação se a interpretação foi correta.
5. Corrigir com os dados fornecidos pelo usuário, caso alguma informação esteja errada.
6. Devolver os resultados em formato JSON.


💡 Próximos Passos 

O ObrAÍ está em desenvolvimento e os próximos passos incluem:

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

3. Instale as dependências necessárias (listadas dentro do código).

4. Utilize as imagens das notas fiscais disponívis na pasta do projeto.

5. Execute o script principal: `obrAI.ipynb`.

6. Utilize o endereço direto da imagem das notas fiscais (ex.:https://raw.githubusercontent.com/samyrsp86/alura-obrai/refs/heads/main/NF1_SD.png)

7. O resultado da análise estará em um texto compatível com um arquivo JSON.



📄 Exemplo de Saída (JSON)

```json { "nota_fiscal_1.jpg": [ { "item": "Saco de cimento 50kg", "categoria": "Alvenaria", "incorporavel_ir": true }, { "item": "Torneira cromada", "categoria": "Hidráulica", "incorporavel_ir": false } ], "nota_fiscal_2.png": [ // Outros itens e notas fiscais ] } 
