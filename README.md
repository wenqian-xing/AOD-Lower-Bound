# AOD-Numerical-Lower-Bound
The numerical lower bound of the Ambulance Offload Delay problem.

In the provided code, we implement the lower bound using the information relaxation technique (Brown and Haugh, 2017). We provide two examples: the first, a toy example, involves no penalties, zero travel time, and a single priority level; the second, a more comprehensive example, incorporates dual penalties, travel time, and multiple priority levels.

<p align="center">
  <img src="https://raw.githubusercontent.com/wenqian-xing/AOD-Lower-Bound/main/toy_example.png" alt="Simplified Small-Sized Example" style="width: 45%; margin-right: 10px;"/>
  <img src="https://raw.githubusercontent.com/wenqian-xing/AOD-Lower-Bound/main/real_case.png" alt="St. Paul, MN Case Study" style="width: 45%;"/>
  <br>
  <em>(a) The simplified small-sized example &nbsp;&nbsp;&nbsp;&nbsp; (b) The St. Paul, MN case study</em>
</p>
<p>We present the results of 50 sample paths for (a) the simplified small-sized example and (b) the St. Paul, MN case study. For each path, we solve the inner optimization problem (7) using both enumeration and our MIP formulation with the Gurobi solver. Optimal solution values obtained through enumeration are depicted as red plus signs, while those from the MIP approach are shown as blue squares, with any discrepancies highlighted by red circles. We discovered that our MIP consistently produces the optimal solution across all sample paths.</p>
