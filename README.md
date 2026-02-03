# BioinformaticsPortofolio
Welcome! This Git concludes all Rafael's Bioinformatics Project, starting from research project to Independent Study and many more.
Feel Free to look around my past projects! If you have any follow-up questions, feel free to email me at: rafaelangeloyudhistira@gmail.com

## Begonia Research (February 2024 - September 2025)
For my final Bachelor Biotechnology Project, I was tasked to do a positive selection analysis on Begonia DNA Chloroplast. Based on Xiong et al. (2023) study, there are eight genes that are detected positively selected which are: _rpoC1, rpoB, psbE, psbK, petA, rpl22, rpl2_, and _rps12_. I was tasked to do another positive selection analysis on Indonesian Begonia samples taken from Bogor Botanic Gardens (Kebun Raya Bogor) genes (partial _rpoC1_ and _petA_) in comparison with Asian Begonia's that are available in NCBI. 

For this analysis, I used Phylogenetic Analysis Maximum Likelihood (PAML) ver 4.9. to detect any site-specific positive selection (Yang et al. 2005; Yang 2007). To detect which site is positively selected, model = 0 (single dN/dS ratio (ω) is assumed for all branches), and Site models = M7 (beta) and M8 (beta & ω > 1) were used as the site model. Other parameters were set to default. Posterior probabilities that are significant (p > 0.05) was selected as a candidate for detecting SNP marker (Xiong et al. 2023). 

## References
Xiong C, Huang Y, Li Z, Wu L, Liu Z, Zhu W, Li J, Xu R, Hong X. 2023. Comparative chloroplast genomics reveals the phylogeny and the adaptive evolution of Begonia in China. BMC Genomics. 24(1). DOI:10.1186/s12864-023-09563-3. https://pubmed.ncbi.nlm.nih.gov/37891463/ 

Yang Z. 2007. PAML 4: Phylogenetic analysis by maximum likelihood. Molecular Biology and Evolution. 24(8):1586–1591. DOI:10.1093/molbev/msm088. https://academic.oup.com/mbe/article/24/8/1586/1103731 

Yang Z, Wong WSW, Nielsen R. 2005. Bayes empirical Bayes inference of amino acid sites under positive selection. Molecular Biology and Evolution. 22(4):1107–1118. DOI:10.1093/molbev/msi097. https://academic.oup.com/mbe/article/22/4/1107/1083468 
