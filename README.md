# HeartEye
Heart Risk Prediction using Retinal Eye Image

This project demonstrates how retinal vessel analysis can be used for
heart disease risk prediction. By extracting vessel area, thickness, and densityfrom
retinal images and training a RandomForestClassifier, the system was able to
predict cardiovascular risk with high accuracy and precision.

retinal image datasets that include annotated vessel features and
corresponding health records. These images undergo preprocessing to enhance
vessel visibility, including techniques such as histogram equalization and Gaussian
blurring. After preprocessing, Canny edge detection is applied toidentifytheedges
of the blood vessels in the retinal images. Algorithms are then developed to
calculate various vessel features, including vessel area, average vessel thickness,
thickest vessel diameter, vessel density, and aspect ratio. These features areusedto
train a RandomForestClassifier model, which is employed to classify the risk of
heart disease based on the extracted vessel characteristics. The trained model is
tested on a separate set of images to predict heart disease risk, classifying each
retinal image as either high or low risk. The results are visualized by overlaying
detected vessel edges on the original images and displaying the corresponding risk
classifications. Performance metrics such as accuracy, precision, recall, F1-score,
and precision-recall curves are generated to evaluate the model. Finally, thetrained
machine learning model is saved for futureuseinpredictingheartdiseaseriskfrom
retinalimages.
