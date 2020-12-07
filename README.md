# Community-Detection-Problem-Based-on-Polarization-Measures.-An-application-to-Twitter-the-COVID-19-
Here we provide the data and the results obtained throught the study of a network related to Twitter by the application of a community detection algorithm based on polarization fuzzy measures
This is a repository that hosts the experiment design and the results related to the paper "Community Detection Problem Based on Polarization Measures. An application to Twitter: the COVID-19 case in Spain".

Here we provide the description of each file.

file_1. It includes the assignation of a numerical ID to each of the 454 users originally considered. In this file we also point out which nodes are part of the weak component (those with value "YES" in the variable "Weak_Component").
file_2. It includes a complete list of interactions considering numerical IDs. The column "Original" refers to the user who posts the tweet. The column "RT"refers to the user who RT it.
file_3. It includes the membership degree of each node of the weak component to the poles \eta_{T_A} and \eta_{T_B}. Probabilities of being a "detractor" or a "supporter" of the Spanish government, represented by respective membership degrees \eta_{T_A} and \eta_{T_B}.


RESULTS. In this file we show the obtained results when applying the Louvain algorithm and the Polarization Louvain algorithm for several values of the balancing factor \alpha, considering the scenarios in which \varphi=\max and \phi=\min as well as \varphi=\max and \phi=\min.
		Communities have a numerical ID assigned; each scenario is represented in a column, so the number represents the community to which the corresponding node is assigned.
		Here we show the label assigned to each scenario.
		Case_0 : Louvain algorithm.
		
		Case_1_min: \gamma=0.1; \varphi=\max; \phi=\min.
		Case_2_min: \gamma=0.2; \varphi=\max; \phi=\min.
		Case_3_min: \gamma=0.3; \varphi=\max; \phi=\min.
		Case_4_min: \gamma=0.4; \varphi=\max; \phi=\min.
		Case_5_min: \gamma=0.5; \varphi=\max; \phi=\min.
		
		Case_1_prod: \gamma=0.1; \varphi=\max; \phi=\product.
		Case_2_prod: \gamma=0.2; \varphi=\max; \phi=\product.
		Case_3_prod: \gamma=0.3; \varphi=\max; \phi=\product.
		Case_4_prod: \gamma=0.4; \varphi=\max; \phi=\product.
		Case_5_prod: \gamma=0.5; \varphi=\max; \phi=\product.
		

The PDF called "Images" includes the graphical representation of the communities obtained in each case.	
