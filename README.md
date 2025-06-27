# Protótipo AE2 - Voluntários do Mangue

Repositório destinado para hospedar as imagens e readme das telas do protótipo referente a atividade extensionista, do curso de ADS da UNINTER.

## Fluxos Principais

### 1. Primeiro Acesso
1. **Splash Screen**
   - Apresentação inicial do aplicativo
   - Carregamento de recursos

2. **Onboarding**
   - Conjunto de 3 telas introdutórias
   - Explicação do propósito do app
   - Guia rápido de utilização

### 2. Autenticação
1. **Login**
   - Acesso à conta existente
   - Links para recuperação de senha

2. **Cadastro**
   - Formulário de novo usuário
   - Validação de dados

3. **Recuperação de Senha**
   - Confirmação de dados
   - Código de verificação
   - Criação de nova senha

### 3. Eventos
1. **Listagem**
   - Meus Eventos (lista)
   - Filtros e buscas

2. **Detalhes do Evento**
   - Informações completas
   - Ações disponíveis

3. **Criação de Evento**
   - Dados principais
   - Agendamento
   - Confirmação

4. **Edição de Evento**
   - Atualização de informações
   - Modificação de dados

### 4. Perfil
1. **Visualização**
   - Dados do usuário
   - Histórico de atividades

2. **Edição**
   - Atualização de informações
   - Alteração de foto

3. **Segurança**
   - Redefinição de senha
   - Configurações de privacidade

### 5. Administração
1. **Gestão de Usuários**
   - Lista de usuários
   - Controle de acesso
   - Moderação

## Estrutura do Projeto

```
prototipo/
└── telas/
    # Fluxo Inicial
    ├── splash/
    ├── introducao/
    
    # Autenticação
    ├── login/
    ├── cadastro-usuario/
    ├── esqueci-minha-senha/
    
    # Navegação Principal
    ├── home/
    
    # Módulo de Eventos
    ├── meus-eventos/
    ├── detalhes-evento/
    ├── criar-evento/
    │   ├── dados-principais/
    │   ├── agendamento/
    │   └── conclusao/
    └── editar-evento/
    
    # Perfil e Configurações
    ├── editar-perfil/
    ├── redefinir-senha/
    └── gestao-usuarios/
```
