# Task 1 – Iris Dataset: Data Exploration & Visualization

## Objective
To understand and analyze the structure and patterns in the Iris dataset using Python, and visualize relationships between flower attributes across species.


##  Dataset Description

The Iris dataset consists of **150 records** of iris flowers from **3 species**:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each record includes:
- **SepalLengthCm**
- **SepalWidthCm**
- **PetalLengthCm**
- **PetalWidthCm**
- **Species** (target class)

##  What I Did

1. **Loaded the dataset** using `pandas.read_csv()` from the input folder.
2. **Inspected the structure** using `.shape`, `.columns`, `.head()` and `.describe()`.
3. **Created visualizations** using `matplotlib` and `seaborn`:
   - Scatter Plot: Sepal Length vs Petal Length by Species
   - Histogram: Petal Width distribution
   - Box Plot: Sepal Width across species
4. **Summarized insights** based on visual patterns and class differences.


##  Visual Insights

- **Setosa** has the smallest petals, clearly separated from the other species.
- **Versicolor** and **Virginica** overlap slightly but show distinguishable trends.
- Sepal width varies more within Setosa, as shown by the box plot.


## Tools Used

| Tool            | Purpose                       |
|-----------------|-------------------------------|
| **Pandas**      | Data loading and inspection   |
| **Matplotlib**  | Plotting graphs               |
| **Seaborn**     | Advanced visualizations       |




