# AZ-900
Estudos para a certificação Microsoft AZ-900

Tópicos Fundamentais da Nuvem (AZ-900)
📈 Escalabilidade (Vertical)
Definição: Aumento da capacidade de um único recurso (ex: adicionar mais CPU/RAM a uma VM).

Também chamada de: Scale-up ou scale-down.

Vantagens:

Simples de implementar.

Ideal para aplicações monolíticas.

Limitações:

Há um limite físico.

Pode exigir reinicialização da máquina.

🔄 Elasticidade (Horizontal)
Definição: Adição ou remoção de múltiplas instâncias para atender à demanda.

Também chamada de: Scale-out ou scale-in.

Vantagens:

Alta disponibilidade.

Resiliência e tolerância a falhas.

Usado em: Arquiteturas modernas como microserviços e aplicações distribuídas2.

🛠️ Gerenciamento
Ferramentas no Azure:

Azure Monitor: coleta métricas e logs.

Azure Advisor: recomendações de otimização.

Azure Policy: governança e conformidade.

RBAC (Role-Based Access Control): controle de acesso baseado em função.

Benefícios:

Centralização da administração.

Automação e segurança.

📊 Disponibilidade e SLA
🔢 Regra dos 9
A “regra dos 9” representa o percentual de tempo em que um serviço está disponível:

SLA (%)	Tempo de inatividade por mês	Tempo de inatividade por ano
99%	~7 horas e 18 minutos	~3 dias e 15 horas
99.9%	~43 minutos	~8 horas e 45 minutos
99.99%	~4 minutos	~52 minutos
99.999%	~26 segundos	~5 minutos e 15 segundos
Exemplo: O Azure Storage oferece SLA de 99.99%, enquanto Máquinas Virtuais com disponibilidade em zona podem chegar a 99.99% ou mais, dependendo da configuração.
