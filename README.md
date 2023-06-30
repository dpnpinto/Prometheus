# Prometheus - Sistema de Monitorização de Ativos de Rede

O objetivo deste projeto é a implementação modular de um sistema de monitorização de ativos de rede nas Escolas dos Açores. Este sistema é baseado em containers Docker, que permitem isolar e gerir os diferentes serviços de forma eficiente e escalável. O sistema utiliza diversas ferramentas e tecnologias, tais como Grafana, Prometheus e SNMP, entre outras, para recolher, armazenar, processar e visualizar os dados dos ativos de rede. O sistema permite monitorizar o estado, o desempenho e a disponibilidade dos equipamentos de rede, bem como gerar alertas e relatórios personalizados. O sistema é flexível e adaptável a diversas necessidades e características, podendo ser instalado com diferentes arquiteturas em diversas plataformas.

SNMP EXPORTER - Recolha, por pulling (SNMP GET), das metricas dos switchs;

PROMETHEUS - Gestão da recolha da informação e armazenamento em base de dados temporal;

GRAFANA - Disponibilização da informação e gestão de alertas por grupos de utilizadores e departamentos; 
