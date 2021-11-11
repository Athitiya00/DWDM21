# DWDM21
**Data Warehouse &amp; Data Mining 2021**

**นางสาวอาธิติยา ธรรมวงษา 623021058-0**

_ชื่อกลุ่ม_ : **แมวส้มสร้างตัว**

1 นางสาวอาธิติยา ธรรมวงษา

2 นางสาววานิตา สมเด็จ 

3 นายคำแสน แก้วพิภพ

4 นายจิตรกร จันทะสี

5 นางสาวกรกนก สังฆพันธ์

# สารบัญ

* บทที่ 1 Introduction
  * [Introduction](https://github.com/Athitiya00/DWDM21/blob/main/Chapter1.pdf)
    * Why Data Mining?    
    * What is Data Mining?    
    * Knowledge Discovery (KDD) Process     
    * Data Mining Functions	       
       * Pattern Discovery	       
       * Classification       
       * Cluster Analysis
      
* บทที่ 2 Getting to Know Your Data
  * [Data Objects and Attribute Types](https://github.com/Athitiya00/DWDM21/blob/main/Chapter2.pdf)
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
  * [Measuring Data Similarity and Dissimilarity](https://github.com/Athitiya00/DWDM21/blob/main/chapter2%E0%B9%80%E0%B8%9E%E0%B8%B4%E0%B9%88%E0%B8%A1.pdf)
    * Similarity, Dissimilarity, and Proximity
    * Data Matrix and Dissimilarity Matrix
    * Standardizing Numeric Data
    * Special Cases of Minkowski Distance
  * [Basic Python](https://github.com/Athitiya00/DWDM21/blob/main/Data101(Chapter2).ipynb)
    * Casting int() float() str() 
    * Data Structure 
      * string คือ list ของตัวหนังสือ
      * วิธีสร้าง list ว่าง
         * การเติมค่าเข้าใน list (.append()) 
         * การชี้ค่า list (indexing) 
      * list slicing 
      * list+list 
      * format string
    * Loop 
      * Nested loop 
    * Condition (if statement) 
      * Quiz 1 หา min 
      * เฉลยquiz1 
      * HW ตัดเกรด 
    * Function 
      * Example1 
      * Example2 (ไม่มี input) 
      * Example 3 (ไม่มี output) 
      * Example 4 (ไม่มี input และ output)
      * ลักษณะของ input(paremeter,argument)
  * [Pandas](https://github.com/Athitiya00/DWDM21/blob/main/Data102(Chapter2).ipynb)
    * Read Data
      * .head() .tail() 
    * Box plot
    * Time Series Plot
  * [Visualization](https://github.com/Athitiya00/DWDM21/blob/main/Data_Visualization.ipynb)
    * Scatter plot
    * Plot
    * Quiz กลุ่ม III วาดภาพที่มี marker เป็น สี่เหลี่ยมจัตุรัส เส้นเป็นเส้นประสลับจุดไข่ปลา สีฟ้าอ่อน
    * Bar Chart กราฟแท่ง
      * Grouped Barchart ใช้เปรียบเทียบกลุ่มย่อยในกลุ่มใหญ่
      * Stacked Barchart เปรียบเทียบข้ามกลุ่ม
    * Histogram
  * [Distance_Numpy](https://github.com/Athitiya00/DWDM21/blob/main/Distance_Numpy.ipynb)
    * Numpy array
      * สร้าง numpy array (matrix) จาก list
        * matrix transpose
      * สร้าง matrix เริ่มต้น (zeros, ones)
      * สร้าง matrix random
        * matix properties
      * Indexing&Slicing
      * Useful functions
      * วนลูปเอง
    * Distance Matrix
      * Euclidean Distance (L2-norm)
      * Distance function
      * Manhattan Distance (L1-norm)
      * Distance of Binary Value

* บทที่ 3 Data Preprocessing
  * [Lecture Data Preprocessing](https://github.com/Athitiya00/DWDM21/blob/main/Chapter-3.pdf)
  * [Data Preprocessing](https://github.com/Athitiya00/DWDM21/blob/main/Data_Preprocessing_(Chapter_3).ipynb)
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
        
        
        
        
        
        
        
        
        
        
        
        




