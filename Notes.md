1. npm i recharts
2. npm i react-icons

3. # Home

   > > ResponsiveContainer: This makes the chart responsive, meaning it adjusts its size to fit the available space.

   > > BarChart: This is the main chart component. It sets up a bar chart with a specified width (500) and height (300). It also has margins around the chart (top, right, left, and bottom).

   > > data: This is the dataset that the chart uses to display the information.

   > > CartesianGrid: This adds a grid to the chart with dashed lines, making it easier to read.

   > > XAxis and YAxis: These components add horizontal (X) and vertical (Y) axes to the chart. The X-axis uses a property called "name" from the data to label the axis.

   > > Tooltip: This adds a tooltip that appears when you hover over the bars, showing more information about the data point.

   > > Legend: This adds a legend to the chart, explaining what each color represents.

   > > Bar: These components represent the bars in the bar chart. Each Bar component displays data from the dataset. One bar shows data from the "pv" key, colored purple (#8884d8), and the other shows data from the "uv" key, colored green (#82ca9d).

4. # ChartJS.register(CategoryScale, LinearScale, BarElement, Title, Tooltip, Legend, LineElement, PointElement, Filler, zoomPlugin);
   This line is telling the Chart.js library to include certain features and components. Think of it like saying, "Hey Chart.js, I want to use these specific parts to create my charts." Here's what each part does:
   > > CategoryScale: Allows us to use categories (like names of pages) on the X-axis.
   > > LinearScale: Allows us to use numerical values on the Y-axis.
   > > BarElement: Lets us draw bar charts.
   > > Title: Lets us add titles to our charts.
   > > Tooltip: Adds tooltips that appear when you hover over parts of the chart to show more information.
   > > Legend: Adds a legend to explain what the different colors or lines represent.
   > > LineElement: Lets us draw line charts.
   > > PointElement: Lets us draw points on line charts (like dots at each data point).
   > > Filler: Allows us to fill areas under lines in a line chart.
   > > zoomPlugin: Adds the ability to zoom in and out of the charts.
