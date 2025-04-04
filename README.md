# Deneb / Vega-Lite Repository

A repository containing code to create advanced data visualisations using Vega-Lite / Deneb. 

A number of these data visualisations have then been used in Power BI reports. 

## Column Chart with Supplier Axis
Column chart with rounded edges showing the number of patients per supplier, split by gender:

<img width="210" alt="msedge_eWCOh6UTcN" src="https://github.com/user-attachments/assets/162611b9-af2c-4c83-a860-93e889ce06a1">

## Dial
A unit dial chart showing actual vs target progress against a (user-selectable) KPI.

<img width="141" alt="yTR1Unp12j" src="https://github.com/user-attachments/assets/b4feebcc-14a5-450a-9b71-9343f093c4ba" />

## Donut chart with central total
Donut chart showing breakdown of a metric across different categories together with the total displayed in the centre.

The native Power BI donut doesn't provide a total and the workarounds such as overlaying a card do not provide a great user experience.

<img width="169" alt="xqzkod9YIR" src="https://github.com/user-attachments/assets/94a83cef-1f1f-4f78-8469-73d8cff05fb7" />

## Dot Plot Over Time
Dot plot showing market share (MS%) of a product across different geographies over time (each dot represents a different branch)

<img width="500" alt="Image" src="https://github.com/user-attachments/assets/95b4c952-07a7-4587-b66a-e1fadb852135">

## Dumbbell Chart
Dumbbell chart comparing the activity (calls, appointments etc) that reps have made in regards to Product 1 vs other products (all time). 

<img width="731" alt="Image" src="https://github.com/user-attachments/assets/0ade1e3f-a6ca-49f2-9d23-b20fb717e40f">

## Dumbbell Chart Years & Countries
Dumbbell chart showing country performance (Denmark, Norway & Sweden) between two distinct calendar years:

<img width="278" alt="Image" src="https://github.com/user-attachments/assets/df625dcc-15f8-4d88-b052-90e41282d3fb" />

## Lollipop Chart
Lollipop chart showing country performance (Denmark, Norway & Sweden) between two distinct calendar years:

<img width="148" alt="Image" src="https://github.com/user-attachments/assets/9b1dd4ba-5817-4bdf-834f-42d0b1c1921f">

## Matrix with Sort
A responsive matrix visualisation showing counts per year for each person sorted in descending order on the most recent year. The native Power BI visual does not allow you to sort by any column. 

This Deneb example could easily be adapted to sort on any of the columns or have no sort at all.  

<img width="696" alt="n28kTsT0Qq" src="https://github.com/user-attachments/assets/3c1f9c8c-c0ec-40c0-95c8-f06bc0c3cefc" />

## Radar / Spider Chart 
A radar chart showing performance across a range of metrics for a given individual.

<img width="322" alt="yRLzVdzf9D" src="https://github.com/user-attachments/assets/4e8c8e3e-8e9d-48b4-aef2-531ec22979ff" />

## Rainfall Scatter Plot
This was a challenge set from the Workout Wednesday website (https://workout-wednesday.com/2023-week-22-power-bi-inverted-jittered-scatter/).

This involves two charts vertically stacked on top of one another. The first represents the sum of rainfall per month as a jitter scatter plot and the second as a bubble chart showing the average rainfall per month.

(The heading was not part of the deneb specification and was done separely using native Power BI) 

<img width="538" alt="Lb1c1gBOhY" src="https://github.com/user-attachments/assets/04b83827-7ec1-4a49-aec5-3a35303b5b6d" />

## Red / Green Combo Chart with Dynamic Date Axis
This was on a drill through page which you navigated to from another where the individual or team and the frequency for which the KPI was measured had been selected. Some teams / individuals were measured over weeks, some over months. 

The requirement was that the x axis should change dynamically based on the frequency chosen on the previous page (either showing weeks or months). There was to be nothing except the visual on the drill through page.  

This was not possible in native Power BI <em>without a slicer</em> and Fields parameters. The user also wanted the actuals to be colour-coded - green if target met, red otherwise. 

<img width="461" alt="zBWaKam3um" src="https://github.com/user-attachments/assets/0756263c-143f-4a77-8b50-5065d1919824" />
<img width="453" alt="x9oYw9IcLD" src="https://github.com/user-attachments/assets/2674b490-b3bb-468e-9e25-a5682b5b2cdf" />

## Rounded Bar Chart
Bar chart with rounded edges showing the number of branches with a given status. The colour of the bars can also be used to indicate.

<img width="206" alt="Image" src="https://github.com/user-attachments/assets/6eaad522-c919-416b-9739-2a21272ff31c" />

## Rounded Column Chart
Two column charts in one showing each month for how many PCOs a given product is on formulary

<img width="428" alt="Image" src="https://github.com/user-attachments/assets/3502d3e2-8e6e-491f-9b82-90d2be410ee8" />

## Scatter Plot Showing Change Over Time
Scatter plot showing performance per rep with a dot per month per rep (thereby showing rep's historical performance each month)

<img width="810" alt="ScatterPlotWithHistory" src="https://github.com/user-attachments/assets/f3358cae-640d-4c69-853e-f74dade72f34" />

## Single Row Table with Transparency
A single row table with transparent background. This was used on top of another visual to hold the target % for the current period and when selected would activate a drill through button to see target % for all past periods. 

A card did not meet the requirements since the evaluation context could not be gleaned from the card. 

<img width="52" alt="29LdfWT9Ss" src="https://github.com/user-attachments/assets/e4238be0-5f72-4980-b55b-d7a96a67e813" />

## Slope Graph
Slope graph showing change between two distinct years for three different countries:

<img width="270" alt="HTEtfJ1I3j" src="https://github.com/user-attachments/assets/7f6f4155-18b6-4cbf-b5b0-95fd86b41787" />

## Small Monthly Actual vs Target
This is a small graph used in side panel to indicate AvT % for each of the last (up to) 12 mths

<img width="136" alt="f69q8h30wU" src="https://github.com/user-attachments/assets/409cc269-bc50-47bf-92fb-9778c5ae8f33" />

