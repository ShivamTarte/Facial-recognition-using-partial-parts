# Facial-recognition
This capstone project and research paper focused on developing a facial recognition system that could accurately identify individuals even when only partial facial features, such as the nose, mouth, and eyes, were available. The primary objective was to overcome challenges faced in scenarios where the face was damaged due to accidents, captured by webcams, masked, or in any other situation where traditional face recognition methods might struggle.

To achieve this, three distinct models were created, each specializing in recognizing specific facial parts. The process began with face landmark detection, which accurately located the key points of the face. Subsequently, the face was cropped around the eyes, nose, and mouth regions, and specific filters and modifications were applied to enhance the extracted facial parts.

For the actual face recognition task, a convolutional neural network (CNN) with dropout regularization was employed. The Haar cascade model, known for its effectiveness in object detection, was utilized to locate the face in the image. The face landmark points provided the necessary guidance to separate and isolate the specific parts of the face. The CNN model was then trained on these facial parts to perform face recognition. The output of the model was a binary result, indicating whether the input faces were deemed similar or dissimilar.

Overall, this project aimed to address the challenges associated with partial face recognition by leveraging face landmark detection, region cropping, and a specialized CNN model. The combination of these techniques and models contributed to a robust facial recognition system capable of accurately identifying individuals, even when only specific parts of the face were visible.

Download any celebrity dataset
