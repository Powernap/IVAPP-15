Rebuttal
========

This rebuttal is written in markdown.

General Changes
---------------

- substantial reductions had to take place, since we were given a `short paper` slot with an 8-page limit.
	- redundancy between `Introduction` and `Epidemiological Background` was minimized as much as possible
	- `Related Work` section was shortened and covers less papers to meet the page limit.
		- as requested by [Reviewer 3], we elaborate on the differences towards the VMV paper in the `Related Work` section
	- `The Lumbar Spine Data Set` section was shortened, `Figure 2` was removed since we found it did not support the train of thought as we intended
	- `Experiments and Preliminary Results` section was shortened and changed due to the Reviewer feedback. It should be more precise and comprehensible.
	- `Results` section now covers *all subjects*, subjects categorized by *gender* and *body mass index*
		- `Figure 3` (former `Figure 4`) was adapted accordingly
	- `Summary & Conclusion` was completely revised and is now structured properly
		- Due to the lack of time until the camera ready deadline as well as the page limit, we are not able to conduct a detailed user test. We did, however, discuss our approach in more detail in the last section

Reviewer 1
----------

- Figure 1 was completely removed since it does not supports the train of thought as we intended and due to lack of space
- Applicability: Comparison to standard workflow is not possible. The classic epidemiological workflow is strictly hypothesis driven and therefore requires a small set of 2 - 3 variables, which are correlated with a target variable. IVA methods amplify *hypothesis generation* and therefore aim to provide insight into unexpected relationships in the data.
- Exploration process is unclear
	- Role of Decision Trees and why they are chosen is now captured in the introduction of section 6 - Interactive Decision Tree Visualization.
	- at the beginning of Section 5 - Experiments and Preliminary Results, all subjects
	- Experiments and Preliminary Results completely restructured to make it comprehensible
- Response to Minor Comments:
	- *GPLOM Analysis Section. “The combination of the image variables with back pain is visualized as histogram at the left side…” left should be bottom*: Back pain is encoded with presence (red) and absence (turquoise) in all plots left of the matrix diagonal. We clarified this in the text.