# PWM-deltaSVM-comparison
Supplementary data for "Positional weight matrices have sufficient prediction power for analysis of noncoding variants".<br>
This project contains the following data:
- <b>Pwm_aupr_2c.tsv</b> - Performance of Yan et al. ΔPWM in predicting preferential binding SNPs on the 1st batch of the SNP-SELEX data (provided by prof. Bing Ren).<br><br>
  Format:
  * *rs_id*, *snp* - genomic position and alleles information,<br>
  * *tf* - transcription factor,<br>
  * *or* - allele imbalance score in corresponding ChIP-Seq experiment,<br>
  * *allelic ratio* - either pwm or pbs score depending on the *model*,
  * *model* - PWM or PBS.

- <b>Chip_asb_hepg2.tsv</b> - Comparison of Yan et al. ΔPWM predictions and DNA binding biases detected in ChIP-Seq experiments in HepG2 cells (provided by prof. Bing Ren).<br><br>
    Format:
  * *tf* - transcription factor,<br>
  * *aupr* - area under precision-recall curve,<br>
  * *auroc* - area under the receiver operating characteristic.<br>

- <b>Supplementary_table_S1.xlsx</b> - Overview of PWMs and their performance in recognizing SNPs affecting transcription factor binding in SNP-SELEX data.<br>
