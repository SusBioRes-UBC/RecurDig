# RecurDig
Algorithm for digging out LCI of interest via recursion

### Development plan for latest version (ver 3)
- Enable the following:
  - list of keywords
  - aggregate values for the same keyword at each recursion lvl
- Expand the function to do LCA and calculate ratios
  - see: https://chris.mutel.org/calculating-inventory-flows.html
- Validate with high recycle content example (e.g., recycled metals)
- Topic development: e.g., find bioeconomy related processes & flows, covering multiple product categories<br/>

### Use of this algorithm
- Summarize the inventory of interest (e.g., recycled flows) at each recursion level—>where high ‘circularity’ happens (e.g., the further away from your foreground, the harder you can influence)
- Accordingly, the environmental impacts—>will there be ‘decoupling’ between high ‘circularity’ and high ‘GHG reduction’? (e.g., smaller use of recycled materials may lead to larger GHG reductions, which helps to identify the...?
- Aggregated recycled flows: what are different recycled flows associated with the FU? which one has the highest environmental benefits?
- Benchmarking:
  - metrics: GHG, water, energy, circularity, precious metal
  - product categories (representative of respective industries): 
- "What-if" scenarios:
  - impact propagation: e.g., change of foreground input-->unintended changes in the background layer
  - feasibility analysis: e.g., a large change of foreground input (e.g., use alternative feedstock)-->will the supply from background exceed the capacity (if assume BAU for the relevant market)?
