Automação de Cadastro de Produtos
Este projeto em Python utiliza a biblioteca pyautogui para automatizar o processo de login e cadastro de produtos em um sistema web. A automação é ideal para tarefas repetitivas, economizando tempo e minimizando erros manuais.

⚙️ Funcionalidades
Login Automático: O script acessa uma URL específica, preenche os campos de e-mail e senha, e realiza o login.

Importação de Dados: Lê os dados de produtos de um arquivo .csv usando a biblioteca pandas.

Cadastro em Massa: Itera sobre as linhas da planilha e preenche automaticamente o formulário de cadastro no sistema web para cada produto.

Tratamento de Observações: Inclui uma lógica para preencher o campo de observações apenas quando a informação estiver disponível na planilha.

🔧 Pré-requisitos
Para rodar este script, você precisará ter o Python instalado. Além disso, as seguintes bibliotecas devem ser instaladas:

 pyautogui
 pandas


🚀 Como Usar
Configure o arquivo CSV: Certifique-se de que o arquivo produtos.csv esteja na mesma pasta do script main.py (ou com o caminho correto). Ele deve conter as colunas: codigo, marca, tipo, categoria, preco_unitario, custo e obs.

Ajuste o código:

Altere as credenciais de login no código (costaalyson@gmail.com e senhateste) para as suas, se necessário.

O script foi desenvolvido para a URL https://dlp.hashtagtreinamentos.com/python/intensivao/login. Se o sistema de destino for outro, ajuste as URLs e a sequência de comandos pyautogui.press() e pyautogui.write(). O tempo de espera (time.sleep()) também pode precisar de ajustes dependendo da velocidade da sua internet e do carregamento da página.

Execute o script: Rode o arquivo no terminal:

python main.py
Aviso: Certifique-se de não mover o mouse ou usar o teclado enquanto o script estiver em execução, pois isso pode interromper a automação.

⚠️ Observações
Este script utiliza automação de interface e é sensível à resolução de tela, disposição de janelas e desempenho do sistema.

O código foi desenvolvido com um pyautogui.PAUSE de 0.5 segundos para garantir que cada comando seja executado corretamente. Você pode ajustar esse valor para maior ou menor velocidade.
