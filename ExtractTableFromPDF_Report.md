# Extract Chart from PDF

### Mission Description
Table detection is carried out by layout and content analysis of documents. Tables have varying layout and variety of encodings. Because of this reason, writing a general algorithm for table detection is very hard.


### Difficulties
##### 1. Without ruling lines
![demo](C:\Users\bkuang\Desktop\s49.png)
##### 2. Spanning across multiple columns
![demo](C:\Users\bkuang\Desktop\s1.png)
tabula package extract result:
![demo](C:\Users\bkuang\Desktop\s11.png)
##### 3. Side by side tables
![demo](C:\Users\bkuang\Desktop\s3.png)
tabula package extract result:
![demo](C:\Users\bkuang\Desktop\s33.png)
##### 4. Multiple Tables appear in single page

![demo](C:\Users\bkuang\Desktop\s0.png)
![demo](C:\Users\bkuang\Desktop\s00.png)
##### 5. Tables across two pages
![demo](C:\Users\bkuang\Desktop\s4.png)


### Current Proposed Method
##### 1. Package reengineering
Simple wrapper of tabula-java: extract table from PDF into pandas DataFrame.

Github link : [tabula-py](https://github.com/chezou/tabula-py)
##### 2. Neural Network
Paper:
* [Table Detection Using Deep Learning](https://www.researchgate.net/publication/320243569)

### Practical Plan
