# NLP-Project-4

Instructions:

corpus/wmt15engfre.csv contains the human ranking for each sentence of the dataset, and for each pair of systems.

corpus/MT_systems_outputs contains the translations done by 7 Automatic Machine Translation services in .txt files (one per system), and corpus/ref_translations contains a .txt file that contains the reference translations.

The scores are computed using part I. and II. of the .ipynb "Evaluation metrics NLP" file. Simply use the wmt15engfre.csv file in the "corpus" folder, and the .txt files in the corpus/MT_systems_outputs and corpus/ref_translations folders.
Score computation can be avoided by directly using part III. of the notebook, along with the files in the "corpus/scores" folder and wmt15engfre.csv. Boxplots are then obtained in a few seconds.
