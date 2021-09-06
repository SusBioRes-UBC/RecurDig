# RecurDig
Script for digging out LCI of interest via recursion

### To-do for latest version (ver 3.4)
- Update the lca calculation procedure (i.e., avoid creating lci matrix every time in an for loop)
- Create a function for reading the scenario information from excel spreadsheet and format it into form that is ready for 'scenario_parser' function (see [here](https://github.com/SusBioRes-UBC/RecurDig/blob/master/ActivityModifier/ActivityModifier3.4.ipynb))
<br/>

### Possible uses of this script
- Summarize the inventory of interest (e.g., recycled scrap metals) at each recursion level—>where high ‘circularity’ happens (foreground (more control) or background (less control))?
- Aggregated recycled flows: what are different recycled flows associated with the FU? which one has the highest environmental benefits?
- "What-if" scenarios:
  - impact propagation: e.g., change of foreground input-->unintended changes in the background layer
  - feasibility analysis: e.g., a large change of foreground input (e.g., a substantial increase in alternative feedstock use)-->what is the corresponding increase in the demand of materials of interest from various background processes? Will the new demand exceed the existing supply capacity?
