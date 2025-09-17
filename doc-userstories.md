
# Documento Lista de User Stories

Documento construído a partido do **Modelo BSI - Doc 004 - Lista de User Stories** que pode ser encontrado no
link: https://docs.google.com/document/d/1Ns2J9KTpLgNOpCZjXJXw_RSCSijTJhUx4zgFhYecEJg/edit?usp=sharing

## Descrição

Este documento descreve os User Stories criados a partir da Lista de Requisitos no [Documento 001 - Documento de Visão](doc-visao.md). Este documento também pode ser adaptado para descrever Casos de Uso. Modelo de documento baseado nas características do processo easYProcess (YP).

## Histórico de revisões

| Data       | Versão  | Descrição                          | Autor                          |
| :--------- | :-----: | :--------------------------------: | :----------------------------- |




### User Story US02 - Manter Fornecedor

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US02</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong>Manter Fornecedor</td>
    <td style="padding:6px;">O sistema de manter um cadastro de fornecedores. Um fornecedor tem os atirbutos: id e name, além de ter relação com as tabelas de endereços e telefones. Ambas as relações são de 1:N (Um fornecedor tem vários endereços/telefones). A tabela de telefones tem os atributos: id, number, supplier_id. Já a tabela de endereços tem os atributos: id, city, street, neighborhood, number, supplier_id. O usuário poderá cadastrar, editar, excluir, listar ou detalhar um fornecedor.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">US01 - Manter Fornecedor</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em>proprietária da loja</em>, quero <em>realizar as operações de manter um fornecedor</em>, para <em>ter um controle e histórico sobre os fornecedores da loja</em>.
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Requisitos Relacionados</strong></td>
    <td style="padding:6px;">RF01</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Critérios de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>O sistema deve exibir mensagem de sucesso após cadastro correto.</li>
        <li>O sistema deve validar campos obrigatórios e exibir mensagens de erro.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Testes de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>TA01.01 - Cadastro bem sucedido com todos os dados válidos redireciona para uma mensagem de cadastro feito com sucesso.</li>
        <li>TA01.02 - Realizar o cadastro com algum campo inválido (vazio, valor não aceito, etc) retorna uma mensagem de erro e não efetua o cadastro.</li>
        <li>TA01.03 - Edição bem sucedida com todos os dados válidos redireciona para uma mensagem de atualização feita com sucesso.</li>
        <li>TA01.04 - Realizar a edição com algum campo inválido (vazio, valor não aceito, etc) retorna uma mensagem de erro e não efetua a edição.</li>
        <li>TA01.05 - Listar os fornecedores retornará a lista de todos os fornecedores cadastrados no sistema.</li>
        <li>TA01.06 - Listar os fornecedores e não encontrar nenhum, será retornada uma mensagem de fornecedores não encontrados.</li>
        <li>TA01.07 - Buscar um fornecedor retorna os dados desse fornecedor em específico.</li>
        <li>TA01.08 - Buscar um fornecedor inexistente retorna uma mensagem de fornecedor não encontrado.</li>
        <li>TA01.09 - Deletar um fornecedor retorna uma mensagem de fornecedor deletado com sucesso.</li>
        <li>TA01.10 - Deletar um fornecedor inexistente retorna uma mensagem de erro.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Estimativa</strong></td>
    <td style="padding:6px;">5h</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tempo Real Gasto</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tamanho Funcional</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Prioridade</strong></td>
    <td style="padding:6px;">Essencial</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Responsáveis</strong></td>
    <td style="padding:6px;">
      <ul>
        <li><strong>Analista:</strong> Elder</li>
        <li><strong>Desenvolvedor:</strong> Felipe</li>
        <li><strong>Revisor:</strong> Mosiah</li>
        <li><strong>Testador:</strong> Pedro Vitor</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Protótipo</strong></td>
    <td style="padding:6px;">
    </td>
  </tr>
</table>

### User Story US03 - Manter Entrada de Produto

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US03</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong>Manter Entrada de Produto</td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">RF03 - Manter Entrada</td>
  </tr> 
  <tr> 
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em>proprietária da loja</em>, quero <em>realizar o cadastro e as operações de entrada de produto</em>, para <em>ter controle sobre o estoque, valores de custo e histórico de entradas</em>.
    </td>
  </tr> 
  <tr>
    <td style="padding:6px;"><strong>Requisitos Relacionados</strong>RF02</td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Critérios de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>O sistema deve exibir mensagem de sucesso após cadastro correto.</li>
        <li>O sistema deve validar campos obrigatórios e exibir mensagens de erro.</li>
      </ul>
    </td>
  </tr>
  <tr> 
    <td style="padding:6px;"><strong>Testes de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>TA03.01 - Cadastro de entrada de produto bem sucedida com todos os dados válidos redireciona para uma mensagem de cadastro feito com sucesso.</li>
        <li>TA03.02 - Cadastro com campo inválido (vazio, valor não aceito etc.) retorna mensagem de erro e não efetua o cadastro.</li>
        <li>TA03.03 - Edição realizada com sucesso redireciona para uma mensagem de atualização concluída.</li>
        <li>TA03.04 - Edição não realizada devido a dados inválidos redireciona para uma mensagem de erro.</li>
        <li>TA03.05 - Consulta bem sucedida exibe os dados da entrada de produto.</li>
        <li>TA03.06 - Consulta sem resultados retorna mensagem de entrada de produto não encontrada.</li>
        <li>TA03.07 - Exclusão bem sucedida retorna mensagem de remoção feita com sucesso.</li>
      </ul> 
    </td>
  </tr> 
  <tr>
    <td style="padding:6px;"><strong>Estimativa</strong></td>
    <td style="padding:6px;">5h</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tempo Real Gasto</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tamanho Funcional</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Prioridade</strong></td>
    <td style="padding:6px;">Essencial</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Responsáveis</strong></td>
    <td style="padding:6px;">
      <ul>
        <li><strong>Analista:</strong> Felipe </li>
        <li><strong>Desenvolvedor:</strong> Pedro Vitor </li>
        <li><strong>Revisor:</strong> Elder </li>
        <li><strong>Testador:</strong> Mosiah </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Protótipo</strong></td>
    <td style="padding:6px;">
    </td>
  </tr>
