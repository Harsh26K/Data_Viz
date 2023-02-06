## Google-Play-Store-Apps
# Business Analysis
# 1. objective:
      The objective of the project is to perform data visualization techniques to understand the insight of the data of Google Play Store. This project aims to apply various Business Intelligence tools such as Tableau or Power BI to get a visual understanding of the data!

# 2. Dataset Used: 
      1.googleplaystore.csv
      2.googleplaystore_user_reviews.csv
      3.new_data.csv (custom dataset)

# 3.Data Transformation:
1.googleplaystore.csv:
      1. Column type Changed
         some columns with type text were converted to type whole number or decimal number
      2. New Columns Created
        New columns were created for convenience and to gain new relations
      3. Columns Removed
         columns: Reviews, Genres, Last updated, Current Ver., Avg. Reviews, Size(Mb) were removed because of less importance for the analysis
      4. Duplicate Rows Removed
           Duplicated rows were removed to avoid the ambiguity
      5. NULL values/Outliers handled
          NULL values were replaced by 0 for the columns and outliers were removed

2.googleplaystore_user_reviews.csv
      1. Column Type changed
          some columns with type text were converted to type decimal number
      2. New Columns Created
          New Columns were created for convenience and to gain new relations
      3. Columns Removed
           columns: translated_reviews was removed because of less importance for the analysis
      4. Duplicate Rows Removed
           Duplicated rows were removed to avoid the ambiguity
      5. NULL values/Outliers handled
          NULL values were replaced by 0 for the columns and outliers were removed

# 4. Data Analysis:
      Tool used : Power BI
      Language: Python, DAX
      Visualization : Bar chart, Line Chart, Summary,
                                Pie Chart, Area Chart, Cards, Tree 
                                Map, Slicer
      Table Relationship : Class Diagram                         





