# desk-object-sorter-ai

## Project Description
This project uses Googles teachable AI to identify a variety of objects that can be commonly found on a desk.
## Classes Identified
The objects my model was trained to identify:
Class 1: Water Bottle
Class 2: battery
Class 3: Playing Cards
Class 4: Remote

## Discussion & Reflection


1.  **Model Performance & Iteration:**
    * How accurate was your first trained model?
      My first trained model did a decent job at sorting the items but still got confused between similar objects.
    * What steps did you take to iterate and improve its performance?
      When it came to improving the performance of the model I took more training photos and emphasized more diversity and defining features for each item.
    * How did these changes affect the model's accuracy and confidence scores?
      After the second round of improving the training data, the model's accuracy and confidence was much more apparent with the given items after having the new photos to go off of.

2.  **Challenges & Observations:**
    * Which objects were the easiest for your model to learn and distinguish? Why do you think that was?
      The model had a very easy time when distinguishing the water bottle due to its sheer size as well as its clear handle.
    * Which objects were the most challenging? What made them difficult?
      The model had a hard time when distinguishing between the cards, battery, and the remote. The model had a tough time due to all 3 objects having similar square faced edges when presented flat.
    * What happened when you showed the model an object it wasn't trained on? How did the confidence scores behave, and why is this significant?
      The model tried its best to compare the untrained objects to pre-trained objects however it sorted it into whatever it best deemed fit.

3.  **Bias in AI:**
    * If you only trained your "mug" class with images of *your specific mug* (and didn't vary color, shape, etc.), how well do you think it would recognize other students' significantly different mugs? How does this illustrate the concept of bias being introduced through training data?
      For instance if someone were to show the model their water bottle there is a chance it would deem it as something else due to how different water bottles can be. The model is going to be more bias towards my half gallon bottle, however if you were to show it a 16.9 fl oz clear water bottle it might be less confident.
    * Imagine all your training images were taken in very bright, direct lighting. What might happen if you tried to use the model in a dimly lit room or with strong shadows? How does this relate to the robustness and potential biases of AI models?
      Lighting and clarity are both extremely important in this exercise, however giving the model more data to work with can help clear up and grey areas in the model's decision making.

4.  **Model Limitations & Usefulness:**
    * What are some key limitations of the model you created?
      The objects that it struggled with are a little concerning since many items on a desk have a darkish squared edge resulting in false sorting.
    * Why is it useful to be able to download your trained model files (like `model.json`, `weights.bin`) and share them (e.g., via GitHub)? What does this enable?
      This enables for anyone to edit and improve their own version of my model which can allow for a more accurate, and overall better model for everyone.

5.  **Real-World Applications & Ethics:**
    * Brainstorm 2-3 real-world applications where a similar image classification model could be useful.
      This can be useful in factories when deeming what is or isn't a defect. Such as legos,car parts, or car manufacturers.
    * Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world (e.g., related to fairness, privacy, misuse).
      It is important to note that you won't always have that "perfect lighting or perfect snapshot" of the given item that you're trying to recognize in the real world. So it's important to have a developer check the data and ensure that the recognition is accurate.

