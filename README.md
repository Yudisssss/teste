&nbsp;
<p align="center">
  <a href="https://editoraviseu.com/publique-conosco/?utm_source=google&utm_medium=pesquisa&utm_campaign=institucional_BRA&gad_source=1&gad_campaignid=20010835834&gclid=CjwKCAjwv5zEBhBwEiwAOg2YKII2Wx-ecZ63yhH6gB1Scm-Hbkuu0O461Q18LGOUjNnbSzKVpW0emxoCugcQAvD_BwE" target="_blank">
    <img src="https://lh4.googleusercontent.com/proxy/WtdjW3KuTpjJcMAG5_SkbY9yVJLUYkrqTy8HWtwnK3l-QhS9ASFca0OI9ICEcsD22j7ZzugkSIzf3kOCBWkuQj0Eg6UewaxRyLBT9CHsiXFJ_HGrMpQa4A=w1920-h962" alt="Viseu" width="500px">
  </a>
<small align="center">0.1</small>
</p>
&nbsp;

<h1 align="center">ETL DATABRIDGE</h3>
&nbsp;

<p align="center">
    <a href="https://spring.io/">
        <img src="https://img.shields.io/badge/4.0.0%20(M1)-green?logo=spring&logoColor=black" alt="Spring" />
        &nbsp;
    </a>
    <a href="https://www.java.com/pt-BR/">
        <img src="https://img.shields.io/badge/0.0.0-orange?logo=coffeescript&logoColor=black" 
        alt="Java" />
        &nbsp;
    </a>
    <a href="https://www.docker.com/">
        <img src="https://img.shields.io/badge/0.0.0-blue?logo=docker&logoColor=black" alt="Docker-Compose" />
        &nbsp;
    </a>
    <a href="https://www.postgresql.org/">
        <img src="https://img.shields.io/badge/0.0.0-gray?logo=postgresql&logoColor=black" 
        alt="Postgres" />
        &nbsp;
    </a>
    <a href="https://swagger.io/">
        <img src="https://img.shields.io/badge/0.0.0-green?logo=swagger&logoColor=black" 
        alt="Swagger" />
        &nbsp;
    </a>
</p>


### ETL Databridge Viseu
Databridge ETL is an internal API developed for Editora Viseu. Its main function is to process data extracted from ClickUp. Once processed, it is then sent to the Metabooks service. The project is based on the main ETL principles: Extract, Transform, and Load.

&nbsp;
### Features
This application functions as a complete, end-to-end ETL solution.

__Data Extraction__
- Secure connection to the ClickUp API.
- Extracts only selected data.
- Configurable data sources (lists, tasks, fields).

__Data Transformation__
- Dynamic and configurable field mapping.
  - Maps ClickUp fields to the Metabooks schema via a configuration file.
- Automated data cleansing and standardization.
  - E.g., Standardizes date formats and cleans text fields.
- Validates data against custom business rules.
  - E.g., Checks required fields, such as ISBNs, before processing.

__Data Loading__
- Optimized data loading for the Metabooks API.
- Intelligent "Upsert" logic to avoid duplicate records.
  - Updates existing entries and creates new ones.
- Efficient batch processing for large data volumes.

&nbsp;
&nbsp;
## Run Locally

Clone the project
bash
  git clone https://link-to-project
Go to the project directory
bash
  cd my-project
Install dependencies
bash
  npm install
Start the server
bash
  npm run start


&nbsp;
&nbsp;
### API Reference
The API routes are found inside 
[Swagger](https://swagger.io/)

&nbsp;
&nbsp;
### Running Tests
To run tests, run the following command
bash npm run test



&nbsp;
&nbsp;

## License

[LICENSE](LICENSE)
