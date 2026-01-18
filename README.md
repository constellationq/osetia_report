# osetia_report
##создание символических ссылок
ln -s <целевой файл> <имя ссылки> 
##fastqc  оценка 
fastqc raw_data/*.fastq.gz -o quality_of_raw_data
##multiqc
multiqc quality_of_raw_data -o quality_of_raw_data -f
