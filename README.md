# ELK Stack 1.0.5

Elk stack project ansible playbook
Ansible role za deployment ElasticSearch Kibana Logstash Filebeat Heartbeat Metricbeat


# Potrebne requirements

Instalirati potreben requirementse za python3

uraditi pip3 -r requirements.txt


Preuzeti verziju ako je potrebno vecu

mkdir -p elk_tar_path
curl  -o elk_tar_path/kibana-8.7.1-linux-x86_64.tar.gz https://artifacts.elastic.co/downloads/kibana/kibana-8.7.1-linux-x86_64.tar.gz
curl  -o elk_tar_path/elk_tar_path/elasticsearch-8.7.1-linux-x86_64.tar.gz https://artifacts.elastic.co/downloads/elasticsearch/elasticsearch-8.7.1-linux-x86_64.tar.gz


# Docs folder

Definisane enviroment varijable potrebne za izmenu vars koji koriste.

