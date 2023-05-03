# notebook_for_staff
Data exploration for staff database
## This is the title

# Numpy Data Frames

This repository contains code for creating and manipulating data frames using the Numpy and Pandas libraries in Python. The following files can be found in this repository:

- `numpy_data_frames.ipynb`: Jupyter Notebook containing code for creating and manipulating data frames using Numpy and Pandas libraries in Python.
- `README.md`: this file

## Libraries used

- Numpy
- Pandas
- Matplotlib

## Usage

To run the code in the `numpy_data_frames.ipynb` notebook, follow the instructions below:

1. Install the necessary libraries by running `!pip install numpy pandas matplotlib`.
2. Open the `numpy_data_frames.ipynb` file in Jupyter Notebook or Jupyter Lab.
3. Run the cells in the notebook in order.

## Examples

### Pie chart

The following code creates a pie chart using the data in the `salary` and `staff_name` arrays:

```python
# concat labels 
new_label = []

for each_item in range (len(salary)):
    
    new_label.append(str(staff_name[each_item]) + '\n:£' + str(salary[each_item]))
    
pl.pie(salary, labels = new_label, counterclock = False, startangle = 90, rotatelabels=True)
pl.show()
```

### Bar chart

The following code creates a bar chart using the data in the `salary` and `staff_name` arrays:

```python
pl.bar(staff_name,salary, color=(0,0.6,0.4,0.9))
```

### Line chart

The following code creates a line chart using the data in the `profit`, `cogs`, `sales`, and `staff_name` arrays:

```python
pl.plot(prof_arr, cogs_arr,)
pl.plot(prof_arr,sales_arr)
pl.legend(['cogs', 'sales'])
pl.title('Relationship Between Profit COGS and Sales at Profit Points')
pl.ylabel('Cogs and Sales in £')
pl.xlabel('Profit in £')
pl.show()
```

## Credits

This code was written by [your name].