</table>

### User Story US04 - Manter Venda de Produto

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US04</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong>Manter Venda de Produto</td>
    <td style="padding:6px;">O sistema deve manter um cadastro de vendas. Uma venda tem os atirbutos: id, preço, quantidade, data e informações do produto, sendo possível obter estes através da relação com a tabela de produto. O usuário poderá cadastrar, editar, excluir, listar ou detalhar um venda.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">RF04 - Manter Venda</td>
  </tr> 
  <tr> 
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em>proprietária da loja</em>, quero <em>realizar o cadastro e as operações de venda de produto</em>, para <em>ter controle sobre o estoque, valores de custo e histórico de vendas</em>.
    </td>
  </tr> 
  <tr>
    <td style="padding:6px;"><strong>Requisitos Relacionados</strong>RF02</td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Critérios de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>O sistema deve exibir mensagem de sucesso após cadastro correto.</li>
        <li>O sistema deve validar campos obrigatórios e exibir mensagens de erro.</li>
      </ul>
    </td>
  </tr>
  <tr> 
    <td style="padding:6px;"><strong>Testes de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>TA04.01 - Venda bem sucedido com todos os dados válidos redireciona para uma mensagem de venda feito com sucesso.</li>
        <li>TA04.02 - Tentar realizar venda com campo vazio, inválido ou sem produto retornará uma mensagem de erro e possibilitará a realização de uma nova venda.</li>
        <li>TA04.03 - Consulta bem sucedida com todos os dados válidos redirecionando para a venda solicitada.</li>
        <li>TA04.04 - Tentar realizar consulta com campo vazio ou inválido retornará uma mensagem de erro e possibilitará a realização de uma nova consulta.</li>
        <li>TA04.05 - Realizar consulta com dados que não correspondem a uma venda existente retornará uma mensagem de "nenhuma venda encontrada" e possibilitará a realização de uma nova consulta.</li>
        <li>TA04.06 - Edição realizada com sucesso, com todos os dados atualizados válidos redireciona para uma mensagem de atualização concluída.</li>
        <li>TA04.07 - Edição não realizada devido dados inválidos redireciona para uma mensagem de dados inválidos.</li>
        <li>TA04.08 - Exclusão com sucesso retorna mensagem de remoção feita com sucesso</li>
      </ul> 
    </td>
  </tr> 
  <tr>
    <td style="padding:6px;"><strong>Estimativa</strong></td>
    <td style="padding:6px;">6h</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tempo Real Gasto</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tamanho Funcional</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Prioridade</strong></td>
    <td style="padding:6px;">Essencial</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Responsáveis</strong></td>
    <td style="padding:6px;">
      <ul>
        <li><strong>Analista:</strong> Mosiah </li>
        <li><strong>Desenvolvedor:</strong> Felipe </li>
        <li><strong>Revisor:</strong> Pedro Vitor </li>
        <li><strong>Testador:</strong> Elder </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Protótipo</strong></td>
    <td style="padding:6px;">
    </td>
  </tr>
</table>

