# Sistema Hospitalar Multiclínica

Sistema de gestão hospitalar desenvolvido em PHP com Laravel Framework.

## Descrição

Este é um sistema completo para gerenciamento de clínicas e hospitais multiclinicas, com funcionalidades que incluem:

- Gestão de pacientes
- Agendamento de consultas
- Prescrição médica
- Gestão de medicamentos
- Controle de internações
- Sistema de presença/assiduidade
- Relatórios e estatísticas
- Controle de acesso baseado em funções

## Tecnologias Utilizadas

- **Backend**: Laravel 5.8 + PHP 7.4
- **Frontend**: Vue.js 2.6, Bootstrap 4.3, jQuery 3.4
- **Banco de Dados**: MySQL
- **Autenticação**: Sistema de autenticação do Laravel
- **Relatórios**: DomPDF para geração de PDFs
- **Código de barras**: Biblioteca milon/barcode
- **Logs e Auditoria**: spatie/laravel-activitylog
- **Backup**: spatie/laravel-backup

## Requisitos do Sistema

- PHP 7.4
- MySQL 5.7+
- Composer
- Node.js e NPM
- Extensões PHP: OpenSSL, PDO, Mbstring, Tokenizer, XML, Ctype, JSON

## Instalação

1. Clone o repositório
2. Instale as dependências do PHP:
   ```bash
   composer install
   ```
3. Instale as dependências do Node:
   ```bash
   npm install
   ```
4. Compile os assets:
   ```bash
   npm run dev
   ```
5. Configure o arquivo .env com suas credenciais de banco de dados
6. Execute as migrações:
   ```bash
   php artisan migrate --seed
   ```
7. Inicie o servidor:
   ```bash
   php artisan serve
   ```

## Usuários de Teste

O sistema possui 5 usuários padrão criados durante a instalação:

1. **Administrador**:
   - Email: shakthisachintha@gmail.com
   - Senha: 12345678

2. **Médico**:
   - Email: ssakunchamikara@gmail.com
   - Senha: 12345678

3. **Farmacêutico**:
   - Email: sachinthaindu95@gmail.com
   - Senha: 12345678

4. **Funcionário geral**:
   - Email: sanduniiresha1029@gmail.com
   - Senha: 12345678

5. **Funcionário geral**:
   - Email: hasikadilshani@gmail.com
   - Senha: 12345678

## Funcionalidades Principais

### Gestão de Usuários
- Controle de acesso baseado em funções
- Autenticação segura
- Recuperação de senha

### Gestão de Pacientes
- Cadastro completo de pacientes
- Cartões com código de barras
- Histórico médico
- Busca e filtragem

### Agendamentos
- Sistema de agendamento de consultas
- Gestão de horários
- Controle de status

### Funcionalidades Médicas
- Registro de diagnósticos
- Prescrição de medicamentos
- Consultas médicas

### Gestão de Medicamentos
- Inventário de medicamentos
- Controle de estoque
- Dispensação de medicamentos

### Internações
- Gestão de enfermarias
- Controle de pacientes internados
- Registro de altas

### Presença
- Controle de ponto eletrônico
- Integração com biometria
- Relatórios de assiduidade

### Relatórios
- Relatórios de atividades
- Estatísticas médicas
- Relatórios administrativos

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.


