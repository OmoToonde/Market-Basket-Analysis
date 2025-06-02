# Market Basket Analysis with Apriori

This is a small project where I used Market Basket Analysis to find items that are often bought together. I used the Apriori algorithm for this, and everything is done in one Jupyter notebook. The goal was to keep it simple and easy to follow, especially for beginners who are just getting into data analysis or machine learning.

---

## What I Did

- Loaded a grocery transactions dataset
- Found the most commonly bought items
- Transformed the data into a format that works for market basket analysis
- Ran the Apriori algorithm to find frequent itemsets
- Generated association rules (like “if you buy X, you’ll probably also buy Y”)
- Built a small function to recommend items based on those rules

---

## How to Use

1. Open the notebook: `Market_Basket_Analysis.ipynb`
2. Make sure the dataset file `Groceries_dataset.csv` is in the same folder
3. Run the cells one by one
4. Try the `recommend_items()` function by passing an item like `"whole milk"` or `"yogurt"`

---

## Example

```python
recommend_items("whole milk")
```

Output:
```
Recommended items (consequents):
['yogurt', 'other vegetables', 'rolls/buns']
```

---

## Tools Used

- Python
- pandas
- matplotlib
- seaborn
- mlxtend (for Apriori and association rules)

---

## Notes

I kept the code and explanations as beginner friendly as possible. If you’re new to this kind of analysis, feel free to go through the notebook slowly — it’s all explained step by step.

---

## Author

Just a regular data enthusiast sharing something I learned 🙂
