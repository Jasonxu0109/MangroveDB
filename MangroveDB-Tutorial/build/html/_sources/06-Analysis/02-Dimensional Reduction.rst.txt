==========================
Dimensional Reduction
==========================

This tool provides insights into the association between samples, and check whether biological replicates have a similar expression profile and tend to cluster together. 
Dimension reduction of gene expression is performed using three methods, such as Principal Components Analysis (PCA), Uniform Manifold Approximation and Projection (UMAP),
and T-distributed Stochastic Neighbor Embedding (tSNE).
	
Read before use
------------------	
Users need to prepare two files, gene expression matrix and metadata information.

**The gene expression matrix:** The first column is Geneid, other columns are data. The name of first column must be Geneid. Data from excel (format: xlsx).

**The metadata:** The first column is sample names, the second column is treatment conditions, and the third column is group names.
Colnames must be Samples, Names, and Groups. Data from excel (format: xlsx).

**Note:** The order of the sample names in both files must be consistent.

**Input example data:** `Gene expression matrix <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Gene_expression_for_dimension_reduction.xlsx>`_,
`Metadata information <https://github.com/Jasonxu0109/MangroveDB/releases/download/Example/Sample_groups_for_dimension_reduction.xlsx>`_.

.. image:: ../../_static/images/DR.png
        :width: 100%
        :align: center
