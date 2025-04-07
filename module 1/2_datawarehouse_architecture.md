#Data Warehousing Architectures

Data warehouses can be architected using varying approaches. There are two primary approaches: the dimensional approach (popularized by Ralph Kimball) and the normalized approach (popularized by Bill Inmon).

## Dimensional Approach
Kimball’s approach depicts a data warehouse via a dimensional model (star schema or snowflake). (These models will be discussed further in Module 2 of this course.) The dimensional approach uses a “bottom-up” design, in which individual data marts are created at the departmental or organizational level (i.e., sales, human resources, finance, etc.) and built up to an enterprise data warehouse (EDW). Today, Kimball’s approach is more popular because business users can quickly gain usefulness from it.

## Normalized Approach
Inmon, on the other hand, utilized a “top-down” approach to normalize a data warehouse. The normalized enterprise data model creates a central repository or enterprise data warehouse. Dimensional data marts for specific departments or organizational units can be created from the master enterprise data warehouse. 