Provide an example of where the bear classification model might work poorly in production, due to structural or style differences in the training data.
Where do text models currently have a major deficiency?
- Text models have a major deficiency in generated factually correct reponses. These models are good at creating compelling answers, but have difficulty combining with a knowledge base to give the right answers.
What are possible negative societal implications of text generation models?
- Contextually appropriate compelling comments on social media could be used to spread misinformation on social media at a massice scale. Models that detect AI generated content will also always be slightly behind generative AI models. 
In situations where a model might make mistakes, and those mistakes could be harmful, what is a good alternative to automating a process?
- Models should be used in a way that deep learning and humans interact closely. Models should make predictions that support humans, such as detecting potential stroke victims from CT scans and sending an alert to review the scan with high priority. 
What kind of tabular data is deep learning particularly good at?
- It's good at high-cardinality categorical columns and columns containing natural language. 
What's a key downside of directly using a deep learning model for recommendation systems?
- It might just recommend extremely similar products to what the user already purchased, such that it can even be just different packaging of the same product. 
What are the steps of the Drivetrain Approach?
- Define an objective
- Think about actions that you can take to meet the object
- What data do you have or can acquire that can help
- build a model to determine the best actions to achieve the objective
How do the steps of the Drivetrain Approach map to a recommendation system?
- the objective is to drive additional sales by recommending the right product
- the lever is the ranking of recommendations
- collect new data, like by conducting randomized experiments that collect data on recommendations across customers
- then you could make two models, for the purcharse probabilities with and without a recommendation, and the difference will be the utility fn
Create an image recognition model using data you curate, and deploy it on the web.
What is DataLoaders?
What four things do we need to tell fastai to create DataLoaders?
What does the splitter parameter to DataBlock do?
How do we ensure a random split always gives the same validation set?
What letters are often used to signify the independent and dependent variables?
What's the difference between the crop, pad, and squish resize approaches? When might you choose one over the others?
What is data augmentation? Why is it needed?
What is the difference between item_tfms and batch_tfms?
What is a confusion matrix?
What does export save?
What is it called when we use a model for getting predictions, instead of training?
What are IPython widgets?
When might you want to use CPU for deployment? When might GPU be better?
What are the downsides of deploying your app to a server, instead of to a client (or edge) device such as a phone or PC?
What are three examples of problems that could occur when rolling out a bear warning system in practice?
What is "out-of-domain data"?
What is "domain shift"?
What are the three steps in the deployment process?