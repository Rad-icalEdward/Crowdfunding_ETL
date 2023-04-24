# Crowdfunding_ETL
<strong>Module 13 Project 2 Extract, Load, Transform challenge for Data Analytics Bootcamp</strong>

<strong>FILES</strong>
<ul>
<li>ETL_Mini_Project_JBegley_VStyles.ipynb (<em>File</em>)
<li>Resources (<em>Directory</em>) - contacts.csv (<em>File</em>), contacts.xlsx (<em>File</em>), crowdfunding.csv (<em>File</em>), crowdfunding.xlsx (<em>File</em>), category.csv (<em>File</em>), subcategory.csv (<em>File</em>), campaign.csv (<em>File</em>)
<li>.ipynb_checkpoints (<em>Directory</em>) - ETL_Mini_Project_JBegley_VStyles-checkpoint.ipynb (<em>File</em>)</li>
</ul>

<strong>REQUIREMENTS</strong>
<ul>
<li>Create the Category and Subcategory DataFrames (30 points)
<li>Create the Campaign DataFrame (30 points)
<li>Create the Contacts DataFrame (15 points) - Option 1: Use Python dictionary methods
<li>Create the Crowdfunding Database (25 points)
</li>
</ul>

<strong>THE STEPS WE TOOK</strong><br>

PART 1: Create the Category and Subcategory DataFrames

1. Extract and transform the crowdfunding.xlsx Excel data to create a category DataFrame that has the following columns:

A "category_id" column that has entries going sequentially from "cat1" to "catn", where n is the number of unique categories,

A "category" column that contains only the category titles.

2. Export the category DataFrame as category.csv

3. Extract and transform the crowdfunding.xlsx Excel data to create a subcategory DataFrame that has the following columns:

A "subcategory_id" column that has entries going sequentially from "subcat1" to "subcatn", where n is the number of unique subcategories,

A "subcategory" column that contains only the subcategory titles.

4. Export the subcategory DataFrame as subcategory.csv

PART 2: Create the Contacts DataFrame






<strong>ERD</strong><br>
![crowdfunding_ERD](https://user-images.githubusercontent.com/121570218/234084392-2ce36440-ca9e-44f7-a748-0368ac8efc44.png)
