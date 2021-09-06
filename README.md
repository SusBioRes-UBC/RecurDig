# RecurDig
Algorithm for digging out LCI of interest via recursion

### Development plan for latest version (ver 3)
- Enable the following:
  - list of keywords
  - aggregate values for the same keyword at each recursion lvl
- Validate with high recycle content example (e.g., recycled metals)
- Update the lca calculation procedure (i.e., avoid creating lci matrix every time in an for loop)
- Create a function for reading the scenario information from excel spreadsheet and format it into form that is ready for 'scenario_parser' function
<br/>

### Use of this algorithm
- Summarize the inventory of interest (e.g., recycled flows) at each recursion level—>where high ‘circularity’ happens (e.g., the further away from your foreground, the harder you can influence)
- Accordingly, the environmental impacts—>will there be a ‘decoupling’ between high ‘circularity’ and high ‘GHG reduction’? (e.g., smaller use of recycled materials may lead to larger GHG reductions, which helps to identify the...?
- Aggregated recycled flows: what are different recycled flows associated with the FU? which one has the highest environmental benefits?
- Benchmarking:
  - metrics: GHG, water, energy, circularity, precious metal
  - product categories (representative of respective industries): 
- "What-if" scenarios:
  - impact propagation: e.g., change of foreground input-->unintended changes in the background layer
  - feasibility analysis: e.g., a large change of foreground input (e.g., use alternative feedstock)-->will the supply from background exceed the capacity (if assume BAU for the relevant market)?
