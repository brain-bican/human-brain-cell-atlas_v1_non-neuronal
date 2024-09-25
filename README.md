# Human Brain Cell Atlas v1.0 (Non-neuronal) (CS202210140)

First draft atlas of human brain transcriptomic cell types: The human brain directs a wide range of complex behaviors ranging from fine motor skills to abstract intelligence and emotion. This broad range of functions is supported by an exceptionally complex cellular and circuit architecture. To create a first draft human brain cell atlas, high-throughput single-nucleus RNA sequencing was used to systematically survey cells across the entire adult human brain in three postmortem donors. Over three million nuclei were sampled from approximately 100 dissections across the forebrain, midbrain, and hindbrain. Analysis of these data showed regional diversity in that cellular organization exhibited regional diversity at multiple scales, identifying 30 superclusters, 461 clusters and 3313 subclusters. As the first single-cell transcriptomic census of the entire human brain, this atlas provides a resource for understanding the molecular diversity of the human brain in health and disease. The Human Brain Cell Atlas v1.0 is presented for visualization and data mining through the Chan Zuckerberg Initiative’s CellxGene application, with the following biologically meaningful partitions: 1. Neuronal and non-neuronal cell types 2. Supercluster-specific groupings (`Supercluster: `) 3.Brain region-specific groupings (`Dissection: `), ordered by the adult human brain anatomical reference atlas ontology in Ding et al. (2016)

Reference: https://doi.org/10.1126/science.add7046   
CellxGene collection: https://cellxgene.cziscience.com/collections/283d65eb-dd53-496d-adb7-7570c7caa443  
PURL: https://purl.brain-bican.org/taxonomy/CS202210140/CS202210140_non-neuronal/

## Stable release versions

The latest version of the taxonomy can always be found at:

https://purl.brain-bican.org/taxonomy/CCN202210140/CS202210140_non-neuronal.json

## Curate taxonomy
Curate your taxonomy in 3 simple steps:

- [Human Brain Cell Atlas v1.0 (Non-neuronal) (CS202210140)](#human-brain-cell-atlas-v10-non-neuronal-cs202210140)
  - [Stable release versions](#stable-release-versions)
  - [Curate taxonomy](#curate-taxonomy)
    - [Get Taxonomy Development Tools](#get-taxonomy-development-tools)
    - [Load your data](#load-your-data)
    - [Browse](#browse)

### Get Taxonomy Development Tools 

Pull the latest TDT docker image via following the steps defined in the project [GitHub Container Registry](https://github.com/brain-bican/taxonomy-development-tools/pkgs/container/taxonomy-development-tools). 

```
docker pull ghcr.io/brain-bican/taxonomy-development-tools:latest
```

### Load your data

Place your data (ex. [AIT115_annotation_sheet.tsv](https://github.com/brain-bican/taxonomy-development-tools/tree/main/examples/nhp_basal_ganglia/AIT115_annotation_sheet.tsv)) and configuration file (ex. [ingestion_config.yaml](https://github.com/brain-bican/taxonomy-development-tools/tree/main/examples/nhp_basal_ganglia/ingestion_config.yaml)) into your project's `input_data` folder.  

Run following command in your project root folder to ingest your data files:

```
bash ./run.sh make load_data
```

### Browse

Run following command in your project root folder to run the online data editor:
```
bash ./run.sh make serve
```

This command will print a set of logs including a log like `nanobot::serve: listening on 0.0.0.0:3000`. This means your web editor is ready, and you can start editing your data.

You can start browsing web taxonomy editor from: [http://localhost:3000/table](http://localhost:3000/table)

_For further details see [Taxonomy Development Tools Documentation](https://brain-bican.github.io/taxonomy-development-tools/)_
