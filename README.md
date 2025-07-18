Healthcare EMR Data Ingestion Pipeline using Azure Data Factory
Designed and implemented a metadata-driven pipeline in Azure Data Factory to ingest EMR data from Azure Data Lake into the Landing zone. The pipeline supports both full and incremental loads based on configuration, performs file existence checks, archives processed files, and logs all activities for traceability. It uses parameterized datasets for flexibility and is part of a medallion architecture feeding into downstream Bronze, Silver, and Gold layers.


<img width="722" height="372" alt="Screenshot 2025-07-18 at 11 37 24 AM" src="https://github.com/user-attachments/assets/66e35b26-dab8-4341-b968-d479b5ac5941" />
