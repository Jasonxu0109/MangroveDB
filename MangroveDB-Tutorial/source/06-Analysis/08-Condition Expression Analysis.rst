==========================
Condition Expression Analysis
==========================
This tool provides a boxplot of the gene expression values of a single gene.

Read before use
------------------		
Users need to prepare three files, gene expression matrix, metadata information, and a single gene.

**The gene expression matrix:** The first column is Geneid, other columns are data. The name of first column must be Geneid. Data from excel (format: xlsx).

**The metadata:** The data must contain Samples, BioProject, Treatment, Tissue, and Groups columns. Data from excel (format: xlsx).

**Single gene:** The first column is Geneid. The name of first column must be Geneid. Data from excel (format: xlsx).

**Note:** The order of the sample names in both gene expression matrix and metadata information files must be consistent.

**Input example data:** `Gene expression matrix <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Gene_expression_under_stress_condition.xlsx>`_,
`Metadata information <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Sample_groups_under_stress_condition.xlsx>`_,
`Single gene <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Gene_under_stress_condition.xlsx>`_.
		
.. image:: ../../_static/images/boxplot.png
        :width: 100%
        :align: center



