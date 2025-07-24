<h1>Azure Data Factory - Deployment Repository</h1>

<p>This repository contains the ARM templates and configurations for an Azure Data Factory project. It includes definitions for datasets, pipelines, linked services, and integration runtimes.</p>

<h2>📁 Repository Structure</h2>
<ul>
  <li><strong>dataset/</strong> - Contains dataset definitions used in the pipelines.</li>
  <li><strong>factory/</strong> - Factory-level configurations and metadata.</li>
  <li><strong>integrationRuntime/</strong> - Integration Runtime setup for managing compute and connectivity.</li>
  <li><strong>linkedService/</strong> - Configuration for linked services such as Azure Blob, SQL DB, etc.</li>
  <li><strong>pipeline/</strong> - Contains ADF pipeline definitions for ETL processes.</li>
  <li><strong>publish_config.json</strong> - Defines publishing settings for ADF deployment.</li>
  <li><strong>README.md</strong> - Repository documentation.</li>
</ul>

<h2>🚀 Deployment Instructions</h2>
<ol>
  <li>Clone this repository to your local environment.</li>
  <li>Use Azure Data Factory's ARM template deployment option.</li>
  <li>Modify <code>publish_config.json</code> as needed for your environment.</li>
  <li>Deploy using Azure DevOps or Azure PowerShell scripts.</li>
</ol>

<h2>✅ Best Practices</h2>
<ul>
  <li>Use separate branches for development and production deployments.</li>
  <li>Keep linked services parameterized where possible.</li>
  <li>Track changes to all objects for CI/CD traceability.</li>
</ul>

<h2>📌 Notes</h2>
<p>This repository reflects automated or manual changes to Azure Data Factory via ARM template exports. Make sure to sync changes from ADF Studio to version control regularly.</p>

<hr />
<p><em>Maintained by the Data Engineering Team</em></p>
