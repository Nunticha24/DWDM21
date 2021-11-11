# DWDM21
Data Warehouse &amp; Data Mining 2021

นางสาวนันทิชา วิชิต 623020526-8

Group Name: ลูกหมี

1 **_นางสาวนันทิชา วิชิต_**

2 นางสาวมินตรา ทิพยรัตน์สุนทร 623020041-2

3 นางสาวกัลยารัตน์ แสนสมบัติ 623020513-7

4 นางสาวฐิติชญา ไกรวงค์ 623020520-0

5 นางสาวศศิกานต์ บุญมี รหัสนักศึกษา 6230205399

# สารบัญเนื้อหา

* บทที่ 1 Introduction 
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter1.pdf
    * Why Data Mining?
    * What is Data Mining?
    * Knowledge Discovery (KDD) Process
    * Data Mining Functions
      * Pattern Discovery
      * Classification
      * Cluster Analysis

* บทที่ 2 Getting to Know Your Data 
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter2.pdf
    * Types of Data Sets
      * Record Data
      * Graphs and Networks
      * Ordered Data
      * Spatial, image and multimedia Data
    * Important Characteristics of Structured Data
    * Data Objects
    * Attributes
    * Attribute Types
    * Numeric Attribute Types
    * Basic Statistical Descriptions of Data
  * https://github.com/Nunticha24/DWDM21/blob/main/Data101_(chapter2).ipynb
    * Basic python
      * Variables
      * Data structure
      * Loop
      * Condition
      * Function
  * https://github.com/Nunticha24/DWDM21/blob/main/Data102_(chapter2).ipynb
    * Data Exploratio
      * Boxplot
      * Times Series Plot
  * https://github.com/Nunticha24/DWDM21/blob/main/Data_Visualization.ipynb
    * Data Visualization
      * Scatter plot
      * Plot
      * Bar chart
        * Grouped Barchart
        * Stacked Barchart
      * Histogram
  * https://github.com/Nunticha24/DWDM21/blob/main/Distance_Numpy.ipynb
    * Distance Numpy
      * Numpy Array
        * สร้าง numpy array (matrix) จาก list
        * สร้าง matrix เริ่มต้น (zeros, ones)
        * สร้าง matrix random
        * matrix properties
        * Indexing & Slicing
        * Useful functions
      * Distance Matrix
        * Euclidean Distance (L2-norm)
        * Distance function
        * Manhattan Distance (L1-norm)
        * Distance of Binary Value

* บทที่ 3 Data Preprocessing
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter3.pdf
  * https://github.com/Nunticha24/DWDM21/blob/main/Data_Preprocessing_(chapter_3).ipynb
    * Meta Data (Data ที่ใช้อธิบาย Data)
    * ชี้ข้อมมูลในตาราง
      * ชี้แบบธรรมดาใช้ [ชื่อคอลัมน์][ชื่อindex]
      * ชี้แบบ .iloc[] (มองข้อมูลเป็นเมทริกซ์)
    * Missing Values
      * Missing Values กำจัดmissing
      * Handling Missing Value 1 (ลบค่า missing)
      * Handling Missing Value 1.5 (ลบค่า missing เฉพาะใน คอลัมล์ที่เราสนใจเท่านั้น)
      * Handling Missing Value 2 (แทนค่าด้วย class ใหม่ (unknown))
      * Handling Missing Value 3 (แทนค่าด้วย class ใหม่ (ค่าที่เหมาะสม))
      * Handling Missing Value 4 (แทนค่าด้วย ค่ากลาง)
        * ถ้าเป็น numeric ใช้ mean
        * ถ้าเป็น numeric (ตัวหนังสือ) ใช้ mode
        * ถ้าเป็น ordinal ใช้ median
      * Handling Missing Value 5 (แทนค่าด้วย ค่ากลาง ของ simple)
    * Select data by values [PD]
      * สร้าง list ของ boolean
        * นำ list ของ boolean มาเลือกค่าในตาราง
      * Handling Missing Value 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)(ต่อ)
      * การเรียงข้อมูล[PD]
    * Outlier
      * ตัด outlier แบบ manual
      * Pandas' looping (.iterrows)
    * การรวมตาราง Data Integration (ต่อตารางในแนวแกน x)
      * รวม 2 ตาราง (.merge())
      * รวม 2 ตาราง (.merge())
      * ตารางรอง (ตารางข้างขวา) ต้องไม่มี index ซ้ำ
      * Group by (pandas)
      * [PD] save ตารางเอาไปใช้ที่อื่น
      * [PD] การสร้างตาราง

