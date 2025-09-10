**Análise de Serviços no Azure**  
O Azure oferece uma ampla gama de serviços voltados para análise e processamento de dados, incluindo:  

- Analysis Services  
- Cluster HDInsight  
- Data Factories  
- Data Lake Analytics  
- Data Lake Storage Gen1  
- Azure Databricks  
- Microsoft Graph Data Connect  
- Azure HDInsight integrado a clusters AKS  

Essa categorização facilita a navegação e a localização dos serviços na console do Azure.  

**SLA e Alta Disponibilidade**  
O Service Level Agreement (SLA) define o tempo de disponibilidade garantido pelo provedor de nuvem. Com um SLA de 99%, o serviço pode ficar indisponível por até 1,68 hora por semana ou 7,2 horas mensais. Já com um SLA de 99,9%, esse tempo é reduzido para 10,1 minutos por semana ou 43,6 minutos mensais.  

Ao criar máquinas virtuais, é possível configurar redundâncias em diferentes servidores ou localidades, o que aumenta a disponibilidade. Essas estratégias ajudam a evitar interrupções em casos de desastres, garantindo que o ambiente esteja acessível em outra região e otimizando a velocidade de acesso por meio de múltiplas fontes de dados.  

Na definição da arquitetura do sistema, é essencial validar a infraestrutura utilizada, pois os custos podem aumentar significativamente dependendo das configurações escolhidas.  

**Criação de Máquinas Virtuais: Configurações e Arquitetura**  
O painel de criação de máquinas virtuais no Azure permite visualizar as estimativas de custo e configurar uma série de recursos:  

- Reinício automático  
- Monitoramento e gerenciamento  
- Discos e peças  
- Modelos de redundância  

Além disso, o site [datacenters.microsoft.com/globe/explore](datacenters.microsoft.com/globe/explore) oferece um mapa interativo em 2D ou 3D para visualizar a localização dos datacenters da Microsoft. Este recurso apresenta as regiões do Azure, informações geográficas e detalhes sobre a infraestrutura global da plataforma.  

**Configurações adicionais na criação de máquinas virtuais**  
- Nome da máquina virtual  
- Região e zona de disponibilidade  
- Tipo de segurança  
- Sistema operacional e tamanhos de máquinas  
- Tipo de autenticação  
- Criação de usuário administrador  

Outras opções incluem: discos, redes, gerenciamento e monitoramento. Na área de governança, o uso de desktops remotos também facilita o acesso dos funcionários às máquinas virtuais, reduzindo a necessidade de hardware dedicado.  

**Armazenamento no Azure**  
A configuração do armazenamento começa com uma assinatura padrão e um grupo de recursos. Deve-se informar um nome único para a conta de armazenamento.  

- **Região**: Escolhido com base na latência ou custo desejado.  
- **Desempenho**: Standard (latência média) ou Premium (latência elevada).  
- **Redundância**: Tipos como LRS (local), GRS (geográfica), ZRS (zona) ou GZRS (zona geográfica).  

Configurações adicionais permitem selecionar o tipo de armazenamento (quente ou frio), rede, criptografia e outras especificações avançadas.  

**Menu: Armazenamento de Dados**  
O armazenamento no Azure permite compartilhamento, organização e backup com funcionalidades como:  

- **Containers**: Gerenciamento de pastas e configuração automática de backups.  
- **Compartilhamento de arquivos**: Conexão SMB para Windows, Linux e Mac.  
- **Filas**: Configuração de mensagens.  
- **Tabelas**: Criação e gerenciamento estruturado.  

**Migração de Dados para o Azure**  
O processo de migração permite transferir arquivos locais para a nuvem usando ferramentas como AZ Copy ou Azure Data Box:  

- **AZ Copy**: Aplicação leve para terminais (Windows, Linux e Mac).  
- **Azure Data Box**: Modalidade física com envio e retorno de disco rígido; ideal para grandes volumes:  
  - Data Box Disk: até 35TB  
  - Data Box Heavy: até 800TB  
  - Data Box Job: até 1TB  

Cada serviço possui custos variados conforme as necessidades do cliente.  

**Gerenciamento de Armazenamento no Azure**  
Com o Gerenciador de Armazenamento do Microsoft Azure, basta instalar a aplicação para acessar sua assinatura, contas de armazenamento e recursos diretamente na console intuitiva. 

**Identidade e Segurança (Entra ID)**  
No Azure, todos os usuários devem ser geridos através do Entra ID, que define funções e permissões atribuídas individualmente. Esse sistema se diferencia do RBAC ao estabelecer controles mais detalhados e específicos visando uma governança robusta da infraestrutura.


**Ferramentas de monitoramento no Azure**
O Azure oferece diversas soluções para acompanhar o ambiente, verificar o estado dos recursos e receber recomendações para otimização.  
Azure Monitor é uma ferramenta robusta que fornece insights detalhados e análises abrangentes sobre toda a infraestrutura, permitindo uma validação eficaz dos serviços.  
Service Health funciona como um painel que apresenta informações sobre a saúde do ambiente e mantimentos programados, ajudando a identificar possíveis pontos de degradação.  
Advisor oferece recomendações personalizadas para otimizar a infraestrutura, garantindo melhorias e benefícios  contínuos.  


Dentre outras diversas funcionalidade graças a sua grande disponibilidade de serviços.
