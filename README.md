# Violin-Plot-in-Python
1) This plot shows the probability of data at different values.<br>
this is better than boxplot to view the distribution of numeric data.



!!!Code:<br>
import matplotlib.pyplot as plt<br>
import numpy as np<br>
c1=np.random.normal(100,90,200)<br>
c2=np.random.normal(50,300,200)<br>
c3=np.random.normal(90,80,200)<br>
c4=np.random.normal(70,95,200)<br>
plot_data=[c1,c2,c3,c4]<br>
fig=plt.figure()<br>
ax=fig.add_axes([0,0,1,1])<br>
vp=ax.violinplot(plot_data)<br>
print(plt.show())<br>

