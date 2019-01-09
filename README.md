This is a project done in the summers trying to build a chat-bot of my own.
The dataset used for training the chatbot was a reddit comment dump. The folder data set creator contains 2 scripts namely:

## 1.datasetcreator.py:
      This script opens our comment dumps which is stored in json format and convert it to a sql database which will be used for creating       our FROM and TO Files which will be used for training the model.
     
## 2.conversation_creator.py:
      This script goes to through our database created in the previous step and based on the common post id links comments to there parent       post in such a way that Parent post goes to the FROM file and comments to the post will go the TO file. After the end of execution       of this script, we will get a FROM and TO file which is used for training chatbot.
   
### Training the model:
     
     
