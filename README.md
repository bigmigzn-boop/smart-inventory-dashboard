# Otimização do Controle de Insumos na Planta Piloto – Kenvue

Durante meu contrato na Planta Piloto da Kenvue, fui responsável pelo controle de insumos das áreas da fábrica, incluindo: Escritório, Engenheirados, Clinical, Supply (Amostra para Cadastro), Formulados e Depósito.
Inicialmente, todo o processo era realizado manualmente — papel e caneta — o que tornava a análise de estoque lenta, suscetível a erros e pouco eficiente.
Percebendo essa limitação, tomei a iniciativa de modernizar o processo criando uma planilha automatizada no Excel, utilizando fórmulas como:
Excel= IF(D3<B3, "Abaixo do estoque", IF(D3<=B3+1, "Ficar Atento", "OK"))
Também apliquei formatação condicional, permitindo uma visualização rápida e clara dos níveis de estoque. Isso tornou o acompanhamento muito mais eficiente e reduziu o tempo gasto em análises.
<img width="1067" height="422" alt="Screenshot 2026-03-04 125105" src="https://github.com/user-attachments/assets/3f4bb4e9-3dd7-4059-8a5d-bd6414116adc" />
<img width="800" height="475" alt="Screenshot 2026-03-04 125032" src="https://github.com/user-attachments/assets/22572c97-4690-4da5-8ae6-258b8829bb40" />



## Evolução do Processo
Apesar da melhoria, a conferência manual do estoque ainda exigia anotar tudo no papel para só depois transferir ao computador. Para otimizar ainda mais, desenvolvi uma segunda planilha, desta vez pensada para uso no celular.
Através de referências simples, como:
Excel= "'Ficha de Controle'!B2Show" 
Passei a inserir as quantidades diretamente pelo smartphone durante as contagens, eliminando a necessidade de papel e agilizando significativamente o processo de gestão de estoque.
<img width="349" height="472" alt="Screenshot 2026-03-05 111815" src="https://github.com/user-attachments/assets/0c283c18-c254-4475-a209-ac6ba9ed4cae" />
