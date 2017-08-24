### Flexbar – flexible barcode and adapter removal

The program Flexbar preprocesses high-throughput sequencing data efficiently. It demultiplexes barcoded runs and removes adapter sequences. Moreover, trimming and filtering features are provided. Flexbar increases read mapping rates and improves genome as well as transcriptome assemblies. It supports next-generation sequencing data in fasta and fastq format, e.g. from Roche 454 and the Illumina platform.

Refer to the [manual](https://github.com/seqan/flexbar/wiki) or contact [jtroehr](https://github.com/jtroehr) for support with this application.

![Flexbar logo](https://github.com/seqan/flexbar/wiki/images/flexbar-logo.png)


### References

Johannes T. Roehr, Christoph Dieterich, Knut Reinert: Flexbar 3.0 – SIMD and multicore parallelization. Bioinformatics 2017.

See article on [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/28541403)

Matthias Dodt, Johannes T. Roehr, Rina Ahmed, Christoph Dieterich: Flexbar – flexible barcode and adapter processing for next-generation sequencing platforms. Biology 2012.

See article on [PubMed](https://www.ncbi.nlm.nih.gov/pubmed/24832523)

### Use docker image

docker run -it --rm cmonjeau/flexbar:latest -v /local_data:/container_data flexbar -r /container_data/reads [-b barcodes] [-a adapters] [options]

