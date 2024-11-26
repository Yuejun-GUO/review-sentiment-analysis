# review-sentiment-analysis

This project evaluates the performance of different ML models for sentiment analysis.

### Dataset

[amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews) and [amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews) are two public datasets on Hugging Face for sentiment analysis. Both datasets include user product reviews on Amazon.

| 	Dataset	 | 	#train	 | 	#test	  | 
|:---------:|:--------:|:--------:| 
| 	[amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews)	  | 	90,000	 | 	10,000	 | 
| 	[amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews)	  | 	86,932	 | 	9,660	  |


### Models

* training: fine-tune pre-trained using the training set from a given dataset
* testing: on the test set

### Models performance (accuracy)

- The models are trained using [amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews)

|                                      	Model	                                      | 	[amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews)	 | 	[amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews)	 | 
|:---------------------------------------------------------------------------------:|:--------:|:---------------------------------------------------------------------------------------------------:| 
|   [gte-base-en-v1.5](https://huggingface.co/Alibaba-NLP/gte-base-en-v1.5)    		   | 		 |                                                 		                                                  | 
|   [bge-base-en-v1.5](https://huggingface.co/BAAI/bge-base-en-v1.5)    		       | 		 |                                                 		                                                  |
|  [bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)    		  | 		 |                                                 		                                                  |
|  [e5-base-v2](https://huggingface.co/intfloat/e5-base-v2)    		  | 		 |                                                 		                                                  |


-  The models are trained using [amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews)

|                                      	Model	                                      | 	[amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews)	 | 	[amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews)	 | 
|:---------------------------------------------------------------------------------:|:--------:|:---------------------------------------------------------------------------------------------------:| 
|   [gte-base-en-v1.5](https://huggingface.co/Alibaba-NLP/gte-base-en-v1.5)    		   | 		 |                                                 		                                                  | 
|   [bge-base-en-v1.5](https://huggingface.co/BAAI/bge-base-en-v1.5)    		       | 		 |                                                 		                                                  |
|  [bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)    		  | 		 |                                                 		                                                  |
|  [e5-base-v2](https://huggingface.co/intfloat/e5-base-v2)    		  | 		 |                                                 		                                                  |