* บทที่ 4 Data Warehousing and On-line Analytical Processing
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter4.pdf
    * What is a Data Warehouse?
    * From Tables and Spreadsheets to Data Cubes
    * Conceptual Modeling of Data Warehouses
      * Star Schema: An Example
      * Snowflake Schema: An Example
      * Fact Constellation: An Example
    * Typical OLAP Operations
      * Roll up (drill-up)
      * Drill down (roll down)
      * Slice and dice
      * Pivot (rotate)
      * Drill across
      * Drill through

* บทที่ 5 Association Rules
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter6.pdf
    * Basic Concepts
      * What Is Pattern Discovery?
        * k-Itemsets and Their Supports
        * Frequent Itemsets (Patterns)
        * From Frequent Itemsets to Association Rules
        * Mining Frequent Itemsets and Association Rules
    * Efficient Pattern Mining Methods
      * Apriori Algorithm
        * Apriori Pruning and Scalable Mining Methods
        * A Candidate Generation & Test Approach
        * The Apriori Algorithm
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter6_Association_Rules.ipynb
    * ลบ recodes ที่ถูก cancel ออกไป
    * เตรียม Data สำหรับ (Fequence Pattern) Association Rule
    * Apriori

* บทที่ 6 Classification
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter8.pdf
    * Basic Concepts
      * Supervised vs. Unsupervised Learning (1)
      * Supervised vs. Unsupervised Learning (2)
      * Prediction Problems: Classification vs. Numeric Prediction
      * Classification—Model Construction, Validation and Testing
    * Decision Tree Induction
      * An Example
      * Information Gain
  * https://github.com/Nunticha24/DWDM21/blob/main/Decision_Tree.pdf
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter7_Classification(Decision_Tree).ipynb
    * Load Data
    * Train Model
      * import (เรียกใช้ algorithm algorithm ที่เราต้องการ)
      * define (กำหนด parameters ให้กับ model)
      * train (ฝึกสอนตัวแบบ)
    * Plot tree
    * Evalution
      * Random
    * Advanced Tree
    * TEST
  * https://github.com/Nunticha24/DWDM21/blob/main/Lecture.pdf
    * Bayes’ Theorem: Basics
    * Naïve Bayes 
      * ClassifierCategorical vs. Continuous Valued Features
      * Training Dataset
    * Lazy Learner: Instance-Based Methods
    * The k-Nearest Neighbor Algorithm
  * https://github.com/Nunticha24/DWDM21/blob/main/Lecture19_10_64.pdf
    * Model Evaluation and Selection
    * Classifier Evaluation Metrics
      * Confusion Matrix
      * Accuracy, Error Rate,Sensitivity and Specificity
      * Precision and Recall, and F-measures
    * Neural Network for Classification
      * Perceptron
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter7Classification(KNN_NN).ipynb
    * Losd data
    * Split Data
    * Train Model
      * import
      * Knn1
      * Knn2
      * Knn3
    * Retrain & Evaluate
    * Neural Network
      * import
      * Define
      * Train - Test
      * ANN2
      * ANN3
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter7_Classification(Evaluation).ipynb
    * Load data
    * แบ่ง Data
    * สร้าง Model ทำนาย
      * import
      * Define
      * Train
    * Evaluation

* บทที่ 7 Clustering
  * https://github.com/Nunticha24/DWDM21/blob/main/Chapter8_Clustering.ipynb
    * K-means
      * Generate Data
      * Explore data
      * Clustering
        * Import
        * Define
        * Fit-Predict
        * Plot
      * Example Application (Color Quantization)
        * นับจำนวนสี
        * จัดกลุ่มสีให้เหลือ 16 สี
        * ใช้ centroid เป็นตัวแทนของสี

* MiniExam
  * https://github.com/Nunticha24/DWDM21/blob/main/MiniExam.ipynb

* Group Project
  * Slide นำเสนอ
  * https://github.com/Nunticha24/DWDM21/blob/main/Project%20%E0%B8%81%E0%B8%A5%E0%B8%B8%E0%B9%88%E0%B8%A1%E0%B8%A5%E0%B8%B9%E0%B8%81%E0%B8%AB%E0%B8%A1%E0%B8%B5.pdf
  * Group Project
    * https://github.com/Nunticha24/DWDM21/blob/main/Project_lookmhee.ipynb
  
