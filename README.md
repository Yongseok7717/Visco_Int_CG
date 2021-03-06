Hello, I am a FEniCS user interested in *coninuous/discontinuous Galerkin finite element methods*.  
Especially, during my PhD research, I have contributed to code implementations for solving **viscoelastic problems**.  
My works forcused on numerical solutions to **dynamic viscoelastic problems**. 
Code implementations deal with simple wave equations, elastic problems, vicoelastic problems modelled by *generalised Maxwell solid* or *fractional order model*.  
Numerical schemes are based on *spatial finite element methods*(CG/DG) and *Crank-Nicolson method* for time discretisation.

For more details, please see **ModelProblem.pdf**.


All codes are constructed in Python 2.7.12 and FEniCS(dolfin) 2016.2.0.
- CG_P1.py: Use the displacement form
- CG_P2.py:	Use the velocity form
- ModelProblem.html:	Describe the model problem of linear viscoelasticity
- ModelProblem.pdf:	Describe the model problem of linear viscoelasticity
- README.md	
- Table1.py:	Generate tables of numerical errors for the displacement form
- Table2.py:	Generate tables of numerical errors for the velocity form
- graph.py: Draw graphs
- graphic_linear.py: Draw graphs for linear polynomial basis
- graphic_quad.py: Draw graphs for quadratic polynomial basis
- main_Figure1.sh: Main task for figures
- main_Table.sh: Main task. You should run this first to run 'main_Figure1.sh'


If you have any inquires, please contact me at email yongseok.jang@brunel.ac.uk or yongseok20007717@gmail.com.
If you are interested in my research, please visit https://yongseokmath.wordpress.com/.
