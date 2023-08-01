import matplotlib.pyplot as plt

# Sample data for performance and efficiency metrics
radisson_hotels = ['Hotel A', 'Hotel B', 'Hotel C', 'Hotel D', 'Hotel E']
performance_scores = [8.5, 7.9, 9.2, 8.0, 8.7]
efficiency_scores = [85, 72, 94, 80, 89]

# Create a bar chart for performance scores
plt.figure(figsize=(10, 6))
plt.bar(radisson_hotels, performance_scores, color='skyblue')
plt.xlabel('Radisson Hotels')
plt.ylabel('Performance Scores')
plt.title('Performance of Radisson Hotels')
plt.ylim(0, 10)
plt.xticks(rotation=45)
plt.grid(axis='y', linestyle='--', alpha=0.7)
plt.show()

# Create a bar chart for efficiency scores
plt.figure(figsize=(10, 6))
plt.bar(radisson_hotels, efficiency_scores, color='lightgreen')
plt.xlabel('Radisson Hotels')
plt.ylabel('Efficiency Scores (%)')
plt.title('Efficiency of Radisson Hotels')
plt.ylim(0, 100)
plt.xticks(rotation=45)
plt.grid(axis='y', linestyle='--', alpha=0.7)
plt.show()
