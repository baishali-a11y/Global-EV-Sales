# Global-EV-Sales
Visual representation of the trends and patterns in electric vehicle (EV) sales and stocks over time.

About the dataset: 
This dataset appears to contain information about electric vehicles (EVs) in different regions. Here's a brief description of each column:
region: This column represents the geographical area where the data was collected. In the provided sample, the region is Australia.
category: This column categorizes the data. In the provided sample, the category is 'Historical', which might suggest that the data is historical data about electric vehicles.
parameter: This column specifies the type of data being recorded. In the provided sample, parameters include 'EV stock share', 'EV sales share', 'EV sales', and 'EV stock'.
mode: This column might represent the mode of transportation. In the provided sample, the mode is 'Cars'.
powertrain: This column likely represents the type of powertrain in the vehicle. In the provided sample, powertrains include 'EV' and 'BEV'. 'EV' stands for Electric Vehicle, and 'BEV' stands for Battery Electric Vehicle.
year: This column represents the year when the data was recorded.
unit: This column represents the unit of measurement for the value. In the provided sample, units include 'percent' and 'Vehicles'.
value: This column represents the actual data value for the given parameter, unit, and year.

Steps followed for the dashboard creation:
Here are the steps to create these charts:
Filter the data for each chart based on the parameter, such as 'EV sales', 'EV stock', 'EV sales share', and 'EV stock share'.
Group the data by the required column, such as 'year', 'region', or 'powertrain', and calculate the sum or average of the 'value' column.
Use a plotting library, such as Matplotlib or Seaborn, to create the chart. For line charts, you can use the plot function. For bar charts, you can use the bar function. For pie charts, you can use the pie function.
Customize the chart by adding a title, labels for the x-axis and y-axis, and a legend if necessary.
Repeat these steps for each chart.
Arrange the charts on the dashboard in a logical and aesthetically pleasing manner. You can use a dashboarding tool or library, such as Dash or Bokeh, to create the dashboard.

Description of few charts in the dashboard:
EV Sales and Stock Over Time Line Chart: This chart can show the trend of EV sales and stock over the years. You can create two line charts, one for sales and one for stock, with the x-axis representing the year and the y-axis representing the value. This will help in understanding how EV sales and stocks have evolved over time.
EV Sales Share and Stock Share Over Time Line Chart: Similar to the previous chart, this can show the trend of EV sales share and stock share over the years. This will help in understanding the market share of EVs over time.
EV Sales and Stock by Region Bar Chart: This chart can show the total EV sales and stock in each region. You can create two bar charts, one for sales and one for stock, with the x-axis representing the region and the y-axis representing the total value. This will help in comparing the EV market across different regions.
EV Sales and Stock by Powertrain Type Bar Chart: This chart can show the total EV sales and stock for each powertrain type. This will help in understanding the popularity of different powertrain types.
EV Sales Share and Stock Share by Region Pie Chart: This chart can show the proportion of EV sales share and stock share in each region. This will help in understanding the market dominance of different regions.
