# Business-Intelligence-Solutions

Project Description:
This project is a fully automated BI solution for Pulling huge data from snowflake and sftp to other sites. This process involves Qc automation process, Data extraction process, Zipping process, Sftp of data and Email alerts system. 

QC Involves:
1. In this process, before extracting data, first current report is pulled and compared with previously sent report and a comparion report is prepared using using Python Pandas. On this comparision report, lot of business rules are applied to check if there are any business or data anamolies. If there are anamolies, detailed are emailed to stakeholders. If there are no anamolies data is extracted from snowflake, zipped, sent to sftp location and email is sent to respective respective stakeholders.

Steps to use:
1. Som_Data_Main_Bat.bat



