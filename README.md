# mc1r-canideos-alinhamento
Análise do gene melanocortin 1 receptor (MC1R) em canídeos com Python e Biopython
## Objetivo
O projeto visa alinhar o gene MC1R do cão doméstico, dingo e lobo mexicano, a fim de comparar as sequências de nucleotídeos e analisar a conservação do gene.
## Método
Utilizou-se a base de dados National Center of Biotechnology Information (NCBI) para coletar as sequências do gene MC1R nas três espécies de canídeos. As sequências obtidas foram lançadas no Clustal Omega para encontrar os Single Nucleotide Polymorphisms (SNPs). O código foi feito em Python para comparar (PairwiseAligner) e obter o score do alinhamento, depois foi inserido no Google Colab para ser executado em Biopython.

**Softwares utilizados**
- Clustal Omega
- NCBI
- Google Colab
- Python + Biopython (PairwiseAligner)
## Resultados
O alinhamento mostrou alta conservação do gene, sendo maior que 95% de identidade com SNPs pontuais (`.`) que explicam a variação de cor entre o cão doméstico, o dingo e o lobo mexicano. A variação de cor está ligada à produção de eumelanina e feomelanina pelo gene MC1R.
Arquivos gerados: `src/alinhamento_mc1r.py` e `src/results_mc1r.txt`
