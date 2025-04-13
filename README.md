🏢 SLA (Service Level Agreement)

SLA é o acordo de nível de serviço que define a disponibilidade mínima que o provedor de nuvem garante para os seus serviços. Caso o serviço fique indisponível além do limite contratado, a empresa é compensada com créditos financeiros.

Exemplo de SLA:
SLA	Inatividade por Semana	Por Mês	Por Ano
99%	1,68 hora	7,2 horas	3,65 dias
99.9%	10,1 minutos	43,2 minutos	8,76 horas
99.95%	5 minutos	21,6 minutos	4,38 horas
99.99%	1,01 minuto	4,32 minutos	52,56 minutos
99.999%	6 segundos	25,9 segundos	5,26 minutos
💡 Benefícios da Nuvem

    Escalabilidade: Capacidade de expandir recursos sob demanda.

    Elasticidade: Redimensionamento automático com base no uso.

    Segurança Compartilhada: O provedor protege a infraestrutura; o cliente é responsável por dados, acessos e aplicações.

💾 Redundância de Dados na Azure

A Microsoft Azure oferece diferentes modelos de replicação de dados para garantir alta disponibilidade e durabilidade dos dados:
Tipo	Descrição
LRS — Locally Redundant Storage	Mantém 3 cópias dos dados dentro de um único datacenter na mesma região. Mais econômico, mas menos resiliente em caso de falhas regionais.
GRS — Geo-Redundant Storage	Mantém 6 cópias: 3 no datacenter original e 3 em outro datacenter, em uma região secundária geograficamente distante. Alta segurança contra falhas regionais.
ZRS — Zone-Redundant Storage	Replica dados entre zonas de disponibilidade (AZs) na mesma região. Protege contra falhas de datacenters locais.
GZRS — Geo-Zone-Redundant Storage	Combina ZRS + GRS: replica os dados entre zonas e também para uma região secundária, unindo alta disponibilidade local com recuperação geográfica.

Cada opção oferece um equilíbrio diferente entre custo, performance e segurança de dados. A escolha depende do nível de criticidade e disponibilidade que seu projeto exige.
🔗 SLA na Azure

A Microsoft Azure oferece SLAs que variam de acordo com o serviço contratado. Caso a disponibilidade mínima não seja atingida, os clientes podem solicitar reembolsos em créditos para uso em futuras faturas.
