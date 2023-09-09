cereal-analysis-health
test 80 brands of cereal to analysis to determine when cereal is health or unhealthy
About this project, Lesley Brewton
Beginning cereal dataset for 80 brands of cereal: Nutrition Linear Regression
Categorical – test run - Converting Numeric Data to Categorical Data (For example, if you have a data set of people’s heights in inches, such as 49.5, 54.0 and 65.5, 
you might want to convert this numeric data into categorical data, for example 0, 1, and 2, to represent small, medium, and tall. 
Congenially, this process is sometimes called binning data.
1. Question: what does the cereal rating mean and how can you maximize it? ranking is out of 100 with the data coming back between 0  and 100.
   Note: I want to try to see if it is nutritious or not nutritious, and I want the rating to be based on health aspects.
Analyze key characteristics such as:
Type:
o  Cold
o  Hot
Calories: Calories per serving
Protein: Grams of protein
Fat: Grams of fat
Sodium: Grams of sodium (Note: The original data contains milligrams.)
Fiber: Grams of dietary fiber
Carbs: Grams of complex carbohydrates
sugars: Grams of sugars
Potassium: Grams of potassium (Note: The original data contains milligrams.)
Vitamins: Vitamins and minerals: 0, 25, or 100, indicating the typical percentage of FDA recommended. 
Rating: A rating of the cereals

2. Hypotheses and tests outcome that you should see:  Calories: Calories per serving
   Brand of cereal
   Calories in cereal from different sources
   Carbo, sugars, potassium 
   Fiber with vitamins and sodium
   The relation of serving size to amount calories
 
3. Findings: 
Key cereal characteristics:    Results:
   calories    Healthy characteristics DID have an impact
   Protein     Unhealthy characteristics like calories and sugar when adding more to cereal did have a major effect
   fat Vitamins  shows a negative impact because it came with sodium
   sodium  
   fiber   
   carbohydrates   
   sugars  
   potassium   
   vitamins    

Key interactions:
sodium correlates with vitamin content for a negative trend, and causation in blood sugar or AC1 is true positive
Carbohydrates with proteins have a positive interaction and not and interaction between vitamins and protein
vitamins and potassium neither interact nor are correlated
interaction between calories and fat yields a positive interaction for rating
To get a positive outcome on cereal nutrition we should:
1. reducing sugar in cereal while reducing overall calories
2. illuminate the amount of vitamins with sodium
3. make carbohydrates protein based

This Python 3 environment comes with many helpful analytics libraries installed
It is defined by the kaggle/python Docker image: https://github.com/kaggle/docker-python
# For example, here's several helpful packages to load

import numpy as np # linear algebra
import pandas as pd # data processing, CSV file I/O (e.g. pd.read_csv)
Input data files are available in the read-only "../input/" directory
# For example, running this (by clicking run or pressing Shift+Enter) will list all files under the input directory

import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))
