# ASL Project
This project is an Arabic lemmatization model called ASL, which lemmatizes words with NMT sequential model on character level.
## Files contained in the project:
###Data.json
The dataset file which was collected from open-source Arabic corpus down below, the data was processed and clean multiple times before use, for future use give a reference for this project when use.
Old-Data:
```
https://lindat.mff.cuni.cz/repository/xmlui/handle/11858/00-097C-0000-0001-4872-3#
http://aracorpus.e3rab.com/ 
```
###Model_trainer.ipynb
Open-source python code for ASL model training, the code is self-explaining.
###Model_tester.ipynb
Open-source python code to use ASL model, you can use the pretrained model in "Models" folder, or train your model and use it, the code is also self-explaining.
###Models
The pretrained model, with all needed files including needed text lists and Tokenizer for model encoder & decoder
