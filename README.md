# IS107 - Laboratory Work 1 - Introduction to Business Intelligence & Power BI
#
## PART 1: Launching Power BI & Loading Data

### Step 1: Open Power BI Desktop

* _This screenshot shows the Power BI Desktop start screen after opening the app. From here, you can load data and start making reports._
 <img width="1909" height="971" alt="Screenshot 2026-02-21 211353" src="https://github.com/user-attachments/assets/680f127c-b84c-46ca-80d6-4c69028dc687" />

### Step 2: Load the Dataset 
* _This screenshot shows how the CSV file Week1_Basic_Sales_Data.csv is imported into Power BI Desktop and loaded for analysis._
<img width="1912" height="975" alt="Screenshot 2026-02-21 212945" src="https://github.com/user-attachments/assets/389251bc-c1c0-4316-b4f0-7b62ddad444a" />

### Step 3: Verify Data in Data View 
* _This screenshot shows the dataset in Power BI’s Data View, where you can see all the columns and check or change the data type for each column if needed._
<img width="1919" height="975" alt="Screenshot 2026-02-21 213554" src="https://github.com/user-attachments/assets/f5007cc4-964b-45e4-92f1-a5b714291a82" />

**Question:**  
1. Are all columns visible?  
2. Is “Date” formatted as Date?
3. Is “Sales” formatted as Decimal Number?
   
**Answers:**  
1. Yes, all columns are visible in the Data View.
2. Yes, all data in date are formated as date
3. No, the sales is not formatted as decimal, it was formatted as whole number
   
#
## PART 2: Exploring the Interface

## Report View 
* _This screenshot displays Power BI’s Report View, where you can design reports by adding and organizing different visuals on the canvas._
<img width="1164" height="753" alt="Screenshot 2026-02-12 100100" src="https://github.com/user-attachments/assets/23e69fc0-c995-4ee9-940c-2a184dde8570" />

## Data View 
* _This screenshot shows Power BI’s Data View, where users can view and check the raw data with all rows and columns._
<img width="1919" height="975" alt="Screenshot 2026-02-21 213554" src="https://github.com/user-attachments/assets/f5007cc4-964b-45e4-92f1-a5b714291a82" />

## Model View
* _This screenshot shows Power BI’s Model View, where you can create and manage relationships between tables for better data modeling._
<img width="1880" height="953" alt="Screenshot 2026-02-21 214841" src="https://github.com/user-attachments/assets/2efa8dc2-abe1-40c6-b4eb-6a931de95f55" />

#
## PART 3: Creating Auto-Generated Visuals 

### Step 1: Quick Visualization 
* _This screenshot shows the automatic chart created when the Sales field is dragged onto the canvas, showing a quick summary of total sales._
<img width="1915" height="972" alt="Screenshot 2026-02-21 215137" src="https://github.com/user-attachments/assets/1415283f-315a-4025-b638-52928b1e5c89" />

**Question:**  
1. What type of chart was created? 
2. What does it show?

**Answers:** 
1. Cluttered column chart
2. It shows the sum of sales

### Step 2: Create a Sales by Region Chart
* _This screenshot shows a Clustered Column Chart that displays total sales for each region, making it easy to compare their performance._
<img width="1912" height="1001" alt="part3 step2" src="https://github.com/user-attachments/assets/f8437ec5-daf0-444f-a020-ed51ae88ebdb" />

**Question:**
1. Which region has highest sales?

**Answer:**
1. The region that is highest us the region West

### Step 3: Sales by Category 
* _This screenshot shows a Pie Chart illustrating sales distribution among product categories, highlighting which categories contribute the most._
<img width="540" height="347" alt="step3 pie chart" src="https://github.com/user-attachments/assets/02af27ed-6479-458b-bd4a-ba811af4321f" />

**Questions:**
1. Which category dominates?  
2. Is the distribution balanced?  

**Answers:**
1. The Electronics category dominates.  
2. The distribution is moderately balanced between the two larger categories, but overall it is not fully balanced because Office Supplies has a much smaller share.

