# Apache Iceberg Optimization Resources

At e6data, we are big admirers of Apache Iceberg. We're witnessing a steep increase in its adoption, with our customers running E6data's query engine for heavy workloads.

While we were scrambling for resources on the internet to optimize Iceberg, why not curate it for the rest of the community?

Here's a curated collection of links, guides, and insights to help you discover the best practices for optimizing your Iceberg tables.

---

## Resources

### General Optimization Strategies

- **[Optimization Strategies for Iceberg Tables by Cloudera](https://blog.cloudera.com/optimization-strategies-for-iceberg-tables/)**  
  An overview of strategies to optimize Iceberg table performance, including partitioning, file format selection, and maintenance.

- **[Best Practices for Optimizing Apache Iceberg Workloads by AWS](https://docs.aws.amazon.com/prescriptive-guidance/latest/apache-iceberg-on-aws/best-practices-general.html)**  
  General best practices for improving Iceberg workloads in AWS environments.

- **[How Amazon Ads Uses Iceberg Optimizations to Accelerate Their Spark Workload on Amazon S3](https://aws.amazon.com/blogs/storage/how-amazon-ads-uses-iceberg-optimizations-to-accelerate-their-spark-workload-on-amazon-s3/#:~:text=Improve%20operational%20efficiencies,in%20Amazon%20EMR)**  
  A case study on how Amazon Ads leverages Iceberg optimizations to enhance Spark workloads on Amazon S3.

- **[Improve Operational Efficiencies of Apache Iceberg Tables Built on Amazon S3 Data Lakes](https://aws.amazon.com/blogs/big-data/improve-operational-efficiencies-of-apache-iceberg-tables-built-on-amazon-s3-data-lakes/)**  
  Insights into enhancing the operational efficiency of Iceberg tables within Amazon S3 data lakes.

---

### Partitioning, Indexing, and Sorting

#### Partitioning and Indexing

- **[Partitioning and Indexing in Apache Iceberg by IOMETE](https://iomete.com/the-ultimate-guide-to-apache-iceberg#chapter-6-partitioning-and-indexing-in-apache-iceberg)**  
  A guide to leveraging partitioning and indexing for improved query performance in Iceberg tables.

- **[Iceberg 101: A Guide to Iceberg Partitioning by Upsolver](https://www.upsolver.com/blog/iceberg-partitioning)**  
  Learn the basics and advanced techniques for partitioning Iceberg tables.

- **[Improving Performance with Iceberg Sorted Tables by Starburst](https://www.starburst.io/blog/improving-performance-with-iceberg-sorted-tables/)**  
  Techniques for improving query performance using sorted tables in Iceberg.

- **[How Z-Ordering in Apache Iceberg Helps Improve Performance by Dremio](https://youtube.com/playlist?list=PLPDk_Pd6K17ZzRspOnOnZF9lYd4aPn0nB&si=ZhKNO_43Vy9_BUR0)**  
  Video series explaining how Z-ordering optimizes data layout for Iceberg tables.

- **[Z-Order Sorting During Compaction by IOMETE](https://iomete.com/resources/blog/z-order-sorting)**  
  A detailed blog on the role of Z-order sorting during compaction.

---

### Compaction and Maintenance

- **[Compaction in Apache Iceberg: Fine-Tuning Your Iceberg Table’s Data Files by Dremio](https://www.dremio.com/blog/compaction-in-apache-iceberg-fine-tuning-your-iceberg-tables-data-files/)**  
  Insights into compacting small files into larger ones for better performance and storage efficiency.

- **[Maintaining Tables by Using Compaction by AWS](https://docs.aws.amazon.com/prescriptive-guidance/latest/apache-iceberg-on-aws/best-practices-compaction.html)**  
  Best practices for maintaining Iceberg tables through compaction.

---

### Performance Optimization

#### General Tips

- **[Iceberg 101: Ten Tips to Optimize Performance by Upsolver](https://www.upsolver.com/blog/optimize-iceberg-performance)**  
  Ten actionable tips to enhance the performance of Iceberg tables.

- **[Amazon EMR 7.1 Runtime for Apache Spark and Iceberg Can Run Spark Workloads 2.7 Times Faster Than Apache Spark 3.5.1 and Iceberg 1.5.2](https://aws.amazon.com/blogs/big-data/amazon-emr-7-1-runtime-for-apache-spark-and-iceberg-can-run-spark-workloads-2-7-times-faster-than-apache-spark-3-5-1-and-iceberg-1-5-2/)**  
  Details on how Amazon EMR's runtime optimizations significantly speed up Spark workloads using Iceberg.

#### Read Optimization

- **[Optimizing Read Performance by AWS](https://docs.aws.amazon.com/prescriptive-guidance/latest/apache-iceberg-on-aws/best-practices-read.html)**  
  Guidelines for optimizing read performance when working with Iceberg tables.

- **[Accelerate Query Performance with Apache Iceberg Statistics on the AWS Glue Data Catalog](https://aws.amazon.com/blogs/big-data/accelerate-query-performance-with-apache-iceberg-statistics-on-the-aws-glue-data-catalog/)**  
  How leveraging Iceberg statistics within AWS Glue Data Catalog can speed up query performance.

#### Write Optimization

- **[Optimizing Write Performance by AWS](https://docs.aws.amazon.com/prescriptive-guidance/latest/apache-iceberg-on-aws/best-practices-write.html)**  
  Strategies for ensuring write operations are efficient in Iceberg workloads.

---

### Storage Optimization

- **[Optimizing Storage by AWS](https://docs.aws.amazon.com/prescriptive-guidance/latest/apache-iceberg-on-aws/best-practices-storage.html)**  
  Tips for reducing storage costs and improving efficiency when using Iceberg tables.

- **[Manage and Optimize Iceberg Tables for Efficient Data Storage and Querying by AWS](https://repost.aws/knowledge-center/glue-optimize-iceberg-tables-data-storage-query)**  
  A guide to managing Iceberg tables for both storage and query efficiency.

---

### Official Documentation

- **[Apache Iceberg Official Documentation (v1.6.0)](https://iceberg.apache.org/docs/1.6.0/performance/)**  
  Detailed technical documentation covering Iceberg table performance optimization.

---

## Miscellaneous

### Contributing

Feel free to contribute to this resource list by suggesting additional articles, tools, or best practices for Apache Iceberg.

---

