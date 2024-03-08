# Data Engineering

This repository contains resources to learn Data Engineering concepts

**What Is Data Engineering?**
<br/>Data engineering is the process of designing and building systems that let people collect and analyze raw data from multiple sources and formats. These systems empower people to find practical applications of the data, which businesses can use to thrive.
<!--- Diagram-->

**Why Is Data Engineering Important?**
<br/>Businesses, regardless of their size, are often faced with the daunting task of sifting through vast amounts of diverse data to address crucial inquiries. Data engineering is crafted to facilitate this process, enabling data consumers such as analysts, data scientists, and executives to thoroughly, swiftly, and securely examine all available data.

Analyzing data poses challenges due to its management across various technologies and diverse storage structures. However, analysis tools typically assume uniformity in data management and storage, leading to complications for those seeking insights into business performance.

Take, for instance, the multitude of customer data collected by a brand:

- Billing and shipping information reside in one system.
- Order history is maintained by another system.
- Customer support, behavioral data, and third-party information are stored in separate systems.

While collectively providing a holistic view of the customer, these disparate datasets operate independently, making it exceedingly difficult to answer specific questions, such as identifying which types of orders incur the highest customer support costs.

Data engineering addresses this challenge by integrating these disparate datasets, enabling swift and efficient retrieval of insights.

**What Do Data Engineers Do?**
The demand for data engineering skills is on the rise, with data engineers being pivotal in designing systems that streamline data integration and facilitate navigation. Data engineers undertake a variety of tasks, including:

- **Acquisition:** Identifying diverse datasets across the organization.
- **Cleansing:** Identifying and rectifying errors within the data.
- **Conversion:** Standardizing data into a uniform format.
- **Disambiguation:** Resolving ambiguous interpretations of data.
- **Deduplication:** Eliminating redundant instances of data.

Following these processes, data is often stored in a centralized repository like a data lake or data lakehouse. Additionally, data engineers may selectively copy and transfer subsets of data into a data warehouse.

**Why Does Data Need Processing through Data Engineering?**
Data engineers play a pivotal role in shaping, operating, and supporting the increasingly intricate infrastructures powering modern data analytics. Traditionally, they meticulously crafted data warehouse schemas, optimizing table structures and indexes to swiftly process queries and ensure optimal performance. However, with the emergence of data lakes, data engineers face the challenge of managing and delivering larger volumes of data to downstream consumers for analysis. Data residing in data lakes often lacks structure and formatting, necessitating attention from data engineers to unlock its value for the business.

Thankfully, once data sets undergo thorough cleaning and formatting through data engineering, they become more accessible and comprehensible. Given the continuous influx of data generated by businesses, leveraging software capable of automating these processes is essential.

An adept software stack can extract extensive insights and value from data, facilitating end-to-end data journeys termed as 'data pipelines.' As data traverses these pipelines, it may undergo multiple transformations, enrichments, and summarizations. There are four key phases of the data pipeline that data engineering directly deals with:

- **Ingestion:** This is the task of gathering data. Depending on the number of data sources, , this task can be focused or large-scale.
- **Processing:** During this phase, ingested data is sorted to achieve a specific set of data to analyze.  For large data sets, this is commonly done using a distributed computing platform for scalability.
- **StoringL** This takes the results of the processing and saves the data for fast and easy retrieval. The effectiveness of this phase relies on a sound database management system - which can be on premise or in the cloud
- **Access:** Once in place, the data is available to users with access.  

**Data Engineering Tools and Skills**
Data engineers use many different tools to work with data. They use a specialized skill set to create end-to-end data pipelines that move data from source systems to target destinations.

Data engineers work with a variety of tools and technologies, including:

- **ETL Tools:** ETL (extract, transform, load) tools move data between systems. They access data, then apply rules to “transform” the data through steps that make it more suitable for analysis.
- **SQL:** Structured Query Language (SQL) is the standard language for querying relational databases.
- **Python:** Python is a general programming language. Data engineers may choose to use Python for ETL tasks.
- **Cloud Data Storage:** Including Amazon S3, Azure Data Lake Storage (ADLS), Google Cloud Storage, etc.
- **Query Engines:** Engines(like Spark, Flink, etc) run queries against data to return answers.

**References**
- https://www.dremio.com/blog/
- https://www.databricks.com/blog
- https://news.apache.org/
