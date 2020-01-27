# LE-tool-streamlit
Latest Estimate front end tool for PEs; built with streamlit

**Introduction**

The LE and Forecast Utility tool is being built to improve the speed and consistency of production reporting for operations. Currently, engineers are required to gather data from several sources and are utilizing multiple excel spreadsheets that contain calculations and estimations in order to report well performance metrics. This utility is designed to:
•	import and manage production forecasts from a variety of sources (such as Aries and custom spreadsheets), 
•	automate applications of midstream downtime/frac hit mitigation to production values, 
•	aggregate field production for low volume producers,
•	manage netting values (interest and shrinkage) and production actuals when BPX system data sources may be down or temporarily incorrect,
•	automatically generate report metrics and dictate workflow for consistency.


**Process**

The tool is designed to be a hub connector to a variety of data sources, most of which are or will be in the cloud environments of EDH and EDW. Many of these data connections require transformations, interpolations, or conversions to output a standard that ensures consistency in the calculation and reporting. 
The front end will allow users to navigate (both numerically and graphically) to existing LE (Latest Estimate) production forecasts and existing forecasts for wells, create new LE forecasts, and calculate performance metrics that are reported to management. The process of creating new LE forecasts will be dictated by the view/control layers with proper input validations, screen navigation, and automatic messages back to the user.
