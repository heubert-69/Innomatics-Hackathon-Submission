# Innomatics Submission

## 📊 Project Overview
Analysis of food delivery data combining transactional orders, user information, and restaurant details from three different source formats (CSV, JSON, SQL).

## 📁 Data Sources
- **orders.csv** - Transactional order data with order details
- **users.json** - User master data including membership tiers
- **restaurants.sql** - Restaurant information with cuisine and ratings

## 🚀 Key Analyses Performed

### 1. **Business Metrics**
- Revenue by restaurant rating ranges
- Average order value by user segments
- Order distribution across cities

### 2. **Customer Insights**
- Gold member behavior analysis
- City-wise spending patterns
- Restaurant preference analysis

### 3. **Performance Analysis**
- Highest revenue generating cuisines
- Restaurant performance by rating
- Seasonal revenue trends

## 🔧 Technical Implementation

### Data Processing Steps
```python
1. Load orders.csv using pd.read_csv()
2. Load users.json using pd.read_json()  
3. Load restaurants.sql using SQLite + pd.read_sql()
4. Merge datasets using user_id and restaurant_id keys
5. Perform analytical queries and aggregations
```
