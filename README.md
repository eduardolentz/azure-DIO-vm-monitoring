# 🚀 Monitoramento de Máquinas Virtuais no Azure

## 📚 Sobre o Projeto

Este repositório faz parte do desafio prático da DIO sobre **Monitoramento de Máquinas Virtuais (VMs)** no Microsoft Azure. Aqui, compartilho resumos, anotações, capturas de tela e dicas práticas sobre como configurar alertas, coletar métricas e analisar logs para garantir visibilidade e segurança em ambientes na nuvem.

---

## 🎯 Objetivos do Projeto

✅ Entender como monitorar recursos no Azure  
✅ Criar alertas para eventos críticos (ex.: exclusão de VMs)  
✅ Consolidar o conhecimento adquirido nas aulas  
✅ Produzir material de estudo para revisões futuras  
✅ Compartilhar conhecimento com a comunidade DIO

---

## 💻 Conteúdos Abordados

### ✅ Visão Geral do Azure Monitor

- Serviço central de monitoramento no Azure
- Coleta dados de métricas e logs
- Permite criar alertas baseados em condições específicas

---

### ✅ Métricas vs. Logs

| Métricas                        | Logs                                  |
|---------------------------------|---------------------------------------|
| Dados numéricos em intervalos   | Dados detalhados em formato texto     |
| Baixo custo                     | Maior custo, mas muito mais detalhes  |
| Ideal para monitoramento rápido | Ideal para auditoria e troubleshooting |

---

### ✅ Criação de Alertas

- Criação via Azure Portal
- Escolha da condição (ex.: exclusão de VM, CPU alta, etc.)
- Definição de Ações:
  - Email
  - SMS
  - Webhook
  - Automation Runbook
- Criação de Action Groups (grupos de ação reutilizáveis)

---

### ✅ Monitoramento da Exclusão de VMs

- Habilitar logs de atividade
- Criar alerta para operação:

- - Definir ação para notificação imediata (email ou webhook)

---

## 🛠️ Passo a Passo: Criando um Alerta no Portal Azure

1. Acesse [https://portal.azure.com](https://portal.azure.com)
2. Pesquise por **Monitor**
3. Clique em **Alerts**
4. Clique em **+ New alert rule**
5. Escolha o recurso (VM ou subscription)
6. Defina a condição (ex.: “Delete Virtual Machine”)
7. Escolha ou crie um Action Group
8. Clique em **Create alert rule**

---

## 📸 Capturas de Tela

Imagens disponíveis na pasta [`/images`](./images). Exemplos incluídos:
- Criação de alertas
- Visualização de logs
- Tela do Azure Monitor

---

## 💡 Dicas Rápidas

✅ Use nomes claros para as regras de alerta  
✅ Agrupe ações em Action Groups para reaproveitar configurações  
✅ Avalie custos do Log Analytics antes de habilitar logs detalhados  
✅ Não configure alertas redundantes (pode gerar custos desnecessários)  
✅ Monitore também alterações de segurança (ex.: alterações em NSGs)

---

## 🔗 Referências

- [Microsoft Learn – Configurar o monitoramento de máquinas virtuais](https://learn.microsoft.com/pt-br/training/modules/monitor-virtual-machines-azure/)
- [Azure Monitor Overview](https://learn.microsoft.com/pt-br/azure/azure-monitor/overview)
- [Documentação do GitHub](https://docs.github.com/pt)
- [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)

---

## 👨‍💻 Autor

**Eduardo**  
[LinkedIn](#) | [GitHub](#)

