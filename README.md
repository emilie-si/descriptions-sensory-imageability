# Supplementary Material for “Laying out the subject before the eyes”? Measuring Sensory Information and Imageability in Literary Spatial Descriptions

This repository contains the supplementary material for our paper “Laying out the subject before the eyes”? Measuring Sensory Information and Imageability in Literary Spatial Descriptions (Emilie Sitter and Berenike Herrmann; CHR2027).

## Contents

| File | Description |
|------|-------------|
| `classifier_annotations_raw.csv` | Raw classifier annotations obtained by BERT classifier used to create the datasets |
| `spatial_descriptions.csv` | Spatial Descriptions according to the classifier; some FPs were filtered out manually/via LLM |
| `reference.csv` | Sentences not classified as spatial descriptions |
| `preprocessing.ipynb` | Jupyter Notebook (Python) for preprocessing the data and descriptive stats |
| `analysis.ipynb` | R Notebook for statistical analyses |


> **Note:** Large files in this repository are stored with [Git LFS](https://git-lfs.com/). Please install Git LFS and run `git lfs install` before cloning, otherwise you will only get pointer files instead of the actual data.

## Related Resources

- **German Spatial Descriptions Dataset:** [LAW2025-Descriptions](https://github.com/emilie-si/LAW2025-Descriptions)


## Citation

If you use this dataset in your research, please cite our paper:

```bibtex
@inproceedings{sitter_herrmann_descriptions,
  title     = {“Laying out the subject before the eyes”? Measuring Sensory Information and Imageability in Literary Spatial Descriptions},
  author    = {Sitter, Emilie and Herrmann, Berenike},
  year      = {in preparation},
language = {en},
}


```

## Contact

For questions, please contact [emilie.sitter@uni-bielefeld.de](mailto:emilie.sitter@uni-bielefeld.de).
