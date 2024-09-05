# Methane and CO2 consumption from a synthetic waste gas by microbial communities in enriched seawater

This study explores how natural microbial communities can be manipulated into consuming both CH4 and CO2 from a gas stream and converting the gases into microbial biomass. Natural seawater was enriched with inorganic nutrients and injected with a continuous gas stream containing CH4 (4.7% v/v) and CO2 (1% v/v) over a period of several days, either in the dark or in the light. Microbial communities established that contained methanotrophic bacteria consuming CH4, and cyanobacteria and microalgae consuming CO2. The microbial communities were characterized using near-full-length 16S/18S rRNA gene amplicon sequencing with the Nanopore technology.

## Rmarkdown to reproduce statistical analyses and manuscript figures

```
cd scripts
Rscript -e 'rmarkdown::render(input = "statistical-analysis-16s.Rmd", output_file = paste0(getwd(), "/../results/statistical-analysis-16s.html"))'
Rscript -e 'rmarkdown::render(input = "statistical-analysis-18s.Rmd", output_file = paste0(getwd(), "/../results/statistical-analysis-18s.html"))'
Rscript -e 'rmarkdown::render(input = "publication-figures.Rmd", output_file = paste0(getwd(), "/../results/publication-figures.html"))'
```
