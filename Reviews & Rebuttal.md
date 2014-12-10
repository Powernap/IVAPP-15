Reviewer Feedback (formatted into Markdown for better readability)

# Reviews
Paper Title: Interactive Visual Analysis of Lumbar Back Pain – What the Lumbar Spine Tells About Your Life
Paper #: 3
Paper Selection State: Short Paper (20 minutes oral presentation)		
Number of Reviews: 3
Rating Scale: 1: Lowest Value, 6: Highest Value

## Reviewer 1

### Rating

- Abstract and Introduction are adequate?: Yes
- Conclusions/Future Work are convincing?: No
- Figures are adequate ? in number and quality: No
- Improve critical discussion ? validation: Yes
- Improve English?: No
- Needs comparative evaluation?: No
- Needs more experimental results?: No
- Originality Newness of the ideas expressed: 2
- Overall Rating Weighted value of above items: 3
- Paper formatting needs adjustment?: No
- Presentation Structure/Length/English: 4
- References are up-to-date and appropriate?: Yes
- Relevance Paper fits one or more of the topic areas? 2
- Significance Is the problem worth the given attention? 3
- Technical Quality/Theoretical soundness/methodology: 3

### Observations for Author
The paper describes an interactive visual analysis aimed at finding relationships between lumbar spine geometrical properties and lower back pain. Lumbar spine geometry is captured by extracting 9 image related metrics from more than 2,000 magnetic resonances. Such numerical information is explored looking for a possible correlation with the binary lower back pain variable, using a scatterplot matrix (on the 9 metrics) and plotting 2 histograms and two box-plots of the binary lower back pain for each numerical variable. Because no statistically significant correlation could be observed the paper proceeds using the principal component analysis and an heterogeneous correlation of more than 100 patient-specific attributes (e.g., age, gender, etc.), finding weak correlations. The third analysis phase uses decision trees, generating a tree for every patient specific attribute in order to locate the attributes that can be explained by image derived variables, producing up to 402 trees that are filtered according to their size and quality and plotted as points on scatterplots, arranged on four classification of the data. Some results are, eventually, discussed (eg., gender can be discriminated with an error of 0.31 using 7 rules and using only two image based variables). I’m not satisfied with the paper for three mains reasons:

- 1) The exploration strategy is, in my opinion, not clear: there are not clear goals or net steps. The analysis is conducted using a brute force attack (scatterplot matrix, correlation of all 134x134 patient-related attributes, exhaustive decision tree generation). Results are collected without a general strategy: e.g., what is the relevance of high correlation between curvature angle and mean curvature with the main goal of understanding how the 9 numerical variables and the 134 patient-based attributes relates to the lower back pain? What is the role of decision trees explaining how numerical variables explains patient-based attributes in explaining the source of lower back pain? And, again, what is the role of PCA? The general impression I get from the paper contains the application of a set of standard and well known statistical techniques without a clear relationship of the main goal of understanding the lower back pain; 
- 2)Visualizations are inserted in the discussion without making clear how they contribute to the overall process. How images on Figure 3 drive the next step? Moreover, some of them are confusing. What is the purpose of Figure 2 w.r.t. the main process? Moreover, no part of an image is the source for the next step: where is the evidence of :”show the important and analyze further”? Where is the interactive part of the images? Just browsing on dots on scatterplots and getting the trees? 
- 3) Weak or no clue is provided about how images allowed for getting the final conclusions. How do the authors get the insights from the Figure 4? Focusing on the origin zone, with low error rate and little size tree? 

On the other hand the amount of work described in the paper is relevant, and likely useful for the medical domain. For this reason, I rate the paper as borderline. Minor comments: Figure 2. The caption is confusing: if the top part refers to male and the bottom part refers to female, what is the meaning of: “The dark gray share of each bar encodes the portion of male (top chart) or female (bottom chart) subjects”? GPLOM Analysis Section. “The combination of the image variables with back pain is visualized as histogram at the left side…” left should be bottom Correlatiob Matrix “an correlation” Text on figure 3 is hard to read.

The prototype is not available at blind.dnsalias.com


## Reviewer 2	

### Rating

- Abstract and Introduction are adequate?: Yes
- Conclusions/Future Work are convincing?: Yes
- Figures are adequate ? in number and quality: Yes
- Improve critical discussion ? validation: Yes
- Improve English?: No
- Needs comparative evaluation?: Yes
- Needs more experimental results?: Yes
- Originality Newness of the ideas expressed: 3
- Overall Rating Weighted value of above items: 4
- Paper formatting needs adjustment?: No
- Presentation Structure/Length/English: 4
- References are up-to-date and appropriate?: Yes
- Relevance Paper fits one or more of the topic areas?: 4
- Significance Is the problem worth the given attention? 3
- Technical Quality Theoretical soundness/methodology: 3

