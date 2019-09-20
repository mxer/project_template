## AutoMasterQA

##### project one for kaikeba senior nlp engineer course

##### the framework of this project is highly depend on the :  [pytorch-lightning](https://github.com/williamFalcon/pytorch-lightning) and the code is organized as [my own templete](https://github.com/tongjinle123/project_template)

Usage:
    
    train: inherit the base class of Model, Parser, Corpus and build the child classes.   
    Each module can build specific default config inplace.
    config child class name in main.py
    python main.py train --batch_size=32
    

Todo:

    add script for tracing the trained model
    add flask scripts for project presentation