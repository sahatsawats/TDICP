# TDICP
Tollway Data Integration and Consolidation Pipeline (TDICP)


Project Overview:

The Tollway Data Integration and Consolidation Pipeline (TDICP) is a data engineering project that aims to extract, transform, and load tollway data from various formats into a centralized database. The project leverages Apache Airflow as the workflow management system and PostgreSQL as the database technology.


Objective:

The primary objective of the TDICP project is to integrate and consolidate tollway data from open government data with various format includes csv, tsv, and fixed-length format. The project streamlines the data ingestion process, performs necessary data transformations and partitioning, and consolidates the data into a unified format for efficient storage and analysis.


Key Components & Step:

1. Data Extraction:  In this project focus on extract the data from various file formats.
2. Data Transformation:  The extracted data undergoes necessary transformations which in this project will be focus on the data partioning.
3. Data Consolidation:  The consolidation process is the necessary point to consolodate the data into a single file for ensuring consistent data structure.
4. Workflow Management:  Apache Airflow is the tool to manage end-to-end data process pipeline, scheduling tasks, and ensuring the seamless execution of data integration and consolidation steps.
5. Data Loading:  In this project we used prosgreSQL database for efficient storage, easy retrieval, and further analytics.
6. Docker Containers:  Docker provides a consistent and isolated environment, simplifying deployment and ensuring portability across different systems.
