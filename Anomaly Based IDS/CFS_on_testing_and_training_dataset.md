# CFS subset on Traning and Testing dataset
We have used Forward Sequence Selection for CFS. In this, an empty set is taken and rest of the features are inserted one by one.

Stopping criteria is set as 5, i.e., search will terminate if 5 consecutive subsets show no improvement over the current best subset. 

### Steps

(1) First we open WEKA tools Explorer.<br />
(2) Under 'Preprocess' tab, we select our training dataset.<br />
(3) Go to 'Select attributes' tab. In 'Attribute Evaluator' choose  'CfsSubsetEval'. Let the default settings be as it is.<br />
(4) In 'Search Method', choose 'BestFirst'.<br />
(5) 'Attribute Selection Mode' should be checked on 'Use full training set'.<br />
(6) Now press on 'Start'.<br />
(7) Whatever features come as 'Selected Attributes', remove them from the dataset.<br />
(8) Do the same for testing dataset.
