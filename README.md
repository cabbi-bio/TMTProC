The TMTProC module is the group of scripts associated with our paper "TMTPro Complementary Ion Quantification Increases Plexing and Sensitivity for Accurate Multiplexed Proteomics at the MS2 Level".

Johnson, A., Stadlmeier, M., Wühr, M. April 30, 2021. [“TMTpro Complementary Ion Quantification Increases Plexing and Sensitivity for Accurate Multiplexed Proteomics at the MS2 Level.”](https://pubs.acs.org/doi/pdf/10.1021/acs.jproteome.0c00813) Journal of Proteome Research (20) 6: 3043–3052. DOI: 10.1021/acs.jproteome.0c00813.

We recommend using the stand-alone version. It is compatible with a MaxQuant search, with directions provided. The only inputs needed are a .raw file and a FASTA file.

The Git repository version requires the generation of an independent way to quantify the Fourier transform signal to noise ratio of complementary peaks. Files are analyzed using the "TMTProc_masterscript.m" script. Inputs include a reporter quant output file, which channels were used, and the S:N cutoff. Script outputs a matlab object with the deconvolved signal ratios in the complementary peaks and summary plots.
