# Self-guided_PowerBI
 
4 kinds of Data Analysis:

	- Descriptive: what happened
	- Diagnostic: why did it happen
	- Predictive: what will happen
	- Prescriptive analysis: what must be done

	PowerBI targets Diagnostic and Prescriptive analysis primarily

	After you feed some data, your choose of data viz is similar to Tableau. It automatically formats the data to the best of its ability
	- Drill up and down to change data clustered in different hierarchys (modificar a granularidade)
	- Always check the encoding and the regional settings, as they may interfere in accents or comma/dot standards

	PowerBI Desktop workflow
	1) Define the problem
	2) Data preparation (Query editor)
	3) Data modelling (Relationship View / Data View)
	4) Data viz (Report View)

---

1st Case Study: Car sales

Creating a dashboard.
- Dashboards connect all kinds of different metrics, data sources, APIs, and services to help companies extract relevant information from those sources and display it in user-friendly ways. Like a car’s dashboard, data dashboards organize and display important information at a glance to help you understand your company’s most valuable data and unearth answers to crucial questions.

- After loading the car sales data, notice that the 'year' column is marked as numeric. This will hinder our ability to correctly display, for example, sales per year, since we don't currently have "labels", but numeric values which PowerBI will automatically sum (in Fields).
- So change it duh!
- With a clustered column chart, now we need some additional formatting: font size, style etc
- Bear in mind that the x-axis is ordered by total sales, but we want it by year: 3 dots --> sort by --> etc. Also reverse the order.