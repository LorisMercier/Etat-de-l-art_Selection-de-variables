# Ouverture à la recherche : Sélection de variables

## **SUJET** : FSPML -> Sélection de variables pour l'approche **Partial Multi-Label**
>La sélection de variables est une tâche primordiale dans les 
processus d’apprentissage automatique et de data mining. Elle 
consiste à « nettoyer » l’espace de description des données en 
vue d’améliorer la performance des algorithmes 
d’apprentissage.  
Cette tâche est relativement, très répandue en mode supervisé, 
encore moins en mode non-supervisé et demeure défiante en 
mode semi-supervisé. Le challenge est de satisfaire le 
compromis entre la structure géométrique de la partie non-étiquetée des données et le peu de supervision opéré dans leur 
partie étiquetée. D’autre part, traiter cette tâche dans un cadre 
multi-labels (plusieurs cibles à la fois) avec un étiquetage 
incertain suscite une investigation plus approfondie sur le 
domaine.  
Le travail consistera à dresser un état de l’art de premier plan 
sur la problématique abordée, et faire une étude comparative 
significative (en Python) des approches investiguées avec des 
tests statistiques à l’appui.


## Rapport d'avancement
Problématique d'étude très récente, la sélection de variables appliquées au multi-label partiel n'en est pour l'heure qu'au stade embryonnaire des recherches. 

