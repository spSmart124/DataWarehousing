# Why Data warehousing

A data warehouse (DW) is a repository that stores relational data that is organized, cleansed, and standardized for enterprise use. A data warehouse is organized by subject-oriented databases and is non-volatile in direct support of decision support system (DSS) functionality. In so doing, a data warehouse includes strategically selected data that is important to an enterprise for historical tracking, reporting, and analysis.

A data warehouse has the following characteristics:

* __Subject-oriented__: data is theme- or object-based (i.e., customer, product, sales, etc.)

* __Integrated__: disparate data is combined and normalized from source systems

* __Time-variant__: data is organized by various time intervals for historical reporting and preservation (i.e., week, month, quarter, year)

* __Non-volatile__: data is never changed or deleted; data is read-only and refreshed at well-defined time intervals

* __Summarized__: data is often aggregated for optimization of reporting

A data warehouse should include metadata, which is “data that describes data.” Metadata often includes data location, data structure, and parameters of valid values. Essentially, metadata acts as “a living dictionary” and documentation for the data warehouse.

The need for data warehousing becomes evident when we understand that data is everywhere. Many organizations utilize disparate means and systems for collecting data. A data warehouse extracts data from these disparate source systems, which may include point-of-sale (POS), enterprise resource planning (ERP), customer relationship management (CRM), etc. The extract, transform, load (ETL) process, which will be discussed later in this module, prepares and normalizes the extracted data for analysis and reporting. In addition, a data warehouse allows for the tracking and maintenance of historical information, and provides a single source of truth.