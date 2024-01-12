<h1 align="center">HealthCare_Insurance_Project</h1>  

<details><summary><b>What is the project trying to solve?</b></summary>
</br>

|    | Problem Statement                                                                                                                                                |
|----|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. | ABC is an insurance company that sells insurance policies to retail customers                                |
| 2. | In this project, I worked on developing an end-to-end data engineering pipeline for an insurance company to analyze claims data and perform customer segmentation|
| 3. | This will help the company to better understand their customers' needs and tailor their offerings accordingly|
</details> 

<details><summary><b>High Level Details</b></summary>
</br>

|    | High-Level Details                                                                                                                                |
|----|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. | These were the source systems: Rest API (To fetch demographic info), CSV Files, JSON Files, SQL Server DB|
| 2. | Plan was to build the 3-layered (Bronze/Silver/Gold) architecture |
| 3. | Data had a lot of inconsistency and needed some cleaning |
| 4. | Once cleanup was done, multiple transformations were performed |
| 5. | Final layer i.e. the gold layer was stored as a Data lakehouse in Databricks|
| 6. | Gold layer data was accessed by PowerBI for visualization and reporting purposes|

</details> 

<details><summary><b>Project : Additional Information</b></summary>
</br>

|    | Additional Information                                                                                                                                             |
|----|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1. | Branch data, Claim data, and Agent data were extracted from Azure SQL DB |
| 2. | Policy Data was sent once every day by an upstream system in an ADLS container in JSON format|
| 3. | Customer Information was sent once every day by the upstream system in an ADLS container in CSV format |
| 4. | Weather data was fetched from Rest API every day |
| 5. | The plan was to create 3 layered Data lake house architecture |
| 6. | Final data was used by PowerBI |
| 7. | Best practices were followed while designing solutions |

</details> 

<details><summary><b>Project: Flow Diagram</b></summary>
</br>
<h4>Flow Diagram</h4>
<img class="center" alt="flow diagram" src="images_readme/Trade Fare Relational Data Model.jpg"> </img></br></br>
</details>    
