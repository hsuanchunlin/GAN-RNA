# Application of Generative Adversarial Network to Generate miRNA Like Structures

Generative adversarial network is an powerful tool in generation of images, style change, and voice conversion. MicroRNA (miRNA) is an single-stranded non-coding RNA with essential functions in RNA silencing and post transcriptional regulation in gene regulation. Customized miRNAs could help us to silence specific gene and be utilized in gene therapy. Here I applied GAN on generation of miRNA like structures as a personal little project to discover the potential of GAN in novel miRNA design. 

## Material

- To download miRNA database, go to [miRBase](http://www.mirbase.org/ftp.shtml), and download [hairpin.fa](ftp://mirbase.org/pub/mirbase/CURRENT/hairpin.fa.gz).
- After downloading, use Convert_RNAtoMatrix.ipynb to convert the hairpin structure to character table.
- Use Study_EZGAN_hairpin_Generation_random_matrix.ipynb to train the small GAN model and generate your miRNAs.

Here is an example for the generated miRNA like sequence.\
![RNA_demo](./image/RNA.png)\
To test the secondary structure of the generated sequences, use [mfold](http://www.unafold.org/mfold/applications/rna-folding-form.php)\ 
