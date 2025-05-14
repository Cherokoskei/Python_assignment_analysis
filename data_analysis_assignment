# 1. Line Chart: Simulating a trend (not time series, but index vs. petal length)
plt.figure(figsize=(8, 4))
plt.plot(df.index, df['petal length (cm)'], label='Petal Length')
plt.title('Petal Length over Sample Index')
plt.xlabel('Sample Index')
plt.ylabel('Petal Length (cm)')
plt.legend()
plt.savefig('line_chart.png')  # Save the line chart
plt.show()

# 2. Bar Chart: Average petal length per species
plt.figure(figsize=(6, 4))
sns.barplot(x='species', y='petal length (cm)', data=df, ci=None)
plt.title('Average Petal Length per Species')
plt.xlabel('Species')
plt.ylabel('Petal Length (cm)')
plt.savefig('bar_chart.png')  # Save the bar chart
plt.show()

# 3. Histogram: Distribution of sepal width
plt.figure(figsize=(6, 4))
plt.hist(df['sepal width (cm)'], bins=10, color='skyblue', edgecolor='black')
plt.title('Distribution of Sepal Width')
plt.xlabel('Sepal Width (cm)')
plt.ylabel('Frequency')
plt.savefig('histogram.png')  # Save the histogram
plt.show()

# 4. Scatter Plot: Sepal Length vs Petal Length
plt.figure(figsize=(6, 4))
sns.scatterplot(x='sepal length (cm)', y='petal length (cm)', hue='species', data=df)
plt.title('Sepal Length vs Petal Length')
plt.xlabel('Sepal Length (cm)')
plt.ylabel('Petal Length (cm)')
plt.legend()
plt.savefig('scatter_plot.png')  # Save the scatter plot
plt.show()