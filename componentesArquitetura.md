# ☁️ Componentes de Arquitetura do Azure

## 📍 Regiões
- Compostas por um ou mais datacenters próximos.
- Fornecem flexibilidade e escala, reduzindo a latência do cliente.
- O Azure possui mais de 60 regiões em mais de 140 países! 🌍

## 🏢 Zonas de Disponibilidade
- Protegem contra o tempo de inatividade causado por falhas em um datacenter.
- Garantem maior resiliência, mantendo os aplicativos funcionando mesmo em caso de falha de infraestrutura.

## 🔗 Pares de Região
- Regiões emparelhadas, com no mínimo 300 milhas de distância entre si.
-  Fornecem replicação automática para alguns serviços e recuperação em caso de interrupção, minimizando o tempo de inatividade.

## 🛡️ Regiões Soberanas
- Oferecem serviços para atender a requisitos de segurança e conformidade governamental.
- Azure Government nos EUA.


# 🛠️ Recursos do Azure

- 🖥️ **Máquinas Virtuais**
- 💾 **Contas de Armazenamento**
- 🌐 **Redes Virtuais**
- 📱 **Serviços de Aplicativos**
- 🗄️ **Banco de Dados SQL**


# 📦 Grupos de Recursos
- contêiner usado para gerenciar e agrupar seus recursos
- recursos podem existir em **apenas um grupo**, mas podem estar localizados em **diferentes regiões**. 🌍


# 🔑 Assinatura do Azure

- Fornece acesso autenticado e autorizado à sua conta do Azure.
- **Funções**:
  - Controle de cobrança por assinatura.
  - Limita o controle de acesso de acordo com as necessidades do usuário.


# 🏢 Grupos de Gerenciamento

- Podem conter **várias assinaturas** dentro de uma organização.
- As condições de gerenciamento são herdadas pelo grupo, garantindo consistência de políticas e permissões.

