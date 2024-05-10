# PowerBI Demo: Store Sales

## Data Source

The data was obtained from Microsoft's "Store Sales" PowerBI sample file: [https://github.com/microsoft/powerbi-desktop-samples/blob/main/new-power-bi-service-samples/Store%20Sales.pbix](https://github.com/microsoft/powerbi-desktop-samples/blob/main/new-power-bi-service-samples/Store%20Sales.pbix)

## Process

### Inspection

I first inspected the content of the data as well as the data model (relationships between the tables). 

### DAX Measurements

Next, I created custom measures using DAX (specifically the "Total Sales Dollars," "Total Units Sold," "Average Sales Dollars Per Store," "Average Units Sold Per Store," and "Average Sales Dollars Per Unit Sold" measures for the "Sales" table as well as the "Number of Stores" and "Number of Territories" measures for the "Store" table). These measures were calculated separately from the measures already existing in the file upon download (in fact, the pre-existing measures in the "Sales" table were deleted because they overlapped with my measures).

### Dashboard Creation

Lastly, I constructed and stylized a dashboard using the existing data as well as my measures (NOT any of the pre-existing measures). The dashboard includes a title pane, 5 card panes, a map pane, a stacked horizontal bar chart, and a table; each of these panes displays different aspects of the data.