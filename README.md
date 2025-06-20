# AZ-104 – Microsoft Azure Administrator

Guia de estudo aprofundado para a certificação **AZ-104**, com foco em cada domínio da prova, incluindo percentuais de incidência, resumos teóricos, serviços usados, e links oficiais da Microsoft Learn.

---

## 🧭 Índice

1. Administração de Identidade (15–20%)  
2. Administração de Contas de Usuário e de Grupo (incluído em Identidade – 15–20%)  
3. Administração dos Recursos do Azure (15–20%)  
4. Administração de Rede Virtual (20–25%)  
5. Administração de Conectividade entre Sites (parte de Rede – 20–25%)  
6. Administração do Tráfego de Rede (parte de Rede – 20–25%)  
7. Administração do Armazenamento do Azure (10–15%)  
8. Administração de Máquinas Virtuais do Azure (25–30%)

---

### 1. Administração de Identidade (15–20%)

**Inclui:** Microsoft Entra ID (Azure AD), sincronização com AD local, Conditional Access, MFA, identidade híbrida.

**Para a prova:**  
- Configurar sincronização com AD Connect  
- Implantar MFA, Conditional Access  
- Compreender papéis administrativos

📚 [Link para Microsoft Learn](https://learn.microsoft.com/pt-br/training/paths/az-104-manage-identities-governance/)

---

### 2. Administração de Contas de Usuário e de Grupo (parte do item 1 – 15–20%)

**Inclui:** criação, gerenciamento, acesso self-service, RBAC e controle de convidados.

**Para a prova:**  
- Delegar permissões com RBAC  
- Implementar SSPR  
- Configurar políticas de acesso de usuários externos

📚 [Link para Microsoft Learn](https://learn.microsoft.com/pt-br/training/modules/manage-azure-identities/)

---

### 3. Administração dos Recursos do Azure (15–20%)

**Inclui:** Resource Groups, tags, locks, Azure Policy, Management Groups, controle de custos.

**Para a prova:**  
- Aplicar Azure Policy  
- Configurar locks (ReadOnly/Delete)  
- Monitorar e controlar custos com Cost Management

📚 [Link para Microsoft Learn](https://learn.microsoft.com/pt-br/training/paths/az-104-manage-identities-governance/)

---

### 4. Administração de Rede Virtual (20–25%)

**Inclui:** criação de VNets/subnets, IPs públicos e privados, DNS personalizado, NSG, VNet Peering, rotas.

**Para a prova:**  
- Criar e configurar VNets, subnets e peering  
- Implantar NSGs e verificar regras efetivas  
- Resolver DNS via zonas públicas e privadas

📚 [Link para Microsoft Learn](https://learn.microsoft.com/pt-br/training/paths/az-104-manage-virtual-networks/)

---

### 5. Administração de Conectividade entre Sites (parte de Rede – 20–25%)

**Inclui:** VPN Gateway, ExpressRoute, Virtual WAN, Bastion.

**Para a prova:**  
- Criar conexões VPN S2S e P2S  
- Configurar ExpressRoute  
- Acessar com segurança via Azure Bastion

📚 [Link para Microsoft Learn](https://learn.microsoft.com/pt-br/training/modules/configure-connectivity-between-azure-virtual-networks/)

---

### 6. Administração do Tráfego de Rede (parte de Rede – 20–25%)

**Inclui:** Load Balancer, Application Gateway, Azure Firewall, Network Watcher.

**Para a prova:**  
- Configurar Load Balancer (inbound/outbound rules)  
- Implementar Application Gateway + WAF  
- Monitorar conectividade com Network Watcher

📚 [Link para Microsoft Learn](https://learn.microsoft.com/pt-br/training/modules/configure-load-balancing-azure/)

---

### 7. Administração do Armazenamento do Azure (10–15%)

**Inclui:** Blobs, Files, containers, tiers, replicação, SAS, File Sync, AzCopy.

**Para a prova:**  
- Criar Storage Accounts e configurar replicações  
- Definir políticas de ciclo de vida  
- Gerenciar SAS e permissões

📚 [Link para Microsoft Learn](https://learn.microsoft.com/pt-br/training/paths/az-104-implement-manage-storage/)

---

### 8. Administração de Máquinas Virtuais do Azure (25–30%)

**Inclui:** criação e gerenciamento de VMs, discos, extensões, scale sets, disponibilidade, backup.

**Para a prova:**  
- Criar e escalar VMs via Portal, CLI e ARM  
- Implantar scale sets e disponibilidade (zones/sets)  
- Usar extensões e configurar Azure Backup

📚 [Link para Microsoft Learn](https://learn.microsoft.com/pt-br/training/paths/az-104-implement-deploy-compute/)

---

## 📊 Distribuição de Conteúdo na Prova

| Área                                   | Incidência estimada |
|----------------------------------------|----------------------|
| Identidade e Governança                | 15–20%               |
| Recursos do Azure                      | 15–20%               |
| Redes Virtuais & Conectividade         | 20–25%               |
| Tráfego de Rede                        | 20–25%               |
| Armazenamento                          | 10–15%               |
| Máquinas Virtuais                      | 25–30%               |

Fonte: [Microsoft Skills Outline AZ-104 (oficial)](https://learn.microsoft.com/certifications/resources/study-guides/az-104)

---

## 🧠 Dicas de Estudo

- Estude por prioridade: **VMs, Redes e Identidade** são os mais cobrados.  
- Use os **sandboxes do Microsoft Learn** para praticar gratuitamente.  
- Faça provas simuladas e revise erros com atenção.  
- Crie flashcards com conceitos como: replicação de storage, tipos de disco, políticas, RBAC.  
- Pratique o uso de **Azure CLI, PowerShell e portal**.

---

🟢 **Dica Final:** Aprender a automatizar tarefas comuns com scripts (ARM, Bicep, CLI)!
---

