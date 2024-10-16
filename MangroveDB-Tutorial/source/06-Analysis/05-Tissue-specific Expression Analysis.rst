==========================
Tissue-specific Expression Analysis
==========================
Currently, the tissue-specific patterns analysis provide valuable information about their potential functions for further studies.

Read before use
------------------	
Users need to prepare two files, gene expression matrix and metadata information.

**The gene expression matrix:** The first column is Geneid, other columns are data. The name of first column must be Geneid. Data from excel (format: xlsx).

**The metadata:** The first column is sample names, the second column is treatment conditions, and the third column is group names.
Colnames must be Samples, Names, and Groups. Data from excel (format: xlsx).

**Note:** The order of the sample names in both files must be consistent.

tau value calculator
------------------
This tool provides a tau value calculator. The tau values varies from 0 to 1.
Gene with tau value close to 1 represented tissue specificity of gene expression, while gene with tau value close to 0 indicated sharing of gene expression across different tissues.

**Input example data:** `Gene expression matrix <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Gene_expression_for_tissue-specific_analysis.xlsx>`_,
`Metadata information <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Sample_groups_for_tissue-specific_analysis.xlsx>`_.

.. image:: ../../_static/images/tvalue.png
        :width: 100%
        :align: center

Venn plot
------------------
This tool provides vennplot for tissue-specific gene expression. 
Tissue-specific genes are a class of genes whose functions and expressions are preferred in one or several tissues restrictedly. 
Identification of tissue-specific genes is essential for discovering multi-cellular biological processes such as tissue-specific molecular regulations, tissue development, physiology, and the pathogenesis of tissue-associated diseases.

Users need to prepare two files, gene expression matrix and metadata information.

**The gene expression matrix:** The first column is Geneid, other columns are data. The name of first column must be Geneid. Data from excel (format: xlsx).

**The metadata:** The first column is sample names, the second column is treatment conditions, and the third column is group names.
Colnames must be Samples, Names, and Groups. Data from excel (format: xlsx).

**Note:** The order of the sample names in both files must be consistent.

**Input example data:** `Gene expression matrix <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Gene_expression_for_tissue-specific_analysis.xlsx>`_,
`Metadata information <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Sample_groups_for_tissue-specific_analysis.xlsx>`_.

.. image:: ../../_static/images/venn.png
        :width: 100%
        :align: center

Bubble Plot
------------------		
This tool provides a bubble plot, which shows gene expression specificity (indicated by dot size and color) among tissues.	
		
Users need to prepare three files, gene expression matrix, metadata information, and genes list.

**The gene expression matrix:** The first column is Geneid, other columns are data. The name of first column must be Geneid. Data from excel (format: xlsx).

**The metadata:** The first column is sample names, the second column is treatment conditions, and the third column is group names.
Colnames must be Samples, Names, and Groups. Data from excel (format: xlsx).

**The gene list:** The first column is Geneid. The name of first column must be Geneid. Data from excel (format: xlsx).

**Note:** The order of the sample names in both gene expression matrix and metadata information files must be consistent.

**Input example data:** `Gene expression matrix <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Gene_expression_for_tissue-specific_analysis.xlsx>`_,
`Metadata information <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Sample_groups_for_tissue-specific_analysis.xlsx>`_,
`Gene list <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Gene_list_for_tissue-specific_analysis.xlsx>`_.
		
.. image:: ../../_static/images/bubble.png
        :width: 100%
        :align: center



