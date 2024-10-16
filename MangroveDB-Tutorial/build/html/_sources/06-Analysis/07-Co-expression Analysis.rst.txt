==========================
Co-expression Analysis
==========================
This tool provides a heatmap, which is a well-received approach to illustrate gene expression data.
And gene co-expression analysis can use raw read counts and other quantification measure arising from RNA-Seq.

Read before use
------------------		
Users need to prepare three files, gene expression matrix, metadata information, and genes list.

**The gene expression matrix:** The first column is Geneid, other columns are data. The name of first column must be Geneid. Data from excel (format: xlsx).

**The metadata:** The first column is sample names, the second column is treatment conditions, and the third column is group names.
Colnames must be Samples, Names, and Groups. Data from excel (format: xlsx).

**The gene list:** The first column is Geneid. The name of first column must be Geneid. Data from excel (format: xlsx).

**Note:** The order of the sample names in both gene expression matrix and metadata information files must be consistent.

**Input example data:** `Gene expression matrix <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Gene_expression_for_time_series_gene_expression_analysis.xlsx>`_,
`Metadata information <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Sample_groups_for_time_series_gene_expression_analysis.xlsx>`_,
`Gene list <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Gene_list_for_time_series_gene_expression_analysis.xlsx>`_.
		
.. image:: ../../_static/images/co.png
        :width: 100%
        :align: center
