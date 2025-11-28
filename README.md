# HDX Tabular Data Endpoints Quickstart

This repository contains a Jupyter Notebook using Python and a PowerQuery script that demonstrates how to interact with the [HDX Tabular Data Endpoints](https://un-ocha-centre-for-humanitarian.gitbook.io/hdx-docs/build-with-hdx/build-with-hdx/hdx-api/tabular-data-endpoints). It is a simple hands on guide for testing queries, exploring data, and learning how to programmatically access tabular data resources on HDX. You can use it as inspiration for incorporating HDX data resources into your own workflows.

For more information, please refer to the HDX documentation or reach out using the contact details below.

## Contents
- **hdx_tabular_data_endpoints.ipynb** This Jupyter notebook walks through how to:
  - Connect to the Tabular Data endpoints (schema information, native, and SQL)
  - Run queries and retrieve data
  - Explore responses with `pandas`
  - Adapt the code for other HDX datasets
- **power_query.txt** This text file can be pasted into Power BI or other PowerQuery based tools to connect to the Tabular Data endpoints. It requires configuring the token and `resource_id`.

## Requirements
- Python 3.8+
- Jupyter Notebook
- Python libraries:
  - `pandas`
  - `requests`
- HDX API Token (see information [here](https://un-ocha-centre-for-humanitarian.gitbook.io/hdx-docs/build-with-hdx/build-with-hdx/overview/hdx-core-concepts))

Install dependencies with:

```
pip install pandas requests jupyter
```

## How to use

1. Clone this repository:
```
git clone https://github.com/OCHA-DAP/hdx-tabular-data-endpoints-notebook.git
cd hdx-tabular-data-endpoints-notebook
```

2. Launch Jupyter:
```
jupyter notebook
```

3. Open **hdx_tabular_data_endpoints.ipynb** and follow the instructions cell by cell.

## Questions?
Contributions, improvements, or additional dataset examples are always welcome! Please reach out to HDX by emailing [hdx@un.org](mailto:hdx@un.org).