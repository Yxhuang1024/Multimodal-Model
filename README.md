# Multimodal-Model
This is the data and code required for the article：

🔗link：
# 0 Introduction

# 1 Data
## 1.1 Sequence data
The sequence data were collected from Uniprot Swiss-prot, dated 2024.8.1, a manually reviewed protein database containing **571,864** sequences.You can download our sequence data here：

🔗:https://zenodo.org/me/uploads?q=&l=list&p=1&s=10&sort=newest

## 1.2 Structural data
The structural data comes from Alphafold db V2, which predicts the structure of the aforementioned sequences and contains a total of **542,265** structural data.You can download our sequence data here：

🔗:https://zenodo.org/me/uploads?q=&l=list&p=1&s=10&sort=newest

## 1.3 Protein Annotation
There are two types of protein annotations, namely natural text description and functional label description. The former describes the function of the protein through a large paragraph of text, while the latter provides several functional labels corresponding to the protein. Natural text and feature labels can be downloaded here：

🔗:https://zenodo.org/me/uploads?q=&l=list&p=1&s=10&sort=newest

Examples of the two are as follows:

**Sequence**：MRWQEMGYIFYPRKLR   
**Natural text**: Regulates insulin sensitivity and metabolic homeostasis.Inhibits the folate cycle, thereby reducing de novo purine biosynthesis which leads to the accumulation of the de novo purine synthesis intermediate 5-aminoimidazole-4-carboxamide (AICAR) and the....    
**Function label**：DNA-binding、Osteogenesis、Transcription、Reference proteome...   

## 1.4 Amino acid annotation
Amino acid annotation is that a protein may contain several functional fragments. We annotate each fragment and describe its function. We use Interpro annotation, and the file is protein2ipr.dat. You can download it here:

🔗:https://zenodo.org/me/uploads?q=&l=list&p=1&s=10&sort=newest

# 2 Code


# 3 Results
