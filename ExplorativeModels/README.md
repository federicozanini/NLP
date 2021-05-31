<h3> BOTH FILE CAN BE OPENED WITH "OPEN IN COLAB" CHROME EXTENSION </h3>




<b> BiDAF_Training </b> is the file that contains the code to train the model. 
The file contains: 
<ul>
  <li>All the code used to prepare the training data, including Glove loading for embedding, Vocabulary class for the extraction a char vocabulary, Sequence subclass ( to feed the training with a generator )</li>
  <li>All custom layer used to create paper-like bidaf model</li>
  <li>Code used to build, train and save the full model</li>
</ul>



<b> BiDAF_Prediction </b> is the file that contains the code to make prediction and evaluate the model. =
The file contains: 
<ul>
  <li>All the code used to prepare the evaluation data, including Glove loading and Vocabulary class for embedding</li>
  <li>All custom layer used to load paper-like bidaf model</li>
  <li>Code used to evaluate the full model</li>
</ul>
