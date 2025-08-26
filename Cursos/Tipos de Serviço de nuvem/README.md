
# ☁️ Tipos de Serviço de Nuvem e Criação de Instância Gerenciada de SQL no Azure

## 🧩 Tipos de Serviço de Nuvem

### 🖥️ IaaS (Infraestrutura como Serviço)

- **Descrição**: Proporciona infraestrutura de TI sob demanda. O usuário aluga servidores, VMs, armazenamento, rede e sistemas operacionais do provedor de nuvem.
- **Exemplo de uso**: Migração de servidores locais para a nuvem.
- **Responsabilidade**: O cliente é responsável por configurar e gerenciar a infraestrutura.
- **Características**:
  - Alta flexibilidade
  - Controle total da infraestrutura
  - Modelo "pague conforme o uso"

---

### 🛠️ PaaS (Plataforma como Serviço)

- **Descrição**: Oferece um ambiente completo para desenvolvimento, teste e implantação de aplicativos sem gerenciar a infraestrutura.
- **Exemplo de uso**: Desenvolvimento de aplicações web.
- **Responsabilidade**: O provedor gerencia a plataforma; o cliente foca no código.
- **Características**:
  - Redução de tempo para desenvolvimento
  - Automatização de provisionamento
  - Escalabilidade integrada

---

### 📦 SaaS (Software como Serviço)

- **Descrição**: O usuário consome diretamente aplicações hospedadas na nuvem via internet.
- **Exemplo de uso**: Microsoft 365, emails, calendários.
- **Responsabilidade**: O provedor gerencia tudo.
- **Características**:
  - Modelo de assinatura
  - Acesso sob demanda
  - Nenhuma preocupação com manutenção

---

## 🔒 Modelo de Responsabilidade Compartilhada

- **Cliente**: Segurança dos dados, contas de usuário e configurações de rede
- **Provedor**: Segurança física, infraestrutura, hardware e parte do software (dependendo do modelo)

---

## 🛠️ Como Criar uma Instância Gerenciada de SQL no Azure (via Portal)

Fonte oficial: [Microsoft Learn](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal)

### 📝 Pré-requisitos

- Conta no Azure
- Permissões de administrador para criar recursos

### 🚀 Etapas no Portal do Azure

1. **Acessar o portal**: [portal.azure.com](https://portal.azure.com)
2. **Criar um recurso**: No menu à esquerda, clique em **Criar um recurso** > **Databases** > **Instância Gerenciada do SQL**
3. **Configurar as informações básicas**:
   - Assinatura e grupo de recursos
   - Nome da instância
   - Região
   - Tipo e tamanho do compute
4. **Configurar a rede**:
   - Usar uma VNet existente ou criar nova
   - Definir regras de firewall se necessário
5. **Configurar a segurança**:
   - Autenticação do SQL (usuário/senha)
   - Opções adicionais: integração com Azure AD
6. **Opções adicionais**:
   - Backup automático
   - Redundância de zona (se necessário)
7. **Revisar e criar**:
   - Verifique todas as configurações
   - Clique em **Criar** e aguarde a implantação (~10 a 30 minutos)

---

## ✅ Conclusão

Você aprendeu os principais tipos de serviço de nuvem (IaaS, PaaS e SaaS), suas características e responsabilidades, além de como provisionar uma **instância gerenciada do SQL no Azure** via portal de forma prática.

---

## 🔗 Links Úteis

- [README Principal](../../README.md)
- [Microsoft Learn: Instância Gerenciada de SQL](https://learn.microsoft.com/pt-br/azure/azure-sql/managed-instance/instance-create-quickstart?view=azuresql&tabs=azure-portal)
