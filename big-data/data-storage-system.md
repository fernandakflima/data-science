# The V for Volume in Big Data

The V for Volume is critical in Big Data

- How are we going to store large sets of data?
- How will we access large sets of stored data?
- Do we really need to store everything?

## How do we store Big Data?

In general, storage can be done based on the following rule:

1. Is the data structured or can it be structured before storage?

- So we use a Data Warehouse!

2. Is the data unstructured or cannot be structured before storage?

- So we use a Data Lake or a Data Store!

## Relational Database

Relational databases are structured databases with a well-defined schema (data organization).

The schema is defined and created before data is stored.

A Data Warehouse is created with some relational database technology such as Managed Database System - Oracle, IBM DB2, Microsoft SQL Server, MySQL, PostgreSQL, etc.

In a relational database, data is organized into tables that relate to each other.

### Data Warehouse

A Data Warehouse (DW) is a storage system that connects and harmonizes large amounts of data from many different sources.

Its goal is to power business intelligence, reporting and analytics and support business requirements, so that companies can transform their data into insights and make intelligent data-drive decisions.

DWs store current and historical data in a single place and act as the single source of reliable information for an organization.

Data flows into a DW from transactional systems such as ERp and CRM, databases and external sources such as partner systems, IoT devices, social media applications - generally on a regular cadence.

In recent years, data storage locations have shitfted from traditional on-premises infrastructure to multiple locations, including private cloud and public cloud.

The schema must be defined before the data storage process.

Modern DWs are designed to handle structured and unstructured data such as videos, image files, and sensor data, although Data Lakes are still better options for unstructured data.

Some leverage integrated analytics and in-memory database technology to provide real-time access to trusted data and drive decision-making.

Without DW it is very difficult to combine data from heterogenous sources, ensure it is the right format for analysis, and obtain a current, long-range view of the data over time.

**Benefits**

- Better businss analytics: With DW, decision makers have access to data from multiple sources and no longer need to make decisions based on incomplete information.

- Faster queries: DW are purpose-built for fast data retrieval and analysis. With a DW, you can quickly query large amounts of consolidated data with little or no IT support.

- Improved data quality: Before being loaded into DW, data geos through a cleaning process ensuring that data is transformed into a consistent format to support analysis and decisions based on accurate, high-quality data.

- Historical view: By storing rich historical data, a DW allows decision makers to leran from past trends and challenges, make predictions and drive continuous business improvement.

### Data Lake