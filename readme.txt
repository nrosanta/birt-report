Reporting Dashboard features -

1. Home
	- All defects by components (bar chart)
		-> Environment based listing of defects filtered by component selected (bar chart)
			-> Defect listing by component-environment selected	(table)
			
	- All defects by components (pie chart)
		-> 
		
2. Breakdown by Priority
	- Summarized defects breakdown by priority levels i.e. low, medium, high & critical (pie charts)
		-> Defect listing by priority level selected (table)
	
3. Breakdown by Severity
	- Summarized defects breakdown by severity levels i.e. low, medium, high & critical (pie charts)
		-> Defect listing by severity level selected (table)

3. All Components By Priority
	- List all components by priority at the org level (individual pie charts by components)
		-> Defect listing by API & priority level selected (table)
	
4. All Components By Severity
	- List all components by severity at the org level (individual pie charts by components)
		-> Defect listing by API & severity level selected (table)
	
5. By Environment
	- List all defects by environment (bar chart with curve fitting line)
		-> Defect listing by environment selected (table)
	
	
	
Notes:
alert( "categoryData=" + categoryData + 
"\nvalueData=" + valueData + 
"\nvalueSeriesName=" + valueSeriesName + 
"\nlegendItemText=" + legendItemText + 
"\nlegendItemValue=" + legendItemValue + 
"\naxisLabel=" + axisLabel);
