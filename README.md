# ConectaBanco
Classe criada para conexão ao DataBase MySQL e MongoDB

Conexão com Banco de Dados:

Estabelece conexão com um banco de dados MySQL/MariaDB utilizando JDBC.
Manipulação de Exceções (SQLException):

Trata exceções relacionadas a operações com o banco de dados usando SQLException.
Uso de Atributos Estáticos:

Declara e utiliza atributos estáticos para armazenar informações como nome do banco de dados, usuário, senha, servidor e porta.
Inicialização Estática:

Utiliza bloco de inicialização estática (static) para definir valores padrão para os atributos.
Manipulação de Conexão:

Implementa métodos para conectar e desconectar do banco de dados.
URL de Conexão Dinâmica:

Constrói dinamicamente a URL de conexão com o banco de dados com base nos atributos fornecidos.
Encapsulamento e Modularização:

Utiliza métodos para encapsular a lógica de conexão, desconexão e obtenção da conexão, promovendo modularização do código.
Singleton de Conexão:

Implementa uma abordagem Singleton, garantindo que apenas uma instância da conexão seja criada.
Configuração Padrão:

Define valores padrão para os atributos, facilitando a configuração inicial do banco de dados.
Uso do Driver JDBC:

Faz uso da classe DriverManager e do driver JDBC para interação com o banco de dados.
