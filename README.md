# ST449-project-2021

This is the repository for the course project. Please keep anything project related in this repository.

**Important dates**:
   * **Project proposal deadline**: 14th March, 5pm London UK time (fill in the information below by this date)
   * **First notification deadline**: 28th March, 5pm London UK time (approval of project topic or request for revision by this date)
   * **Project topic approval deadline**: 31st March, 5pm London UK time (all project topics must be approved by this date)
   * **Project solution submission deadline**: 30th April, 5pm London UK time

Your first task is the propose your project topic by filling the information requested below. 

You are encouraged to propose your course project topic as soon as possible but not later than by the project proposal deadline indicated above. We will try to process your project proposal and provide feedback as soon as possible. In any case, the first feedback from us will not be later than by the first notification deadline indicated above. All project topics must be approved by the project approval deadline indicated above -- the approval will be indicated in the feedback section below. 

You will receive feedback for your project topic proposal in the feedback section below of this Markdown file. A project topic proposal may be immediately approved or some revision may be required. The feedback should be limited to a few rounds of interactions (one or two) in order to deal with the workload. 

---

Please add the following information:

## Project title:

Comprehend Sentiments in Product Reviews (Natural Language Processing with Deep Learning)


## Summary:

**what is the problem you want to solve**:

Social distancing during the current pandemic has prompted consumers to buy products online. One of the important factors that help consumers judge quality of a product or service without being able to tangibly review the product is customer reviews. In addition, reviews also help product seller to get feedback from their customers.

I choose using Deep Learning to analyze sentiments of product reviews that can help product sellers and consumers to take focused approach on the reviews that matter to them. 

**why this is an interesting project**

1. Sentiment analysis can understand what customers like and dislike about the product.
2. Compare the product reviews with those of your competitors.
3. Get the latest product insights in real-time

**what methodologies you plan to apply**

1│ Data preparation
  * Clearing data
  * Data augmentation
 
2│ Data analysis and visualization, split data(Train, Valid, Test)

3│ Proposed Methodology
  * Long Short Term Memory (LSTM) Neural Network will be used at the core of the algorithm. 
  * In addition, PyTorch will be used to generate embedding of the tokenized text; specifically, torch.nn.Embedding module of the PyTorch framework will be used to generate embedding.
  In addition, the deep learning model using LSTM neural network will be developed using PyTorch framework as well.
 
5│Train the Model


  **The input** to the deep learning system will be product review comprised of product rating and text description of the review. 

  **The input** will be processed to generate embedding, which will be passed to Neural Network model. 

  **The output** will be rating in the range of 1-5 signifying score of the review.



**Datasets you plan to use**

  Dataset too big to upload so save in Google Drive.

**How you plan to evaluate your solution**

  Accuracy precision, recall, support, F1-sore 
 
 
## References:

[1] J. Blitzer, M. Dredze, F. Pereira, "Biographies, Bollywood, Boom-boxes and Blenders: Domain Adaptation for Sentiment Classification." Association of Computational Linguistics (ACL), 2007

[2] Predicting Amazon product reviews’ ratings https://towardsdatascience.com/predicting-sentiment-of-amazon-product-reviews-6370f466fa73

[3] S. Hochreiter, and J. Schmidhuber. "LONG SHORT-TERM MEMORY." Neural ComputationNovember 1997

[4] - Yoon Kim. 2014. Convolutional neural networks for sentence classification. In Proceedings of the 2014 Conference on Empirical Methods in Natural Language Processing (EMNLP). Association for Computational Linguistics, pages 1746–1751.

[5] - Aditya Joshi, Vaibhav Tripathi, Kevin Patel, Pushpak Bhattacharyya, and Mark Carman. 2016. Are word embedding-based features useful for sarcasm detection? In Proceedings of the 2016 Conference on Empirical Methods in Natural Language Processing. Association for Computational Linguistics, pages 1006–1011.

[6] T. Young, D. Hazarika, S. Poria and E. Cambria, "Recent Trends in Deep Learning Based Natural Language Processing [Review Article]," in IEEE Computational Intelligence Magazine, vol. 13, no. 3, pp. 55-75, Aug. 2018, doi: 10.1109/MCI.2018.2840738.

[7] Y. Wang, M. Huang, X. Zhu, and L. Zhao, “Attention-based LSTM for aspect-level sentiment classification,” in Proc. Conf. Empirical Methods Natural Language Processing, 2016, pp. 606–615.

[8] Y. Ma, H. Peng, and E. Cambria, “Targeted aspectbased sentiment analysis via embedding commonsense knowledge into an attentive LSTM,” in Proc. Association Advancement Artificial Intelligence Conf., 2018, pp. 5876–5883.

[9] D.S. Sachan, M. Zaheer, R. Salakhutdinov, "Revisiting LSTM Networks for Semi-Supervised Text Classifi- cation via Mixed Objective Function", arXiv: 2009.04007


---

## Feedback:

* [MV, 27 March 2021] Approved, but please note that you **must** use TensorFlow (not PyTorch)---TensorFlow is the software library we use in the course!


---


## Candidate project topics: 

Here you may find information about some candidate project topics: [Project.md](https://github.com/lse-st449/lectures2021/blob/master/Projects.md).

**Important**: You do not need to take a project topic listed in our list of suggestions -- you are encourged to come up with a project topic proposal of your own, which is not listed in our list.


## Marking criteria:

<img src="https://github.com/lse-st449/lectures2021/blob/main/images/ST449-final-coursework-rubric.png"></img>
 