### Observations for Author
The paper proposes a new way to visually explore decision tree results. It is used to analyze lumbar spine data and understand relationship between 9 image features and 134 non-image features. The strengths of the paper:
- the paper is well-written and gives detailed introduction into the epidemiology domain
- the visual analytics approach is well-motivated and intuitive The weaknesses of the paper:
- the explanation of the domain is probably too lengthy
- the approach was not evaluated with user tests or at least with some inspection methods Suggestions:å
- the paper would be strengthened if we could see some illustration where the proposed approach is uniquely capable of providing some actionable insights as compared to the existing approaches (such as looking at the decision trees or performing feature selection)


## Reviewer 3

### Rating
- Abstract and Introduction are adequate?: Too long
- Conclusions/Future Work are convincing?: No
- Figures are adequate ? in number and quality: Yes
- Improve critical discussion ? validation: No
- Improve English?: No
- Needs comparative evaluation?: No
- Needs more experimental results?: No
- Originality Newness of the ideas expressed: 3
- Overall Rating Weighted value of above items: 3
- Paper formatting needs adjustment?: Yes
- Presentation Structure/Length/English: 2
- References are up-to-date and appropriate?: Yes
- Relevance Paper fits one or more of the topic areas?: 6
- Significance Is the problem worth the given attention?: 3
- Technical Quality Theoretical soundness/methodology: 3

### Observations for Author
This paper is an extension of the authors' previous VMV paper. The IVA appears quite the same with the addition of a decision tree that the authors claim is data mining. The paper is very long and does not need to be. The authors should be specific about their contributions (the IVA is not new) and condense the paper to about 8 pages maximum. Be specific about how this is an extension of the VMV paper and what is new and different. Compare and contrast with that paper rather than obfuscate the two. The future work has a paragraph ending in '(' I guess completing the section is future work? I would argue for a weak accept of this paper though it needs a rewrite to be publishable.

Rebuttal & Coverletter
======================

This rebuttal/coverletter is written in markdown. A graphical summary of the reviews can be found [here](https://docs.google.com/spreadsheets/d/1DTPt5eGe6PpMiNh38p4YsQrKLI3bqKhylZQKZKiZg4w/edit?usp=sharing).

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
	- due to the lack of time until the camera ready deadline as well as the page limit, we are not able to conduct a detailed user test. We did, however, discuss our approach and its drawbacks in more detail in the last section
- Figure 1 was completely removed since it does not supports the train of thought as we intended and due to lack of space

Reviewer 1
----------

- *"The exploration strategy is, in my opinion, not clear: there are not clear goals or net steps."*
	- role of Decision Trees and why they are chosen is now captured in the introduction of Section 6 - Interactive Decision Tree Visualization.
	- experiments and Preliminary Results completely restructured to make it comprehensible
- *"What is the role of decision trees explaining how numerical variables explains patient-based attributes in explaining the source of lower back pain?"*
	- the first step is always finding associations with back pain. As we conclude, that no such associations could be extracted at the given model precision, the focus shifts towards assessing, which variables can be described through the shape variables.
- *"Where is the interactive part of the images? Just browsing on dots on scatterplots and getting the trees?"*
	- Browsing the decision tree results is one interactive part. More important, however, is the ability to select target variables, which are used to subdivide the subjects, to assess their influence towards the result. Also, depending on how many subjects are included in a certain sub group (e.g. people suffering from a rare condition), the minimum subject count for a classification and the maximum error can be adjusted.
- *"Weak or no clue is provided about how images allowed for getting the final conclusions. How do the authors get the insights from the Figure 4? Focusing on the origin zone, with low error rate and little size tree?"*
	- We clarified this in the Figure caption.
- response to Minor Comments:
	- *"GPLOM Analysis Section. “The combination of the image variables with back pain is visualized as histogram at the left side…” left should be bottom"*: Back pain is encoded with presence (red) and absence (turquoise) in all plots left of the matrix diagonal. We clarified this in the text.
- *"The prototype is not available at blind.dnsalias.com"*
	- Regarding to our server logs we had a 100% uptime through the time of the reviewing process, we cannot comprehend whats gone wrong there

Reviewer 2
----------

- *"the explanation of the domain is probably too lengthy"*
	- we removed redundancies and shortened the `Epidemiological Background` section
- *"the approach was not evaluated with user tests or at least with some inspection methods"*
	- due to the lack of time until the camera ready deadline as well as the page limit, we are not able to conduct a detailed user test. We did, however, discuss our approach and its drawbacks in more detail in the last section
- *"the paper would be strengthened if we could see some illustration where the proposed approach is uniquely capable of providing some actionable insights as compared to the existing approaches"*
	- the standard workflow of the epidemiologists is deriving hypotheses from the clinical day to day practice. The data are analyzed towards 2-3 independent variables at maximum towards a dependent variable, such as back pain. To our knowledge, there are no existing approaches used by epidemiologists in the day to day practice allowing for an explorative analysis using decision trees, so it is difficult to conduct a comparison as suggested. IVA methods amplify *hypotheses generation* and therefore aim to provide insight into unexpected relationships in the data.

Reviewer 3
----------

- *"The authors should be specific about their contributions (the IVA is not new) and condense the paper to about 8 pages maximum."*
	- we elaborate on the differences towards the VMV paper in more detailed in the `Related Work` section.
	- the paper was shortened as requested