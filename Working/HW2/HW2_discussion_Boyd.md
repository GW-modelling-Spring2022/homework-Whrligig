## HW #2 Discussion & Glossary

#### Connal Boyd

1. Create a conceptual model of the homogenous MODFLOW model: This should be an illustration that shows the locations and values of constant head boundaries, the number of grid cells and their spacing as well as any other model properties. You should also include in here a cross section with your predicted head gradient and direction of flow.  You can draw this by hand if you would like. 



2. Show, based on the flux with horizontal distance from a constant head boundary, that the model is steady state.  Repeat this for a homogenous and a heterogenous cases where you place different K values in series in the direction of flow (Note: to modify the K values you should change the `.bcf` file, just be careful because spacing matters!  Note 2: see the excel sheet for an example calculating flux. Keep in mind that that heads are calculated at the center of a cell and the K values are defined across the entirety of a cell)

3. Show the steady state head contour in plan view for the homogenenous and heterogeneous (zones in series) condition.  Use this plot to defend a contention that flow is 1D.  Then, drawing on your first assignment, use the results to explain WHY the equivalent hydraulic conductivity, Keq, is closer to the lower of the two K values.

4. Build a model based on a homogeneous domain with a square region of lower K in the middle of the domain.  What can you learn based on your explanation of what controls the effective K for a 1D flow system now that you are applying it to a 2D system?  What do you think the Keq of this entire system would be compared to the high and low K values?  Explain why it is much more difficult to develop a direct solution for this 2D system than it was for a 1D system (including the zones placed in series). 
   
5. For steady state conditions, there are equivalent Type I and Type II boundary conditions.  What would the Type II boundary condition be that would result in the same equipotentials for the first model?  What is the value of the constant flux?  What about the second model?  What are the values of the constant flux on the left and right boundaries?  What is fundamentally different about the equivalent Type II boundary for the third model compared to the first two? 

## Glossary Questions:
1. What is MODFLOW?  What is a MODFLOW package (provide at least 2 examples)?  What are the inputs to a MODFLOW model?

Packages allow you to simulate additional properties within the model.

2. What is the relationship between head gradients and hydraulic conductivity in steady state systems? 

Inverse relationship between hydraulic conductivity and head gradient. When one increases the other has to decrease.

3. What is a model node?  A model cell?  Use a simple diagram to show the relationship between heads defined at nodes and properties defined in cells.
   
4. What is the difference between TypeI and Type II boundary conditions and under what conditions might you use each? Provide at least 2 examples for locations where we might use Type I or Type II boundaries to represent a feature in the real world. 