Afin d'aborder en profondeur les différentes notions rattachées à ce sujet FSPML, nous avons fait le choix en concertation avec nos encadrants de projet de traduire ce sujet en trois états de l'art :
1. **[Sélection de variables supervisée mono-label](A_Etat_de_l'art_FS_SuperviseeMonoLabel_LEFEBVRE_MERCIER)**
2. **[Sélection de variables semi-supervisée mono-label](B_Etat_de_l'art_FS_SemiSuperviseeMonoLabel_LEFEBVRE_MERCIER)**
3. **[Sélection de variables appliquée à l'univers multi-label et multi-label partiel (PML)](C_Etat_de_l'art_FS_MultiLabel_LEFEBVRE_MERCIER)**


Ces 3 parties ont l'avantage d'être progressive.   
**Tout d'abord**, notre premier état de l'art présente les différentes catégories de sélection de variables en se basant sur le mode d'apprentissage le plus répandu : Supervisé, mono-label. Nous introduisons ainsi les trois grandes approches de sélection de variables que sont les filtres, les wrappers et les méthodes embedded.   
**Nous** appliquons ensuite un focus sur l'approche semi-supervisée dépendant à la fois de l'approche supervisée et non-supervisée.    
**Enfin**, nous appliquons les connaissances précédemment étudiées à l'univers multi-label. Ici chaque instance initiale est rattachée à plusieurs labels en sortie. Cette partie est l'occasion pour nous d'étudier en détail la sélection de variables en mode multi-label partiel, point d'orgue des 6 mois de travail.


## Les productions
Les 3 états de l'art sont à retrouver dans les fichiers PDF de ce dépôt.  

La vidéo de vulgarisation est disponible ici : https://youtu.be/NsH3ifd8bCo

Les références des différents articles sont disponibles ci-dessous. (Pour le troisième état de l'art, toutes les références sont à retrouver directement dans le document)

### Etat de l'art 1 : Sélection de variables pour l'approche supervisée
[1] Battiti, R. (1994).  Using Mutual Information for Selecting Features in Supervised Neural Net Learning.  
*IEEE Trans*. Neural Netw. 5, 537–550.    

[2] Ben Brahim, A., Jerbi, W., and Nadia, E. (2017). A Hybrid Embedded-Filter Method for Improving Feature 
Selection Stability of Random Forests, *Advances in Intelligent Systems and Computing* 552:370-379.  

[3] Bolón-Canedo, V., Sánchez-Maroño, N., and Alonso-Betanzos, A. (2013). A Review of Feature Selection 
Methods on Synthetic Data. *Knowl. Inf. Syst. 34*, 483–519  

[4] Breiman, L., Friedman, J. H., Olshen, R. A., and Stone, C. J. (1984). Classification and Regression Trees. 
*Chapman and Hall/CRC*.  

[5] Breiman, L. (2001). Random Forests. *Mach. Learn*. 45, 5–32. 

[6] Caruana, R., and Niculescu-Mizil, A. (2006). An empirical comparison of supervised learning algorithms, 
in *23rd International Conference on Machine Learning*, (Pittsburgh, PA: ACM Press), 161–168.  

[7] Fisher,R (1935). Statistical Methods for Research Workers, *Oliver and Boyd*, p200.   

[8] González, J., Ortega, J., Damas, M., Martín-Smith, P., & Gan, J. Q.  (2019). A new multi-objective wrapper 
method for feature  selection–Accuracy and stability analysis for BCI. *Neurocomputing*, 333, 407-418.   

[9]  Goudey,  B.,  Rawlinson,  D.,  Wang,  Q.  et  al.  (2013).  GWIS  -  model-free,  fast and  exhaustive search  for 
epistatic interactions in case-control GWAS. *BMC Genomics 14* (Suppl 3).

[10] Greene, C. S., Penrod, N. M., Kiralis, J., and Moore, J. H. (2009). Spatially Uniform ReliefF (SURF) for 
Computationally-Efficient Filtering of Gene-Gene Interactions. *BioData Min*   

[11] Guyon,I. and Elisseeff,A. (2003). An introduction to variable and feature selection. *J. Mach Learn Res.*, 
3, 1157–1182.  

[12] Guyon, I., Gunn, S., Nikravesh, M., and Zadeh, L. (2006). Feature Extraction: Foundations and 
Applications, *Berlin: Springer*, 207 

[13] John, G. H., Kohavi, R., and Pfleger, K. (1994). Irrelevant Features and the Subset Selection Problem, 
*Machine Learning Proceedings* 1994 (Burlington, MA: Morgan Kaufmann Publishers), 121–129, 121–129.   

[14]  Kassahun  Azezew  Ayidagn,  prof.  Shilpa  Gite  (2017)  Analysis  of  Feature  Selection  Algorithms  and  a 
Comparative study on Heterogeneous Classifier for High Dimensional Data survey, *International Journal of 
Engineering Trends and Technology* (IJETT), V53(2),59-63.  

[15]  Kira,  K.,  and  Rendell,  L.  A.  (1992).  Feature  Selection  Problem:  Traditional  Methods  and  a  New 
Algorithm, *Proceedings Tenth National Conference on Artificial Intelligence 2*, 129–134.   

[16] Kohavi, R., and John, G. H. (1997). Wrappers for Feature Subset Selection. *Artif. Intell. 97*, 273–324. 

[17]  Kononenko,  I.  (1994).  Estimating  Attributes:  Analysis  and  Extensions  of  RELIEF,  Lecture  Notes  in 
*Computer  Science*  (Including  Subseries  Lecture  Notes  in  Artificial  Intelligence  and  Lecture  Notes  in 
Bioinformatics) (Berlin, Heidelberg: Springer), 784, 171–182  

[18] Mao, Y., & Yang, Y. (2019). A wrapper feature subset selection method based on randomized search and 
multilayer structure. *BioMed research international*.   
 
[19] Mnich, K., & Rudnicki, W. R. (2020). All-relevant feature selection using multidimensional filters with 
exhaustive search. *Information Sciences*, 524, 277-297.   

[20]  Nguyen,  B. &  Xue,  B.  &  Liu,  I. &  Zhang,  M..  (2014).  Filter  based backward  elimination  in  wrapper 
based PSO for feature selection in classification. *Proceedings of the 2014 IEEE Congress  on Evolutionary 
Computation*, CEC 2014.   

[21]  Lunetta,  K.  L.,  Hayward,  L.  B.,  Segal,  J.,  and  van  Eerdewegh,  P.  (2004).  Screening  Large-Scale 
Association Study Data: Exploiting Interactions Using Random Forests. *BMC Genet. 5*, 32.   

[22]  Peng,  H.,  Long,  F.,  and  Ding,  C.  (2005).  Feature  Selection  Based  on Mutual  Information:  Criteria  of 
Max-Dependency, Max-Relevance, and Min-Redundancy. *IEEE Trans. Pattern Anal. Mach. Intell. 27*, 1226–1238.  
   
[23] Quinlan, J.R. (1986). Induction of decision trees. *Mach Learn 1*, 81–106.   

[24] Quinlan, J.R. (1992). C4.5 Programs for Machine Learning, *Morgan Kaufmann*, San Mateo.

[25] Reif, M., & Shafait, F. (2014). Efficient feature size reduction via predictive forward selection. *Pattern 
Recognition*, 47(4), 1664-1673. 

[26] Saeys, Y., Inza, I., and Larrañaga, P. (2007). A Review of Feature Selection Techniques in Bioinformatics. 
*Bioinformatics 23*, 2507–2517  

[27] Schlittgen, R. (2011). A Weighted Least-Squares Approach to Clusterwise Regression. *AStA Adv. Stat. 
Anal. 95*, 205–217.   

[28] Schwarz, D. F., König, I. R., and Ziegler, A. (2010). On Safari to Random Jungle: a Fast Implementation 
of Random Forests for High-Dimensional Data. *Bioinformatics 26*, 1752–1758.   

[29]  Stracuzzi,  D.  J.,  &  Utgoff,  P.  E.  (2004).  Randomized  variable  elimination.  *The  Journal  of  Machine 
Learning Research*, 5, 1331-1362. 

[30] Tibshirani, R. (1996), Regression Shrinkage and Selection Via the Lasso. Journal of the Royal Statistical 
*Society: Series B (Methodological)*, 58: 267-288. 

[31] Winham, S. J., Colby, C. L., Freimuth, R. R., Wang, X., de Andrade, M., Huebner, M., et al. (2012). SNP 
Interaction Detection with Random Forests in High-Dimensional Genetic Data. *BMC Bioinforma. 13*, 164. 

[32] Yang, H., and John Moody (1999). Feature selection based on joint mutual information. *Proceedings of 
international ICSC symposium on advances in intelligent data analysis.* Vol. 23. Rochester, NY: Citeseer. 

[33]  Yu,  L.,  and  Liu,  H.  (2004).  Efficient  Feature  Selection  via  Analysis  of  Relevance  and  Redundancy.               
*J. Mach. Learn.* Res. 5, 1205–1224. 

[34] Ziegler, A., DeStefano, A. L., König, I. R., & Group 6. (2007). Data mining, neural nets, trees—problems 
2 and 3 of genetic analysis workshop 15. *Genetic epidemiology*, 31(S1), S51-S60.

### Etat de l'art 2 : Sélection de variables pour l'approche semi-supervisée
[1]  Ang,  J.  C.,  Haron,  H.,  &  Hamed,  H.  N.  A.  (2015,  May).  Semi-supervised  SVM-based  feature 
selection  for  cancer  classification  using  microarray  gene  expression  data.  *In Current  Approaches  in 
Applied  Artificial  Intelligence:  28th  International  Conference  on  Industrial,  Engineering  and  Other 
Applications  of  Applied  Intelligent  Systems,  IEA/AIE  2015*,  Seoul,  South  Korea,  June  10-12,  2015, 
Proceedings (pp. 468-477). Cham: Springer International Publishing. 

[2]  Barkia,  H.,  Elghazel,  H.,  &  Aussem,  A.  (2011,  December).  Semi-supervised  feature  importance 
evaluation with ensemble learning. *2011 IEEE 11th International Conference on Data Mining (pp. 31-
40). IEEE.*

[3] Belkin, M., Niyogi, P., Sindhwani, V. (2006) Manifold regularization: A geometric framework for 
learning from labeled and unlabeled examples. *Journal of Machine Learning Research*, 7:2399–2434. 

[4]  Bellal,  F.,  Elghazel,  H.,  &  Aussem,  A.  (2012).  A  semi-supervised  feature  ranking  method  with 
ensemble learning. *Pattern Recognition Letters*, 33(10), 1426-1433. 

[5] Breiman, L. (2001). Random forests. *Machine learning*, 45, 5-32. 

[6]  Cheng, H., Deng,  W., Fu, C., Wang, Y., & Qin, Z. (2011).  Graph-based semi-supervised  feature 
selection with application to automatic spam image identification, *Computer Science for Environmental 
Engineering and EcoInformatics: International Workshop, CSEEE 2011*, Kunming, China, July 29-31, 
2011, *Proceedings, Part II (pp. 259-264). Springer Berlin Heidelberg.* 

[7] He, X., Cai, D., Niyogi, P. , (2005). Laplacian score for feature selection, *Proceedings of the 18th 
International Conference on Neural Information Processing Systems (NIPS'05)*. *MIT Press*, Cambridge, 
MA, USA, 507–514. 

[8] Han, Y., Park, K., & Lee, Y. K. (2011). Confident wrapper-type semi-supervised feature selection 
using an ensemble classifier. *2011 2nd International Conference on Artificial Intelligence, Management 
Science and Electronic Commerce (AIMSEC) (pp. 4581-4586). IEEE*. 

[9] Kalakech, M., Biela, P., Macaire, L., & Hamad, D. (2011). Constraint scores for semi-supervised 
feature selection:A comparative study. *Pattern Recognition Letters*, 32(5), 656-665. 

[10] Ren, J., Qiu, Z., Fan, W., Cheng, H., & Yu, P. S. (2008). Forward semi-supervised feature selection. 
*Advances  in  Knowledge  Discovery  and  Data  Mining:  12th  Pacific-Asia  Conference,  PAKDD  2008 
Osaka, Japan, May 20-23, 2008 Proceedings 12 (pp. 970-976). Springer Berlin Heidelberg.*

[11] Xu, Z., King, I., Lyu, M. R. T., & Jin, R. (2010). Discriminative semi-supervised feature selection 
via manifold regularization. *IEEE Transactions on Neural networks*, 21(7), 1033-1047. 

[12] Yang, M., Chen, Y. J., Ji, G. L. (2010). Semi_Fisher Score: A semi-supervised method for feature 
selection. *2010 International Conference on Machine Learning and Cybernetics (Vol. 1, pp. 527-532). 
IEEE.*

[13] Zhao, Z., Liu, H. (2007). Semi-supervised feature selection via spectral analysis, *Proceedings of 
the  2007  SIAM  international  conference  on  data  mining (pp.  641-646).  Society  for  Industrial  and 
Applied Mathematics.*

[14] Zhao, J., Lu, K., & He, X. (2008). Locality sensitive semi-supervised feature lection. 
*Neurocomputing*, 71(10-12), 1842-1849. 

[15] Zhang, D., Chen, S., & Zhou, Z. H. (2008). Constraint score: A new filter method for feature 
selection with pairwise constraints, *Pattern Recognition*, 41(5), 1440-1451.

### Etat de l'art 3 : Sélection de variable pour le multi-label & multi-label partiel
Je veux la bibliographie ci-dessous avec le nom de la revue en italic
[1] Alalga, A., Benabdeslem, K., & Taleb, N. (2016). Soft-constrained Laplacian score for semi-supervised multi-label feature selection. *Knowledge and Information Systems*, 47(1), 75-98.  

[2] Bao, W. X., Hang, J. Y., & Zhang, M. L. (2021, August). Partial label dimensionality reduction via confidence-based dependence maximization. *In Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data
Mining* (pp. 46-54).  

[3] Bao, W. X., Hang, J. Y., & Zhang, M. L. (2022, August). Submodular Feature Selection for Partial Label Learning. *In Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining* (pp. 26-34).  

[4] Boutell, M. R., Luo, J., Shen, X., & Brown, C. M. (2004). Learning multi-label scene classification. *Pattern recognition*, 37(9), 1757-1771.  

[5] Chang, X., Nie, F., Yang, Y., & Huang, H. (2014, June). A convex formulation for semi- supervised multi-label feature selection. *In Proceedings of the AAAI Conference on Artificial Intelligence* (Vol. 28, No. 1).  

[6] Chang, X., Shen, H., Wang, S., Liu, J., & Li, X. (2014). Semi-supervised feature analysis for multimedia annotation by mining label correlation. *In Advances in Knowledge Discovery and Data Mining: 18th Pacific-Asia Conference, PAKDD 2014, Tainan, Taiwan, May 13-16, 2014. Proceedings, Part II 18* (pp. 74-85). Springer International Publishing.  

[7] Clare, A., & King, R. D. (2001). Knowledge discovery in multi-label phenotype data. *In Principles of Data Mining and Knowledge Discovery: 5th European Conference, PKDD 2001, Freiburg, Germany, September 3–5, 2001
Proceedings 5* (pp. 42-53). Springer Berlin Heidelberg.  

[8] Elghazel, H., Aussem, A., Gharroudi, O., & Saadaoui, W. (2016). Ensemble multi-label text categorization based on rotation forest and latent semantic indexing. *Expert Systems with Applications*, 57, 1-11.  

[9] Elisseeff, A., & Weston, J. (2001). A kernel method for multi-labelled classification. *Advances in neural information processing systems*, 14.  

[10] Gharroudi, O., Elghazel, H., & Aussem, A. (2014). A comparison of multi-label feature selection methods using the random forest paradigm. *In Advances in Artificial Intelligence: 27th Canadian Conference on Artificial Intelligence, Canadian AI 2014, Montréal, QC, Canada, May 6-9, 2014. Proceedings 27* (pp. 95-106). Springer International Publishing.  

[11] Gu, Q., Li, Z., & Han, J. (2011, October). Correlated multi-label feature selection. *In Proceedings of the 20th ACM international conference on Information and knowledge management* (pp. 1087-1096).  

[12] He, J., Gu, H., & Wang, Z. (2012). Bayesian multi-instance multi-label learning using Gaussian process prior. *Machine learning*, 88(1-2), 273-295.  

[13] Kashef, S., Nezamabadi‐pour, H., & Nikpour, B. (2018). Multilabel feature selection: A comprehensive review and guiding experiments. *Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery*, 8(2), e1240.  

[14] Kira, K., & Rendell, L. A. (1992). The feature selection problem: Traditional methods and a new algorithm. *In Aaai (Vol. 2, No. 1992a, pp. 129-134).*  

[15] Kong, X., & Yu, P. S. (2012). gMLC: a multi-label feature selection framework for graph classification. *Knowledge and information systems*, 31, 281-305.  

[16] Lastra, G., Luaces, O., Quevedo, J. R., & Bahamonde, A. (2011). Graphical feature selection for multilabel classification tasks. *In Advances in Intelligent Data Analysis X: 10th International Symposium, IDA 2011, Porto, Portugal, October 29-31, 2011. Proceedings 10* (pp. 246-257). Springer Berlin Heidelberg.  

[17] Liu, H., Zhang, S., & Wu, X. (2014). MLSLR: Multilabel learning via sparse logistic regression. *Information Sciences*, 281, 310-320.  

[18] Lo, H. Y., Wang, J. C., Wang, H. M., & Lin, S. D. (2011). Cost-sensitive multi-label learning for audio tag annotation and retrieval. *IEEE Transactions on Multimedia*, 13(3), 518-529.  

[19] Lv, S., Shi, S., Wang, H., & Li, F. (2021). Semi-supervised multi-label feature selection with adaptive structure learning and manifold learning. *Knowledge-based systems*, 214, 106757.  

[20] Ma, Z., Nie, F., Yang, Y., Uijlings, J. R., Sebe, N., & Hauptmann, A. G. (2012). Discriminating joint feature analysis for multimedia data understanding. *IEEE Transactions on Multimedia*, 14(6), 1662-1672.  

[21] Madjarov, G., Kocev, D., Gjorgjevikj, D., & Džeroski, S. (2012). An extensive experimental comparison of methods for multi-label learning. *Pattern recognition*, 45(9), 3084-3104.  

[22] Nie, F., Huang, H., Cai, X., & Ding, C. (2010). Efficient and robust feature selection via joint ℓ2, 1-norms minimization. *Advances in neural information processing systems*, 23.  

[23] Nie, F., Xu, D., Tsang, I. W. H., & Zhang, C. (2010). Flexible manifold embedding: A framework for semi-supervised and unsupervised dimension reduction. *IEEE Transactions onImage Processing*, 19(7), 1921-1932.  

[24] Pereira, R. B., Carvalho, A. P. D., Zadrozny, B., & Merschmann, L. H. D. C. (2015). Information gain feature selection for multi-label classification.  

[25] Read, J. (2008). A pruned problem transformation method for multi-label classification. *Proceedings 2008 New Zealand Com-puter Science Research Student Conference (NZCSRS 2008), pp. 143–150*  

[26] Ren, Y., Zhang, G., Yu, G., & Li, X. (2012). Local and global structure preserving based feature selection. *Neurocomputing*, 89, 147-157.  

[27] Reyes, O., Morell, C., & Ventura, S. (2015). Scalable extensions of the ReliefF algorithm for weighting and selecting features in multi-label datasets. *Neurocomputing*, 161, 168-182. 
    
[28] Trohidis, K., Tsoumakas, G., Kalliris, G., & Vlahavas, I. P. (2008, September). Multi-label classification of music into emotions. *In ISMIR (Vol. 8, pp. 325-330).*  

[29] Wang, J., Li, P., & Yu, K. (2022, July). Partial Multi-Label Feature Selection. *In 2022 International Joint Conference on Neural Networks (IJCNN) (pp. 1-9). IEEE.*  

[30] Wang, X. D., Chen, R. C., Hong, C. Q., Zeng, Z. Q., & Zhou, Z. L. (2017). Semi-supervised multi-label feature selection via label correlation analysis with l1-norm graph embedding. *Image and Vision Computing*, 63, 10-23.  

[31] Wu, J. S., Huang, S. J., & Zhou, Z. H. (2014). Genome-wide protein function prediction through multi-instance multi-label learning. *IEEE/ACM Transactions on Computational Biology and Bioinformatics*, 11(5), 891-902.  

[32] Xie, M. K., & Huang, S. J. (2018, April). Partial multi-label learning. *In Proceedings of the AAAI Conference on Artificial Intelligence (Vol. 32, No. 1).*  

[33] Xie, M. K., Sun, F., & Huang, S. J. (2021, August). Partial multi-label learning with meta disambiguation. *In Proceedings of the 27th ACM SIGKDD conference on knowledge discovery & data mining* (pp. 1904-1912).  

[34] Xu, T., Xu, Y., Yang, S., Li, B., & Zhang, W. (2023). Learning Accurate Label-Specific Features From Partially Multilabeled Data. *IEEE Transactions on Neural Networks and Learning Systems*.  

[35] Xu, Y., Wang, J., An, S., Wei, J., & Ruan, J. (2018, October). Semi-supervised multi-label feature selection by preserving feature-label space consistency. *In Proceedings of the 27th ACM international conference on information and knowledge management* (pp. 783-792).  

[36] You, M., Liu, J., Li, G. Z., & Chen, Y. (2012). Embedded feature selection for multi-label classification of music emotions. *International Journal of Computational Intelligence Systems*, 5(4), 668-678.  

[37] Yu, L., & Liu, H. (2004). Efficient feature selection via analysis of relevance and redundancy. *The Journal of Machine Learning Research*, 5, 1205-1224.  

[38] Yu, T., Yu, G., Wang, J., & Guo, M. (2020). Partial multi-label learning with label and feature collaboration. *In Database Systems for Advanced Applications: 25th International Conference, DASFAA 2020, Jeju, South Korea, September 24–27, 2020, Proceedings, Part I 25* (pp. 621-637). Springer International Publishing.  

[39] Yu, Y., & Wang, Y. (2014). Feature selection for multi-label learning using mutual information and GA. *In Rough Sets and Knowledge Technology: 9th International Conference, RSKT 2014, Shanghai, China, October 24-26, 2014, Proceedings 9* (pp. 454-463). Springer International Publishing.  

[40] Zhang, M. L., Peña, J. M., & Robles, V. (2009). Feature selection for multi-label naive Bayes classification. *Information Sciences*, 179(19), 3218-3229.  

[41] Zhang, M. L., & Zhang, K. (2010, July). Multi-label learning by exploiting label dependency. *In Proceedings of the 16th ACM SIGKDD international conference on Knowledge discovery and data mining* (pp. 999-1008).  

[42] Zhang, M. L., & Zhou, Z. H. (2007). ML-KNN: A lazy learning approach to multi-label learning. *Pattern recognition*, 40(7), 2038-2048.  

[43] Zhang, M. L., & Zhou, Z. H. (2013). A review on multi-label learning algorithms. *IEEE transactions on knowledge and data engineering*, 26(8), 1819-1837.  

[44] Zhang, M. L., Wu, J. H., & Bao, W. X. (2022). Disambiguation enabled linear discriminant analysis for partial label dimensionality reduction. *ACM Transactions on Knowledge Discovery from Data (TKDD), 16*(4), 1-18.  

[45] Zhang, Y., Gong, D. W., Sun, X. Y., & Guo, Y. N. (2017). A PSO-based multi-objective multi-label feature selection method in classification. *Scientific reports*, 7(1), 1-12.  