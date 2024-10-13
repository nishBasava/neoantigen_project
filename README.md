NEO: Novel Epitope Optimizer

As cancer cases continue to rise, with a 2023 study from Zhejiang and Harvard predicting a 31% increase in cases and a 21% increase in deaths by 2030, the need to find more effective treatments for cancer is greater than ever before. Traditional approaches to treating cancer, such as chemotherapy, often kill healthy cells because of their lack of targetability. On the contrary, personalized cancer vaccines can utilize neoepitopes - distinctive peptides on cancer cells that are often missed by the body’s immune system - that have strong binding affinities to a patient’s MHC to provide a more targeted treatment approach. The selection of the perfect neoepitopes that elicit an immune response is a time-consuming and costly process because of the required inputs of modern predictive methods. This project aims to facilitate faster, cheaper, and more accurate neoepitope binding predictions with the use of Feed Forward Neural Networks and Recurrent Neural Networks. 
The neural networks were trained on data from whole-exome and RNA-sequencing data from 70 individuals with metastatic cancer with at least one human leukocyte antigen (HLA) class I-restricted epitope. The model requires next-generation sequencing data and utilizes the stacking ensemble method by calculating scores from state-of-the-art models (MHCFlurry1.6, NetMHCstabpan-1.0, and IEDB.) The model’s architecture includes an FFNN and an RNN with LSTM layers with memory to analyze both sequential and non-sequential data. Both model’s results are aggregated to produce predictions. Using this model, personalized cancer vaccines can be produced with improved results (0.9166 AUC, recall = 91.67%,).

