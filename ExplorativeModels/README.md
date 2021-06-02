<h3> EVERY FILE CAN BE OPENED WITH "OPEN IN COLAB" CHROME EXTENSION </h3>

<b> 0_Data_Preparation </b> is the file that contains the code to clean, prepare and split the dataset in train, validation and test sets.
The file contains all the code used to prepare the data: 
<ul>
  <li> Punctuation cleaning, </li>
  <li> Single strings conversion to lists of words, saved in new columns, </li>
  <li> Dropping of the little number of rows with no answer-context match, </li>
  <li> Splitting in Train (75%), Validation (15%) and Test (10%) sets according to titles along BERT's split, </li>
  <li> Sets' distribution generalisation, </li>
  <li> Saving the train and validation sets as pickle and test set as json files </li>
</ul>

<b> 1.0_ExplorativeModels_Glove </b> is the file that contains the code to train our first models, which exploit GloVe embeddings.
The file contains: 
<ul>
  <li> Loading train and validation sets from pickle files, </li>
  <li> Creating and saving vocabularies on the basis of lists of words from contexts and questions (answers are sublists of contexts) (NB adding a term for future test set's OOV terms) </li>
  <li> Encoding train (through generator) and validation sets as vocabulary' indexes, </li>
  <li> Defining a function to draw training graph and a function to handle training using TensorFlow callbacks, </li>
  <li> Creating the Embedding matrix for the Embedding in-model layer (NB adding a term for future test set's OOV terms),</li>
  <li> Building the different models with different structure and parameters, </li>
  <li> Code used to build, train and save the full model: </li> <ul>
        <li> different batch sizes, </li>
        <li> different learning rates, </li>
        <li> different attention types, </li>
  </ul>
  <li> The best is chosen according to the performance over the validation set's loss value. </li>
</ul>

<b> 1.1_LayersExperiments_Glove </b> is the file that contains the code to train some other models, which also exploit GloVe embeddings.
The file contains: 
<ul>
  
</ul>

<b> 2_ExplorativeModels_Word2Vec </b> is the file that contains the code to train other models, which exploit Word2Vec embeddings.
The file contains: 
<ul>
  
</ul>

<b> 3_ExplorativeModels_TrainableEmbeddings </b> is the file that contains the code to train other models, which also have a trainable embedding layer.
The file contains: 
<ul>
  
</ul>

<b> 4_MakingPredictions </b> is the file that contains the code to make prediction and evaluate the model.
The file contains: 
<ul>
  <li>All the code used to prepare the evaluation data, including the encoding using the Vocabularies</li>
  <li> Loading the best models' weights and making them predicting the answers for the evaluation data</li>
  <li> Evaluation of the models' results through our professor's evaluation file</li>
</ul>
