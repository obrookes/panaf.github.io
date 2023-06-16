![](assets/media/images/dataset_overview.jpg)

---

# **Dataset download coming soon!**

---

### **Overview**

We present the PanAf20K dataset, the largest and most diverse open-access annotated video dataset of great apes in their natural environment. It comprises more than 7 million frames across 20,000 camera trap videos of chimpanzees and gorillas collected at 18 field sites in tropical Africa as part of the Pan African Programme: The Cultured Chimpanzee. The footage is accompanied by a rich set of annotations and benchmarks making it suitable for training and testing a variety of challenging and ecologically important tasks including detection, species classification, fine-grained and multi-label action recognition. Furthering AI analysis of camera trap information is critical given the International Union for Conservation of Nature now lists all species in the great ape family as either Endangered or Critically Endangered. We hope the dataset can form a solid basis for engagement of the AI community to improve performance, efficiency and result interpretation in order to support assessments of great ape presence, abundance, distribution, and behaviour and thereby aid conservation efforts.

The PanAf20K dataset consists of two distinct parts. The first includes a large video dataset containing approximately 20,000 videos annotated with multi-label behavioural labels. The second part comprises 500 videos with 180k+ fine-grained annotations. The difference between annotation types is shown below:

![](assets/media/images/annotation_examples.jpg)

#### **Part 1: PanAf20K**

Multi-label Behavioural Annotation of PanAf-20K. Citizens scientists on the Chimp&See platform provided multi-label behavioural annotations for 20,000 videos. During annotation, particular focus was given to ecologically and anthropologically important behaviours such as tool use, camera reaction and bipedalism. To ensure annotation quality and consistency a video was only deemed to be analyzed when either three volunteers marked the video as blank, seven volunteers unanimously agreed on the behaviour of the animal present, or 15 volunteers annotated the video. These annotations were then extracted and expertly grouped into 18 co-occurring classes comprising ~40 sub-classes, which form the multi-label behavioural annotations presented here.

![](assets/media/images/p20k_dist.jpg)

#### **Part2: PanAf500**

The PanAf-500 was ground-truth labelled by users on the citizens science platform Chimp&See and researchers at the University of Bristol. We re-formatted the metadata from these sources specifically for use in computer vision under reproducible and comparable benchmarks ready for AI-use. The dataset includes frame-by-frame annotations for full-body location, intra-video individual identification, species classification, and nine behavioural actions across 500 videos and 180k+ frames. The behavioural action annotations cover 9 basic behavioural actions; sitting, standing, walking, running, climbing up, climbing down, hanging, sitting on back, camera interaction.

![](assets/media/images/p500_dist.jpg)

---

### **Benchmarks**

---

### **Citation**

```BibTeX
 @article{brookes2023panaf20k,
  title={PanAf20K: A Large Video Dataset for Wild Ape Detection & Behaviour Analysis},
  author={Brookes, Otto and Mirmehdi, Majid and Stephens, Colleen and McCarthy, Maureen and Murai, Mizuki and Normand, Emmanuelle and Vergnes, Virginie and Meier, Amelia and Lapuente, Juan and Wittig, Roman and Dowd, Dervla and Jones, Sorrel and Leinert, Vera and Wessling, Erin and Corogenes, Katherine and  Zuberb{\"u}hler, Klaus and Lee, Kevin and  Angedakin, Samuel and  Langergraber, Kevin and Dieguez, Paula and Maldonado, Nuria and Boesch, Christophe and Arandjelovic, Mimi and K{\"u}hl, Hjalmar and Burghardt, Tilo},
  year={2023}
}
 ```
---

### **Acknowledgments**

We thank the Pan African Programme: ‘The Cultured Chimpanzee’ team and its collaborators for allowing the use of their data for this paper. We thank Amelie Pettrich, Antonio Buzharevski, Eva Martinez Garcia, Ivana Kirchmair, Sebastian Schütte, Linda Gerlach and Fabina Haas. We also thank management and support staff across all sites; specifically Yasmin Moebius, Geoffrey Muhanguzi, Martha Robbins, Henk Eshuis, Sergio Marrocoli and John Hart. Thanks to the team at https://www.chimpandsee.org particularly Briana Harder, Anja Landsmann, Laura K. Lynn, Zuzana Macháčková, Heidi Pfund, Kristeena Sigler and Jane Widness. The work that allowed for the collection of the dataset was funded by the Max Planck Society, Max Planck Society Innovation Fund, and Heinz L. Krekeler. In this respect we would like to thank: Ministre des Eaux et Forêts, Ministère de l'Enseignement supérieur et de la Recherche scientifique in Côte d’Ivoire; Institut Congolais pour la Conservation de la Nature, Ministère de la Recherche Scientifique in Democratic Republic of Congo; Forestry Development Authority in Liberia; Direction Des Eaux Et Forêts, Chasses Et Conservation Des Sols in Senegal; Makerere University Biological Field Station, Uganda National Council for Science and Technology, Uganda Wildlife Authority, National Forestry Authority in Uganda; National Institute for Forestry Development and Protected Area Management, Ministry of Agriculture and Forests, Ministry of Fisheries and Environment in Equatorial Guinea. This work was supported by the UKRI CDT in Interactive AI under grant EP/S022937/1.








