# CrossFit

## 📋 Requisitos Funcionais

### 1. Login
- **RF01**: Login com email e senha
- **RF02**: Validação de campos não vazios
- **RF03**: Exibição de mensagem de erro do backend
- **RF04**: Logout do sistema
  
### 2. Tela Principal
- **RF05**: Exibir nome do usuário logado
- **RF06**: Botão para Cadastro de Produtos
- **RF07**: Botão para Gestão de Estoque
- **RF08**: Botão Sair

### 3. Cadastro de Produto
- **RF09**: Listar produtos em ordem alfabética
- **RF10**: Buscar produtos por nome
- **RF11**: Cadastrar novo produto (nome, quantidade, estoque mínimo)
- **RF12**: Editar produto existente
- **RF13**: Excluir produto com confirmação
- **RF14**: Validação: nome obrigatório
- **RF15**: Validação: quantidade não negativa
- **RF16**: Validação: estoque mínimo não negativo
- **RF17**: Indicador "⚠️" quando quantidade < estoque mínimo

### 4. Gestão de Estoque
- **RF18**: Listar produtos em ordem alfabética com quantidades
- **RF19**: Registrar movimentação (entrada/saída)
- **RF20**: Selecionar produto
- **RF21**: Selecionar tipo (entrada/saída)
- **RF22**: Informar quantidade > 0
- **RF23**: Informar data da movimentação (opcional)
- **RF24**: Informar observação (opcional)
- **RF25**: Alerta se estoque ficar abaixo do mínimo após movimentação
- **RF26**: Atualizar lista de produtos após movimentação
