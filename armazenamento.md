# 🌩️ **Armazenamento Azure**

## 📂 **Contas de Armazenamento**  
- 🌍 Nome único globalmente  
- 🌐 Acesso à internet em todo o mundo  
- ⚙️ Define os serviços e a redundância de dados  

---

## 🔁 **Redundância de Armazenamento**
- 🔸 **LRS (Locally Redundant Storage)**: Armazena 3 cópias dos dados em um único datacenter. Não recomendado para produção devido à falta de tolerância a falhas em diferentes zonas.  
- 🔹 **ZRS (Zone-Redundant Storage)**: Armazena 3 cópias em diferentes zonas dentro de uma região, garantindo maior segurança e disponibilidade.  
![image](https://github.com/user-attachments/assets/ba00ab25-66a3-4c58-b524-605216ff4d76)

---

## 📦 **Serviços de Armazenamento**
- 🗃️ **Blob**: Armazenamento de grandes quantidades de dados não estruturados (ex.: texto, dados binários).  
- 💽 **Disco**: Discos para Máquinas Virtuais (VMs) e aplicativos.  
- 📩 **Fila**: Armazenamento e recuperação de mensagens (até 64KB cada).  
- 🖥️ **Arquivos**: Compartilhamento de arquivos de rede altamente disponível.  
- 🧮 **Tabelas**: Armazenamento de dados estruturados não relacionais, baseado em chave/atributo.

---

## 🔗 **Pontos de Extremidade Públicos**  
- Acessíveis globalmente pela internet.

---

## 🏷️ **Camadas de Acesso ao Armazenamento**
💰 Relacionadas aos custos de acesso:
- **Frequente**: 📈 Otimizada para dados acessados frequentemente.  
- **Exporádico**: 🔄 Acessos ocasionais, com armazenamento mínimo de 30 dias.  
- **Frio**: ❄️ Acessos raros, armazenados por pelo menos 90 dias.  
- **Arquivo Morto**: 🗃️ Acessos extremamente raros, com armazenamento mínimo de 180 dias.  

---

## 🛠️ **Migrações para o Azure**
- 🚚 **Azure Data Box**: Migração física de até 80 TB de dados.  

---

## 🗃️ **Opções de Gerenciamento de Arquivos**
- 📋 **AzCopy**: Ferramenta de linha de comando para copiar e sincronizar blobs ou arquivos em uma direção.  
- 🖥️ **Gerenciador de Armazenamento**: Interface gráfica do usuário disponível para Windows, macOS e Linux.  
- 🔄 **Sincronização de Arquivos**: Sincroniza arquivos do Azure e locais de forma bidirecional, mantendo os mais acessados localmente e liberando espaço.  
