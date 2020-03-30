# orgchart-generator
Script, data file and readme.md used to generate and orgchart using .csv data with draw.io

The following steps document how you can use draw.io to create an Org Chart.  The data that is used to populate the org chart is provided
via a .csv file.

You can use the desktop version of draw.io or the browser based version for the org chart generation.

1. Open draw.io
2. Open orgchart-generator.script using your favorite text editor.
3. Create the .csv file of the personnel you want to document in the org chart.  Specify the employee name, position, manager.  You can      leave the width and height (100, 75) as they are.
   The employee.sample file contains what the data format should look like.  Be sure to include the field names at the top of
   the file.
4. Copy the employee data at the bottom of the orgchart-generator.script.
5. In draw.io, select Arrange --> Insert --> Advanced --> CSV.  This should open a window that contains a sample script.
6. Delete the contents of the sample script and paste the contents of the orgchart-generation.script file that contains your employee
   data.
7. Select 'Import' in the lower right of the window.  The org chart should generate on the draw.io canvas.

Once the chart has been generated, you can move the boxes around using draw.io to suit how you'd like the chart to look.  Once you're
satisfied with how the chart looks, you can export the org chart as a .png or .jpg.  

There's a plug-in available here that you add to Powerpoint that allows you to insert the .drawio file: 
https://store.office.com/addinsinstallpage.aspx?rs=en-001&assetid=WA200000113 
