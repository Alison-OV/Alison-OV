### 🚀 Hey there! I'm Alison-OV
<p>
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&color=A63885&pause=1000&width=1000&lines=Code+Hard,+Break+The+Mold;Innovate+Without+Fear;Imagine,+Build,+Inspire!" alt="Typing SVG" /></a>
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/alison-gissel) 

---

### About Me

- 💻 Turning data and code into clean, scalable backend systems and intelligent architectures.
- 🚀 Passionate about building web apps and AI-driven solutions.

---

### Tech Stack

Here are some of the technologies I work with:

- **Backend & Databases:** 
<p>
  <!-- Lenguajes y Base -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="40" height="40" alt="Python" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="40" height="40" alt="NodeJS" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg" width="40" height="40" alt="Docker" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/kubernetes/kubernetes-plain.svg" width="40" height="40" alt="Kubernetes" />
  
  <!-- Bases de Datos -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="40" height="40" alt="PostgreSQL" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/oracle/oracle-original.svg" width="40" height="40" alt="Oracle" />
  <img src="https://www.vectorlogo.zone/logos/snowflake/snowflake-icon.svg" width="40" height="40" alt="Snowflake" />
  
  <!-- Big Data y Procesamiento -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/apachespark/apachespark-original.svg" width="40" height="40" alt="Spark" />
  <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fa/Microsoft_Azure.svg/330px-Microsoft_Azure.svg.png?utm_source=commons.wikimedia.org&utm_campaign=index&utm_content=thumbnail&_=20211008202712" width="40" height="40" alt="Azure" />
  
  <!-- Cloud (AWS y GCP) -->
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTcl__1dyRDPCWNQ3bYtPXsdrHih-0jGOE6QjvnU_f9og&s=10" width="40" height="40" alt="AWS" />
  <img src="https://www.vectorlogo.zone/logos/google_cloud/google_cloud-icon.svg" width="40" height="40" alt="GCP" />
  
  <!-- IA / ML / LLMs -->
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tensorflow/tensorflow-original.svg" width="40" height="40" alt="TensorFlow" />
  <img src="https://www.vectorlogo.zone/logos/pytorch/pytorch-icon.svg" width="40" height="40" alt="PyTorch" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="40" height="40" alt="Pandas" />
</p>

- **Frontend & Web:**
  <p>
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40" height="40" alt="JavaScript" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="40" height="40" alt="React" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg" width="40" height="40" alt="TailwindCSS" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg" width="40" height="40" alt="NextJS" />
  </p>

---

## GitHub Contribution

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Alison-OV/Alison-OV/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Alison-OV/Alison-OV/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Alison-OV/Alison-OV/output/github-contribution-grid-snake.svg">
</picture>

---

## Arquitectura de Datos Empresarial y Soluciones Backend Escalables

```mermaid
flowchart LR
    %% Capa 1: Ingesta
    subgraph Ingest [📦 Data Ingestion]
        API[API REST / GraphQL]
        DB[Enterprise DBs]
        S3[S3 / Data Lake]
    end

    %% Capa 2: Procesamiento
    subgraph Process [⚡ ETL & Processing]
        Py[Python Services]
        Spark[PySpark / Spark]
        Batch[SSIS / Batch Jobs]
    end

    %% Capa 3: Almacenamiento
    subgraph Storage [💾 Warehousing]
        Fabric[Microsoft Fabric]
        BQ[Google BigQuery]
        DWH[Data Marts]
    end

    %% Capa 4: Consumo
    subgraph Delivery [🚀 Serving & BI]
        BI[Power BI / Looker]
        API_Out[Backend APIs]
        ML[ML Inference]
    end

    %% Flujos de datos principales
    API --> Py
    DB --> Py
    S3 --> Spark
    
    Py --> Fabric
    Spark --> BQ
    
    Fabric --> DWH
    BQ --> DWH
    
    DWH --> BI
    DWH --> API_Out
    Fabric --> ML
