### Processo 7: Cadastro de Usuários

#### Requisitos Funcionais:

1. O sistema deve permitir o cadastro de novos usuários, coletando informações como nome, e-mail, telefone e função (administrador, técnico, cliente).
2. O sistema deve suportar diferentes níveis de acesso com base no tipo de usuário (e.g., administradores têm acesso total, técnicos têm acesso limitado a monitoramento e manutenção, e clientes podem visualizar relatórios).

#### Requisitos Não Funcionais:

1. **Segurança:** O cadastro de usuários deve ser protegido por autenticação forte, como autenticação de dois fatores (2FA), e criptografia de dados sensíveis (e.g., senhas).
2. **Escalabilidade:** O sistema deve ser capaz de suportar até 10 mil usuários cadastrados sem afetar o desempenho geral do sistema, com possibilidade de expansão.
