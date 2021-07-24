# Evolv-fit
This repository consist of 2 models
1) yoga pose estimation:
  I have used opencv to identify the yoga pose from image. Through this model we can observe the body points and pair points generated for each pose.
2) Random Forest Classifier:
  In this model the images are first scattered using CNN then a complete model is prepared using RandomForestClassifier.
  Random forest classifier creates a set of decision trees from randomly selected subset of training set. It then aggregates the votes from different decision trees to decide the final class of the test object.
  Size of traning dataset is 920 files and that of test data is 470 files. The dataset consist of 5 classes: downdog, goddess, plank, tree, warrior.
  As we can see size of traning dataset is small. Random forest can give good accuracy in small dataset.
