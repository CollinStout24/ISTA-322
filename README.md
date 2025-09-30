# ISTA-322
This is my final project for ISTA 322 - Data Engineering with the University of Arizona. Full ETL on data from multiple sources, using Python, Pandas, PostgreSQL and AWS S3.

Purpose

The purpose of this final project is to join data sources from across the web from the 
National Center for Educational Statistics' (NCES) Integrated Postsecondary Education Data System (IPEDS) 
public data, as well as data from the State Higher Education Finance (SHEF), 
which is compiled by the State Higher Education Executive Officers Association (SHEEO).

What questions can this RDB answer?


*   Does a states' capacity to fund higher education have a statistically significant effect on retention/graduation outcomes for students?
*   Similarly, does a states' overall student tuition share have an impact on retention/graduation outcomes?
* What are the differences between a states capacity to fund higher education and actual percentage of aid via budget allocation and does that have an impact on retention.graduation outcomes?

Who will the end user of this RDB be?

* This RDB can be used by advocacy groups or state governments to help show the relationship between state funding 
and retention/graduation outcomes for students. Thus, they could potentially advocate for increased funding at higher education institutions.  

Data Sources

[Urban Institute - IPEDS Data](https://educationdata.urban.org/documentation/colleges.html#ipeds_institutional-characteristics)
* Specific reports:
  *   IPEDS Institutional Characteristics
  *   Fall Retention
  *   Graduation Rate (200%)

[SHEEO SHEF Data](https://shef.sheeo.org/data-downloads/)
* Specific Reports:
  *   State Effort Capacity
  *   Overall Report Data