### Step 4: Sales Over Time 
* _This screenshot shows a Line Chart displaying sales trends over time, making it easy to spot increases or decreases._
<img width="552" height="345" alt="step4 line chart" src="https://github.com/user-attachments/assets/595d98c6-63e2-47e0-b889-64b378188df5" />

**Questions:**
1.Is there growth? 
2. Any noticeable trend?  

**Answers:**
1. No, there is no growth
2. Yes, there is a downward trend

#
## PART 4: Basic Data Insight Interpretation 

**Questions:**

1. Which region contributes the most revenue?  
2. Which product category performs best?  
3. Are sales consistent across dates?  
4. What business recommendation can you suggest?  

**Answers:**

1. The West region contributes the most revenue.  
2. The Electronics category performs best.  
3. No, sales are not consistent across dates.  
4. Investigate the major drop in 2025 sales.

## LABORATORY QUESTIONS  

### Part A – Technical Questions  

1. What are the five columns in the dataset?  
2. What data type is assigned to the “Sales” column?  
3. Which Power BI view allows you to see raw data?  
4. What chart type is best for showing trends over time?  
5. What aggregation is automatically applied to Sales?  

**Answers:**

1. The five columns in the dataset are Date, Product, Category, Region, and Sales.  
2. The data type assigned to the Sales column is Decimal Number.  
3. The Table (Data) View allows you to see raw data.  
4. A Line Chart is best for showing trends over time.  
5. The Sum aggregation is automatically applied to Sales.  

---

### Part B – Analytical Questions  

6. Which region has the highest total sales?  
7. Which category has the lowest performance?  
8. Are sales increasing, decreasing, or stable?  
9. If you were a manager, which region would you prioritize?  
10. Provide one actionable recommendation based on the data.  

**Answers:**

6. The West region has the highest total sales.  
7. Office Supplies has the lowest performance among the categories.  
8. Sales are decreasing.  
9. If I were the manager, I would prioritize the North region because it has the lowest sales.  
10. Launch a targeted sales campaign in the North region to improve performance.
#
	 
# ENHANCEMENT SECTION 

## Advanced Exploration 
### Task 1: Add a Card Visualization 
* _This screenshot shows a Card visualization that displays the total sales amount._
<img width="383" height="272" alt="Screenshot 2026-02-12 102700" src="https://github.com/user-attachments/assets/587c1b95-a47f-4958-883d-e6211f4043f9" />

**Question:**
What is the total sales amount?

**Answer:**
The total sales amount is 220,000.

## Task 2: Add Slicer 
* _This screenshot shows a Slicer for the Region field, letting users filter all visuals on the report page by the selected region._
<img width="793" height="480" alt="Screenshot 2026-02-21 223502" src="https://github.com/user-attachments/assets/5de6f335-84dd-44f9-9c79-6d20c6c2d643" />

**Question:**
 1. What happens to other visuals when you click a region?
 2. Why is filtering important in BI? 

**Answer:**
1. When you click a region, all other visuals change to show data only for that region.
2. Filtering helps you focus on specific data so you can understand it faster and make better decisions.

## Task 3: Sort Sales 
* _This screenshot shows the Region chart sorted by sales from highest to lowest, making it easier to identify the top and bottom performing regions._
<img width="827" height="513" alt="Screenshot 2026-02-21 223714" src="https://github.com/user-attachments/assets/b61eb0c6-bcf8-4dfc-8933-4a785723b227" />

**Question:**
 1.Does sorting improve readability? 
 2. Why?

 **Answer:**
 1. Yes, sorting makes it easier to compare values quickly.
 2. Because it arranges the data from highest to lowest (or lowest to highest), so you can easily see the top and bottom performers.

## Task 4: Identify Outliers 

**Question:**
1. Which region is significantly higher or lower? 
2. What might explain that difference? 

**Answer:**
 1. The North region is lower compared to the others. West, East, and South are all close to 60K and performing similarly.
 2. The North may have fewer customers, stronger competitors, or fewer resources compared to the other regions.

## INSIGHT SUMMARY
1. The West region achieves the highest revenue among all regions.
2. Electronics is the best-performing product category.
3. Sales show a downward trend from 2024 to 2025.
4. Office Supplies consistently underperform compared to other categories.
5. The North region needs focused strategies to boost its sales performance.
