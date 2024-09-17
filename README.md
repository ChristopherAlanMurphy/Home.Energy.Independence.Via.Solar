# Project Overview:
The analysis examines energy consuption and energy generation in a home with a newly installed solar electrical system.  All home appliances and lawn equipment are electric.  In addition, an Electric Vehicle (EV) is charged multiple times in a given week. The analysis compares costs of energy consuption, cost avoidance from energy generated from solar power, and ultimately evaluates the return on investment (ROI) of the solar system implementatation.

# Team Members:
John Woodcock Jr. (the owner)
Christopher Murphy
Joshua Wiser

# Reason for Selecting this Topic:
As of September 17, 2024, energy costs in Hawaii are higher than anywhere else in the United States. As of August 2024, families are paying 44.28 cents per kilowatt hour (kWh), almost three times the national average of 15.45 cents . The average gas price in Hawaii is $4.667 per gallon for regular unleaded fuel. This is again the highest in the nation and 35.5% higher than the national average . Sustainable living is not just an environmental imperative, it is essential to be able to maintain a comfortable lifestyle.

# Background Information
The scope of the analysis has 5 main components.
1. Photovoltaic (PV) Panels.
   - The PV panels generate electricity from the sun. This system is located on the western part of the island of Oahu. This area has very little cloud cover and only gets about 28 days of rain per year.
3. Batteries
   - Modern solar power systems may include one or more batteries to store and distribute electrical power when the sun is not shining or to serve as a backup in the event of a power outage that makes the power grid unavailable. 
5. The electrical grid
   - The local utility company, Hawaiian Electric (HECO), provides electrical power when needed. HECO also buys back excess electricity produced by solar electric systems at a reduced rate.
7. The home
   - The home is the consumer of electricity. As part of this case study, all appliances and lawn equipment are electric with most drawing from the power provided by the solar electric system.
9. Electric Vehicle (EV) charger
   - The EV charger provides power for one vehicle, offsetting the cost of fuel. However, the EV charger is the single greatest draw on the power system, quickly draining the batteries and forcing increased reliance on the electrical grid.
     
# Questions We Hope to Answer with the Data:
1. What is the energy capacity of the solar electrical system? (unit of analysis = kW or kWh)
2. Is it possible to optimize car charging to reduce reliance on the grid and retain enough charge in the batteries to power the home through the night? (unit of analysis = hours)
3. Can the system be removed from the grid and be completely self-reliant? (unit of analysis = kWh)
4. At what point will the system deliver a return on investment? (unit of analysis = U.S. dollars)

# Description of Data Sources:
The analysis used three different sets of data: electrical system data covering 32 days of power generation and consumption measured at 5-minute intervals, approximately 60 days of EV charging data, and Hawaiian Electric Company (HECO) rates for both energy consumption and solar export. The data represented the home’s energy usage, solar production, the impact of EV charging, and potential savings from selling solar energy back to the grid. Together, this information helped estimate the system’s ROI and the feasibility of energy independence.

# Technologies Used:
Google Colab Notebook, Google Drive, Python and Libraries: pandas, numpy, matplotlib, seaborn, statistics, datetime
