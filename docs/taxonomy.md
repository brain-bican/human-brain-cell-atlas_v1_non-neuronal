## Human Brain Cell Atlas v1.0 Taxonomy (Non-Neuronal)

Atlas of human primary motor cortex (M1), developed in collaboration with the BRAIN Initiative Cell Census Network (BICCN).
First draft atlas of human brain transcriptomic cell types: The human brain directs a wide range of complex behaviors ranging from fine motor skills to abstract intelligence and emotion. This broad range of functions is supported by an exceptionally complex cellular and circuit architecture. To create a first draft human brain cell atlas, high-throughput single-nucleus RNA sequencing was used to systematically survey cells across the entire adult human brain in three postmortem donors. Over three million nuclei were sampled from approximately 100 dissections across the forebrain, midbrain, and hindbrain. Analysis of these data showed regional diversity in that cellular organization exhibited regional diversity at multiple scales, identifying 30 superclusters, 461 clusters and 3313 subclusters. As the first single-cell transcriptomic census of the entire human brain, this atlas provides a resource for understanding the molecular diversity of the human brain in health and disease. The Human Brain Cell Atlas v1.0 is presented for visualization and data mining through the Chan Zuckerberg Initiative’s CellxGene application, with the following biologically meaningful partitions: 1. Neuronal and non-neuronal cell types 2. Supercluster-specific groupings (`Supercluster: `) 3.Brain region-specific groupings (`Dissection: `), ordered by the adult human brain anatomical reference atlas ontology in Ding et al. (2016)

---

**Matrix File ID:** CellXGene_dataset:b165f033-9dec-468a-9248-802fc6902a74

**Cell Annotation URL:** https://purl.brain-bican.org/taxonomy/CS202210140/CS202210140.json

**Author name:** Kimberly Siletti

**Author contact:** 

**Author orcid:** https://orcid.org/0000-0001-7620-8973


---

**Cell Annotation Schema Version:** 0.2b0

**Cell Annotation Timestamp:** 

**Cell Annotation Version:** 

---

**Labelsets:**

| Name | Description | Annotation Method | Rank |
|------|-------------|-------------------|------|
|subcluster|The finest level of cell type definition in the human whole brain taxonomy. It is defined by applying Louvain clustering independently for each cluster. Cells within a subcluster share similar characteristics and belong to the same cluster. In some cases subclusters are distinct, and in other cases represent cell states or gradients within the same cluster.||0|
|Cluster|An intermediate level of cell type definitions in the human whole brain taxonomy. It is defined by applying Louvain clustering independently for each supercluster. All cells within a subcluster belong to the same cluster. Clusters group together similar subclusters and are highly distinct from one another.||1|
|supercluster_term|The top level of cell type definition in the human whole brain taxonomy. It is defined using Louvain clustering (Cytograph) with most superclusters determined by broad brain region and neurotransmitter type. All cells within a cluster belong to the same supercluster. Supercluster provides a broader characterization of cell types.||2|
