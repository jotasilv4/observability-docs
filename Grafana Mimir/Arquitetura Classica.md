O grafana mimir, ele tem uma arquitetura classica que daqui a pouco será obsoleta nas proximas versões mas ainda pode ser utilizada. Vamos começar a aprender com ela para depois ir para a arquitetura mais avançada, **sempre** vamos utilizar informações das documentações oficiais.

## Caminho de Escrita
O grafana mimir tem dois caminhos e vamos começar primeiro pelo caminho da escrita, que precisamos para fazer as escrita e guardar dados. O caminho de leitura precisa de um bucket para conseguir guardar seus dados. Os componentes de escritas são `distributor, ingester, compactor` o compactor e o ingester sempre vão enviar informações para o bucket

## Caminho da Leitura
Agora vamos falar sobre o caminho da leitura para poder utilizar e consultar os dados que está em nossas queries 