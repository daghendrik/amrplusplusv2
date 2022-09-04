# Microbial Ecology Group (MEG)

Our international multidisciplinary group of scientists and educators is addressing the issues of antimicrobial resistance (AMR) and microbial ecology in agriculture through research, outreach, and education. By characterizing risks related to AMR and microbial ecology, our center will identify agricultural production practices that are harmful and can be avoided, while also identifying and promoting production practices and interventions that are beneficial or do no harm to the ecosystem or public health. This will allow society to realize “sustainable intensification” of agriculture.

## MEGARes and the AmrPlusPlus v2.0 bioinformatic pipeline

The MEGARes database (https://megares.meglab.org/) contains sequence data for approximately 8,000 hand-curated antimicrobial resistance genes accompanied by an annotation structure that is optimized for use with high throughput sequencing and metagenomic analysis. The acyclical annotation graph of MEGARes allows for accurate, count-based, hierarchical statistical analysis of resistance at the population level, much like microbiome analysis, and is also designed to be used as a training database for the creation of statistical classifiers. The latest update in MEGARes 2.0 ([https://megares.meglab.org](https://megares.meglab.org)) incorporates previously published resistance sequences for antimicrobial drugs, while also expanding to include published sequences for metal and biocide resistance determinants.

The goal of many metagenomics studies is to characterize the content and relative abundance of sequences of interest from the DNA of a given sample or set of samples. You may want to know what is contained within your sample or how abundant a given sequence is relative to another.

Often, metagenomics is performed when the answer to these questions must be obtained for a large number of targets where techniques like multiplex PCR and other targeted methods would be too cumbersome to perform. AmrPlusPlus v2.0 can process the raw data from the sequencer, identify the fragments of DNA, and count them. It also provides a count of the polymorphisms that occur in each DNA fragment with respect to the reference database.

Additionally, you may want to know if the depth of your sequencing (how many reads you obtain that are on target) is high enough to identify rare organisms (organisms with low abundance relative to others) in your population. This is referred to as rarefaction and is calculated by randomly subsampling your sequence data at intervals between 0% and 100% in order to determine how many targets are found at each depth.With AmrPlusPlus v2.0, you will obtain alignment count files for each sample that can be combined into a count matrix and analyzed using any statistical and mathematical techniques that can operate on a matrix of observations.

---

### More Information 

- [References](references.md)
- [Citing AMR++](citing.md)
- [Accessing AMR Plus Plus v2.0](accessing_AMR.md)
- [Installation](installation.md)
- [Usage](usage.md)
- [Configuration](configuration.md)
- [Output](output.md)
- [Dependencies](dependencies.md)
- [Software Requirements](requirements.md)
- [FAQs](FAQs.md)
- [Contact](contact.md)
- [AmrPlusPlus v1](https://megares.meglab.org/)