### User Story US06 - Manter Despesa

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US06</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong>Manter Despesa</td>
    <td style="padding:6px;">O sistema deve manter um cadastro de despesas. Uma despesa tem os atirbutos: nome, descrição, valor, data e tipo da despesa. O usuário poderá cadastrar, editar, excluir, listar ou detalhar um despesa.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">RF06 - Manter Despesa</td>
  </tr> 
  <tr> 
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em>proprietária da loja</em>, quero <em>realizar o cadastro e as operações de despesa</em>, para <em>ter controle sobre os valores de custo e histórico de despesas</em>.
    </td>
  </tr> 
  <tr>
    <td style="padding:6px;"><strong>Requisitos Relacionados</strong>RF06</td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Critérios de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>O sistema deve exibir mensagem de sucesso após cadastro correto.</li>
        <li>O sistema deve validar campos obrigatórios e exibir mensagens de erro.</li>
      </ul>
    </td>
  </tr>
  <tr> 
    <td style="padding:6px;"><strong>Testes de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>TA06.01 - Cadastro bem sucedido com todos os dados válidos redireciona para uma mensagem de cadastro realizado com sucesso.</li>
        <li>TA06.02 - Realizar o cadastro com algum campo inválido retorna uma mensagem de erro e não efetua o cadastro da despesa.</li>
        <li>TA06.03 - Edição bem sucedida com todos os dados válidos redireciona para uma mensagem de atualização feita com sucesso.</li>
        <li>TA06.04 - Realizar a edição com algum campo inválido retorna uma mensagem de erro e não efetua a edição.</li>
        <li>TA06.05 - Consultar a despesa retornará todos os seus dados.</li>
        <li>TA06.06 - Consultar a despesa e não encontrar nenhuma retornará uma mensagem de despesa não encontrada.</li>
        <li>TA06.07 - Deletar uma despesa retorna uma mensagem de despesa deletada com sucesso.</li>
        <li>TA06.08 - Deletar uma despesa inexistente retorna uma mensagem de erro</li>
      </ul> 
    </td>
  </tr> 
  <tr>
    <td style="padding:6px;"><strong>Estimativa</strong></td>
    <td style="padding:6px;">6h</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tempo Real Gasto</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tamanho Funcional</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Prioridade</strong></td>
    <td style="padding:6px;">Importante</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Responsáveis</strong></td>
    <td style="padding:6px;">
      <ul>
        <li><strong>Analista:</strong> Pedro Vitor </li>
        <li><strong>Desenvolvedor:</strong> Elder </li>
        <li><strong>Revisor:</strong> Mosiah </li>
        <li><strong>Testador:</strong> Felipe </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Protótipo</strong></td>
    <td style="padding:6px;">
    </td>
  </tr>
</table>

### User Story US07 - Geração de Relatórios

<table>
  <tr>
    <th colspan="2" style="text-align:left;background:#e0e0e0;padding:8px;">📌 User Story - US07</th>
  </tr>
  <tr>
    <td style="width:25%;padding:6px;"><strong>Título</strong>Geração de Relatórios</td>
    <td style="padding:6px;">O sistema deverá permitir gerar relatórios de produtos, histórico de produtos,
estoque, entrada, saída e despesas.</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Identificação</strong></td>
    <td style="padding:6px;">RF07 - Geração de Relatórios</td>
  </tr> 
  <tr> 
    <td style="padding:6px;"><strong>Story</strong></td>
    <td style="padding:6px;">
      Como <em>proprietária da loja</em>, quero <em>gerar os relatórios dos produtos e das despesas</em>, para <em>ter controle sobre os valores de custo, estoque e histórico de de entradas e saídas</em>.
    </td>
  </tr> 
  <tr>
    <td style="padding:6px;"><strong>Requisitos Relacionados</strong></td>
    <td style="padding:6px;">RF07</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Critérios de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>O sistema deve exibir mensagem de sucesso após geração correta.</li>
        <li>O sistema deve validar campos obrigatórios e exibir mensagens de erro.</li>
      </ul>
    </td>
  </tr>
  <tr> 
    <td style="padding:6px;"><strong>Testes de Aceitação</strong></td>
    <td style="padding:6px;">
      <ul>
        <li>TA07.01 - Relatórios de produtos é exibido com sucesso.</li>
        <li>TA07.02 - Campos início e fim de período são preenchidos corretamente e relatório de entradas é exibido com sucesso.</li>
        <li>TA07.03 - Campos início e fim de período estão vazios ou são preenchidos de forma inválida exibindo mensagem de erro na consulta de entradas.</li>
        <li>TA07.04 - Campos início e fim de período são preenchidos corretamente e relatório de saídas é exibido com sucesso.</li>
        <li>TA07.05 - Campos início e fim de período estão vazios ou são preenchidos de forma inválida exibindo mensagem de erro na consulta de saídas.</li>
        <li>TA07.06 - Campos início e fim de período são preenchidos corretamente e relatório de despesas é exibido com sucesso.</li>
        <li>TA07.07 - Campos início e fim de período estão vazios ou são preenchidos de forma inválida exibindo mensagem de erro na consulta de despesas.</li>
        <li>TA07.08 - Relatórios de histórico de produtos é exibido com sucesso.</li>
        <li>TA07.09 - Relatórios de estoque é exibido com sucesso. </li>
      </ul> 
    </td>
  </tr> 
  <tr>
    <td style="padding:6px;"><strong>Estimativa</strong></td>
    <td style="padding:6px;">8h</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tempo Real Gasto</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Tamanho Funcional</strong></td>
    <td style="padding:6px;"></td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Prioridade</strong></td>
    <td style="padding:6px;">Essencial</td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Responsáveis</strong></td>
    <td style="padding:6px;">
      <ul>
        <li><strong>Analista:</strong> Mosiah </li>
        <li><strong>Desenvolvedor:</strong> Pedro Vitor </li>
        <li><strong>Revisor:</strong> Elder </li>
        <li><strong>Testador:</strong> Felipe </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td style="padding:6px;"><strong>Protótipo</strong></td>
    <td style="padding:6px;">
    </td>
  </tr>
</table>
