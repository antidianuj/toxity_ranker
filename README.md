# toxity_ranker

First the dataset for learning embeddings of the textual data in "toxity_data.csv" is created from "create_dataset".

Second, the embedddings of the text are learned from "transfer_learning_text" in a transfer learned manner.

Lastly, the LightGBM ranking model is fitted on these embedding features, with output ranks as thresholding of toxity type vector.
