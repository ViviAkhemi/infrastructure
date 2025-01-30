# Desafio DevOps



## Equipe 

### PO Yanne Oliveira Almeida
### Scrum Viviane Akemi Okuma
### Engenheira Cloud Natália Custódio de Melo Mendes
### Engenheira Cloud Daiana Menezes Lima



# 🚀 Infraestrutura como Código (IaC) para WordPress com Terraform

## 📌 Requisito
Construir um ambiente para hospedar sites em WordPress e automatizar o processo com IaC.

### 🔹 **Princípios Adotados**
1️⃣ **Controle de Versão**: Todos os scripts de infraestrutura estão versionados no GitHub, utilizando GitActions para automação.
2️⃣ **Testes Automatizados**: Garantia de integridade das mudanças antes da implantação.
3️⃣ **Documentação Clara**: Processos e configurações documentados e constantemente atualizados.
4️⃣ **Segurança Incorporada**: Práticas seguras aplicadas desde a fase de desenvolvimento.

## 🛠️ **Tecnologias Utilizadas**
Foi utilizado o **LAMP Stack** (Linux, Apache, MySQL, PHP) em conjunto com o **Terraform** para criação da infraestrutura como código. O monitoramento e observabilidade são garantidos por **Prometheus** e **Grafana** na nuvem **AWS**.

## 🎯 **Benefícios da Infraestrutura como Código (IaC)**
✅ **Automatiza** a criação da infraestrutura.
✅ **Padroniza** ambientes, reduzindo erros humanos.
✅ **Facilita a replicação** da infraestrutura em diferentes ambientes.

## 🔄 **Integração Contínua (CI) & Implantação Contínua (CD)**
🔹 **CI (Continuous Integration):** Testa e valida automaticamente as alterações nos códigos de infraestrutura.
🔹 **CD (Continuous Deployment):** Aplica as alterações validadas para garantir que a infraestrutura esteja sempre atualizada.

## 🔒 **Segurança na IaC**
🔹 **Uso de SSH com chaves** para acesso seguro.
🔹 **Princípio do Menor Privilégio**, limitando acessos.
🔹 **Auditoria e gerenciamento rigoroso** das permissões.
🔹 **Evita exposição de credenciais**, utilizando ACCESS KEYs seguras.

## 🏗️ **Componentes da Solução**
✅ **Linux:** Sistema operacional estável e seguro.
✅ **Apache:** Servidor web para hospedagem dos sites.
✅ **MySQL:** Banco de dados relacional para armazenar informações do WordPress.
✅ **PHP:** Linguagem de programação utilizada para lógica do WordPress.
✅ **Terraform:** Ferramenta de IaC para provisionamento da infraestrutura na AWS.
✅ **Prometheus:** Monitoramento e coleta de métricas em tempo real.
✅ **Grafana:** Visualização de dados e dashboards dinâmicos.

## 📊 **Arquitetura do Projeto**
![Imagem Requisito](https://github.com/ViviAkhemi/Jorned/blob/main/MCIO/Infrastucture/ReadMe/requisito.jpg)

## 🔧 **Provisionamento Automatizado**
O provisionamento automatizado instala e configura servidores, redes e software de forma consistente e sem erros humanos. Utilizamos **Terraform com AWS** para criar:
✅ **Instâncias EC2** (hospedagem do WordPress).
✅ **Banco de Dados RDS** (armazenamento das informações).
✅ **Grupos de Segurança** (controle de acesso e firewall).

Com isso, garantimos um ambiente confiável e escalável para hospedar sites WordPress.




