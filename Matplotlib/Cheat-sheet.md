# Cheat-sheet


| Syntax      | Description | Comments |
| :-----------: | :-----------: | :-----------: |
| `import matplotlib.pyplot as plt`      |  import Statement      |
| `plt.title(str_title)` | Title of the figure | |
| `plt.xlabel('Ages')` | x label | |
| `plt.ylabel('Median Salary(USD)')` | y label | |
| `plt.legend(loc='Upper Left')` | legend of the figure | loc of the legend |
| `plt.show()` | shows the plot | Final statement |
| `plt.xscale('log')`| X axis is log scalled| | 
| `plt.yscale('log')`| Y axis is lof scalled |  |
| `plt.grid(True) # This puts the grid` | Draws the grids | |
| `plt.style.available` | Available styles | |      
| `plt.style.use('ggplot')` | plots are drawn using this style | |
| `plt.fill_between(py_dev_x, py_dev_y, dev_y,where = (py_dev_y > dev_y), alpha = 0.25, label = 'Above Avg')` | Fills the space  | Condition is specified using the where |  
| `plt.plot(dev_x, dev_y, color='k', linestyle='--', marker='.', label = 'All Devs')`   | Line plot | x_values , y_vlaues , label is used for legend |
| `plt.bar(py_dev_x , py_dev_y, width = width , label = 'Python')` | `bar` plot | width of the bar can be specified  |
| `plt.barh(languages, popularity) ` | Vertical bar plots | similar to bar |
| `plt.pie(slices, labels = labels , wedgeprops={'edgecolor' : 'black'}, explode=explode, autopct = '%1.1f%%',shadow = True, startangle=90)` | Pie chart | |
| `plt.stackplot(minutes, player1, player2, player3, labels = ['Player 1', 'Player 2', 'Player 3'])` | Stack plots |  |
| `plt.hist(ages, bins = bins, edgecolor = 'black', log = True)` | Histogram | bins can be integer or list of bin edges |
| `plt.axvline(median_age, color = color, label = 'Median Age')` | Draws a vertical line in the plot | |      
| `plt.scatter(x , y , s = sizes , c =  colors , edgecolors='black', cmap ='Greens')` | Scatter plot | `sizes` and `colors` are all lists  |
| `cbar = plt.colorbar(); cbar.set_label('Color Map')` | Shows the color map on the plot | |
| `plt.plot_date(dates, y, linestyle = 'solid')` | plot dates  | |
| `plt.gcf()` | Return the current figure | |
| `plt.gca()` | Return the current axes | |
| `plt.gcf().autofmt_xdate()` | position the dates on x axis to look better | |
| `date_format = mpl_dates.DateFormatter('%b, %d %Y')`| Choose a date format  |  |
| `plt.gca().xaxis.set_major_formatter(date_format)` | Convert the dates according to that dates| |
| `fig, ax = plt.subplots(nrows = 2, ncols = 2, sharex = True)` | To draw differnt plots the OOP way |  |
| `ax.set_title('Title)` | Sets the title for that axes | See the change from plt set_ is added |
| `set_xlabel('x label')` | Sets the x label for that axes | | 
| `set_ylabel(ylabel)`| Sets the y label for that axes | |  

* To use the OOP way, replace the `plt` in all the above comands with `ax` thats it !