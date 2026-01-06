# Jmeter Performance Teste

Suite de testes focada em análise de desempenho do YouTube utilizando JMeter.

## 📋 Sobre o Projeto

Ferramenta automatizada para execução de testes de performance no YouTube, utilizando JMeter como framework principal. O projeto realiza testes de Carga, Estresse e Pico, simulando diferentes cenários de uso.

## 📁 Estrutura do Projeto

Todos os arquivos relacionados aos testes de performance estão localizados dentro da pasta `performance`, incluindo:
- Scripts JMeter
- Arquivos de dados CSV
- Relatórios de teste
- Configurações do projeto

## 🚀 Funcionalidades

- Teste de Carga (600 threads)
- Teste de Estresse (400 threads)
- Teste de Pico (400 threads)
- Parametrização via CSV
- Monitoramento via Results Tree e Aggregate Report

## 🛠️ Tecnologias

- Apache JMeter
- CSV para parametrização
- Listeners:
  - Results Tree
  - Aggregate Report

## ⚙️ Configuração

### Pré-requisitos
- JMeter instalado
- Java Runtime Environment (JRE)

### Estrutura do CSV
O arquivo de parametrização deve conter os termos de busca a serem utilizados nos testes.

## 📊 Tipos de Teste

### Teste de Carga
- Threads: 600
- Objetivo: Validar o comportamento do sistema sob carga normal de usuários

### Teste de Estresse
- Threads: 1000
- Objetivo: Avaliar o sistema em condições extremas

### Teste de Pico
- Threads: 1000
- Objetivo: Analisar o comportamento em picos repentinos de acesso

## 📈 Relatórios
Os resultados podem ser analisados através de:
- Results Tree: Análise detalhada de cada requisição
- Aggregate Report: Visão consolidada dos resultados

## 🤝 Contribuindo
Sinta-se à vontade para contribuir com melhorias neste projeto.
