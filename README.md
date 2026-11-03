
# 🌊 Projeto FrontEnd - Monitoramento Hidrológico (Cogmo Technology)

Aplicação FrontEnd desenvolvida em **React** para o monitoramento de estações hidrológicas, exibindo níveis de rios, precipitação recente, gráficos de séries históricas e tabelas de consulta analítica de medições, como parte dos desafios do **Bolsa Futuro Digital (BFD)**.

---

## 🚀 Deploy da Aplicação

* **FrontEnd (Produção):** [Acesse o projeto na Vercel](https://hydrocogmo.vercel.app/) *(substitua pelo link real)*

---

## 📂 Repositórios do Projeto

* **FrontEnd (React):** [Repositório GitHub do Monitoramento Hidrológico](https://github.com/silver-ward/monitoramento-hidrologico)

---

## 🎯 Visão Geral do Projeto

* **Domínio:** Monitoramento Hidrológico e Ambiental.
* **Entidades Principais:** Estações Hidrológicas, Nível do Rio (metros), Precipitação (mm/h) e Estado de Transmissão.
* **Objetivo:** Desenvolver uma interface web interativa para consumo de dados hidrológicos, oferecendo visualização gráfica e analítica para apoio à tomada de decisão.

---

## 💻 Tecnologias Utilizadas

### FrontEnd
* **ReactJS**
* **JavaScript (ES6+)**
* **Ant Design (AntD)** / Componentes customizados
* **Chart Libraries** para os gráficos de nível e chuva

---

## 📊 Modelagem dos Dados

### Diagrama de Classes
O diagrama de classes abaixo representa o modelo conceitual utilizado no projeto para estruturar as informações das estações e medições hidrológicas.

 <img width="2085" height="1635" alt="graph" src="https://github.com/user-attachments/assets/839cd554-04b8-48c3-adc1-3e79ec80413e" />


---

## 🗂️ Estrutura do Projeto FrontEnd

A organização das pastas e arquivos do projeto segue a seguinte estrutura:

```text
monitoramento-hidrologico/
├── img/
│   ├── cogmo-logo.png
│   ├── ifb-logo.png
│   └── ...
├── src/
│   ├── assets/
│   │   └── fonts/
│   ├── components/
│   │   ├── AppHeader.jsx
│   │   ├── MeasurementCharts.jsx
│   │   ├── MeasurementTable.jsx
│   │   ├── Overview.jsx
│   │   └── StationControls.jsx
│   ├── data/
│   │   └── stations.js
│   ├── App.css
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
├── .env
├── package.json
└── README.md
```
---

---

## 💻 Execução Local

Para executar este projeto em sua máquina localmente, siga os passos abaixo:

```bash
# Clone este repositório
git clone [https://github.com/RebecaNM30/monitoramento-hidrologico.git](https://github.com/RebecaNM30/monitoramento-hidrologico.git)

# Entre na pasta do projeto
cd monitoramento-hidrologico

# Instale as dependências
npm install

# Inicie o servidor de desenvolvimento
npm run dev
```
