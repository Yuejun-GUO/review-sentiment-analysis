# review-sentiment-analysis

This project evaluates the performance of different ML models for sentiment analysis.

### Dataset

[amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews) and [amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews) are two public datasets on Hugging Face for sentiment analysis. Both datasets include user product reviews on Amazon.

| 	Dataset	 | 	#train	 | 	#test	  | 
|:---------:|:--------:|:--------:| 
| 	[amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews)	  | 	90,000	 | 	10,000	 | 
| 	[amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews)	  | 	86,932	 | 	9,660	  |


### Model performance (accuracy)

The models are fine-tuned using [amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews) on pretrained models.

|                                      	Model	                                      | 	[amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews)	 | 	[amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews)	 | 
|:---------------------------------------------------------------------------------:|:--------:|:---------------------------------------------------------------------------------------------------:| 
|   [gte-base-en-v1.5](https://huggingface.co/Alibaba-NLP/gte-base-en-v1.5)    		   | 		 |                                                 		                                                  | 
|   [bge-base-en-v1.5](https://huggingface.co/BAAI/bge-base-en-v1.5)    		       | 		 |                                                 		                                                  |
|  [bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)    		  | 		 |                                                 		                                                  |
|  [e5-base-v2](https://huggingface.co/intfloat/e5-base-v2)    		  | 		 |                                                 		                                                  |


The models are fine-tuned using [amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews) on pretrained models.

|                                      	Model	                                      | 	[amazon-shoe-reviews](https://huggingface.co/datasets/gyoungjr/amazon-shoe-reviews)	 | 	[amazon-electronics-reviews](https://huggingface.co/datasets/gyoungjr/amazon-electronics-reviews)	 | 
|:---------------------------------------------------------------------------------:|:--------:|:---------------------------------------------------------------------------------------------------:| 
|   [gte-base-en-v1.5](https://huggingface.co/Alibaba-NLP/gte-base-en-v1.5)    		   | 		 |                                                 		                                                  | 
|   [bge-base-en-v1.5](https://huggingface.co/BAAI/bge-base-en-v1.5)    		       | 		 |                                                 		                                                  |
|  [bert-base-uncased](https://huggingface.co/google-bert/bert-base-uncased)    		  | 		 |                                                 		                                                  |
|  [e5-base-v2](https://huggingface.co/intfloat/e5-base-v2)    		  | 		 |                                                 		                                                  |