# Prometheus
Implementação modular de um sistemas de monitorização para ativos de rede
Este sistema vai funciona de forma modular implementado em containers utilizando o Docker.
Esta forma de implementação permite a colocação dos serviço em produção de forma agil e utilizando diversas arquiteturas.
A flexibilidade do sistema utilizado tem se evrificado muito interessante e a utilização do melhor de cada componente:
SNMP EXPORTER - Recolha por poling das metricas dos switchs
PROMETHEUS - Recolha da informação em base de dados temporal
GRAFANA - Disponibilização da informação e gestão de alertas por grupos de utilizadores e departamento 
