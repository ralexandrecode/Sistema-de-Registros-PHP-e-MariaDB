# Sistema de Registros PHP/MariaDB

Este repositório contém uma aplicação CRUD (Criar, Ler, Atualizar, Deletar) completa, desenvolvida em PHP e MariaDB, para gerenciar informações de clientes. A aplicação oferece uma interface web intuitiva com funcionalidades para adicionar, visualizar, pesquisar, modificar e excluir registros de clientes, utilizando um banco de dados MariaDB para armazenamento persistente dos dados. O projeto inclui arquivos PHP para a lógica de negócios, HTML para a estrutura das páginas e CSS para a estilização, proporcionando uma solução completa e pronta para uso.

**Descrição dos Arquivos:**

1.  **`config.php`**:
    * **Descrição:** Este arquivo contém as configurações de conexão com o banco de dados MariaDB. Ele armazena as credenciais (nome do host, nome de usuário, senha e nome do banco de dados) e estabelece a conexão com o banco de dados.
    * **Propósito:** Centralizar as configurações de conexão para facilitar a manutenção e evitar a duplicação de código.

2.  **`index.php`**:
    * **Descrição:** A página inicial da aplicação CRUD. Ela exibe um menu com links para as outras páginas (visualizar, pesquisar, excluir, modificar e adicionar clientes).
    * **Propósito:** Servir como ponto de entrada para a aplicação e facilitar a navegação entre as funcionalidades.

3.  **`visualizar.php`**:
    * **Descrição:** Esta página exibe uma tabela com todos os registros da tabela `clientes` do banco de dados. Ela lista os campos: ID, nome, email, telefone e data de cadastro.
    * **Propósito:** Permitir que os usuários visualizem todos os clientes cadastrados no banco de dados.

4.  **`pesquisar.php`**:
    * **Descrição:** Esta página permite que os usuários pesquisem clientes por nome ou ID. Ela exibe os resultados da pesquisa em uma tabela.
    * **Propósito:** Facilitar a busca de clientes específicos no banco de dados.

5.  **`excluir.php`**:
    * **Descrição:** Esta página permite que os usuários excluam clientes por nome ou ID. Ela exibe um formulário de confirmação antes de excluir os registros.
    * **Propósito:** Permitir a remoção de clientes do banco de dados.

6.  **`modificar.php`**:
    * **Descrição:** Esta página permite que os usuários modifiquem os dados de clientes existentes. Ela exibe um formulário preenchido com os dados do cliente selecionado.
    * **Propósito:** Permitir a atualização dos dados dos clientes no banco de dados.

7.  **`adicionar.php`**:
    * **Descrição:** Esta página exibe um formulário para adicionar novos clientes ao banco de dados. Ela coleta os dados: nome, email e telefone.
    * **Propósito:** Permitir a inclusão de novos clientes no banco de dados.

8.  **`style.css`**:
    * **Descrição:** Este arquivo CSS contém os estilos para as páginas da aplicação. Ele define a aparência dos elementos HTML, como tabelas, formulários e botões.
    * **Propósito:** Melhorar a experiência do usuário, tornando a aplicação mais atraente e fácil de usar.

9.  **`logo.png`**:
    * **Descrição:** Este arquivo de imagem contém a logo da aplicação. Ele é exibido no canto superior esquerdo de todas as páginas.
    * **Propósito:** Identificar a aplicação e melhorar sua identidade visual.

10. **`baseDB.sql`**:
    * **`Descrição:`** Este arquivo SQL contém os comandos para criar o banco de dados baseDB e a tabela clientes. Ele define a estrutura da tabela com os campos: id, nome, email, telefone e data_cadastro.
    * **`Propósito`**: Fornecer um script SQL para configurar o banco de dados necessário para a aplicação CRUD, facilitando a instalação e o uso por outros desenvolvedores.

