# mc1r-canideos-alinhamento
Análise do gene melanocortin 1 receptor (MC1R) em canídeos com Python e Biopython
## Objetivo
O projeto visa alinhar o gene MC1R do cão doméstico, dingo e lobo mexicano, a fim de comparar as sequências de nucleotídeos e analisar a conservação do gene.
## Método
Utilizou-se a base de dados National Center for Biotechnology Information (NCBI) para coletar as sequências do gene MC1R nas três espécies de canídeos. As sequências obtidas foram lançadas no Clustal Omega para encontrar os Single Nucleotide Polymorphisms (SNPs). O código foi feito em Python para comparar (PairwiseAligner) e obter o score do alinhamento, depois foi inserido no Google Colab para ser executado em Biopython.

**Softwares utilizados**
- Clustal Omega
- NCBI
- Google Colab
- Python + Biopython (PairwiseAligner)
## Resultados
O alinhamento mostrou alta conservação do gene, sendo maior que 99% de identidade entre os três canídeos. Há SNP A>T e C>G nas posições 180 e 840, respectivamente. A ocorrência de SNPs explica a variação de cor entre o cão doméstico, o dingo e o lobo mexicano. O gene MC1R possui 954 pares de base (bp).

**Alinhamento do gene**
- Cão vs lobo: 99,90% (1 SNP, 0,1% de diferença)
- Cão vs dingo: 99,79% (2 SNPs, 0,21% de diferença)
- Dingo vs lobo: 99,90% (1 SNP, 0,1% de diferença)
 
### Saídas do projeto
- Código e resultados: `src/alinhamento_mc1r.py`, `src/results_mc1r.txt`
- Figuras finais (fundo branco): `docs/finais/`
    - `guide tree.png` e `phylogram.png`
    - `snp_trecho1.png` e `snp_trecho2.png`
    - `percentual_identidade.png`
- Figuras originais: `docs/originais/`
