# BertQA

This is a working repo for the Kaggle Tensor 2.0 Question Answering Kaggle competition. Before being recurited by the project leader for a Portland based data science team wanting to compete in this competition I had not entered a Kaggle competition before. My kaggle account is https://www.kaggle.com/howardgoff.

**_12/06/19_** - The team met to discuss the competition, how to organize work on the project and explore the data. A decision was made to explore Google Colab as an alternative platform for development rather than using the default Kaggle platform. Because of my experience in development operations I agreed to explore Colab and figure out how to interface it with Kaggle. My initial attempts at this can be seen in ColabGettingStarted.ipnyb

**_12/13/19_** Created initial Notebooks at Colab and created functionality to establish an SSH shell connection to the colab with the vim editor available if team members wanted to use it (default Colab does not inclue functionality to log into the virtual machine). The note Notebook imports data using the Kaggle API. Kaggle and Colab use different directory structures for input and output data so I implemented a directory abstraction so the same Notebook could be made to run in both locations.<br>
I am currently converting the https://www.kaggle.com/abhinand05/bert-for-humans-tutorial-baseline to run on google Colab as BERT_for_Humans_Baseline.ipynb. <em>(Score was 0.15)</em>

**_12/19/19_** Was able to the abhinand05 Notebook fork to run on Kaggle and made an initial submission to the competition so our team would qualify for a Google TPU credit that is being provided to competitors. The abhinand05 is still not running successfully on Colab.<br>
Switched to an updated Kaggle notebook (https://www.kaggle.com/prokaj/bert-joint-baseline-notebook/notebook) and with a few modifications ran that to completion on Colab as BERTjoint_yes_no_Howard.ipynb. This notebook was successfully copied to Kaggle and submitted. https://www.kaggle.com/howardgoff/bertjoint-yes-no <em>(score was 0.57 and current place on leaderboard is 208 out of 918)</em>.<br>
This demonstrates that our team has a solid configuration to develop on Colab and submit on Kaggle.<p>
I merged the changes from Bertjoint_yes_no_Howard.ipynb back to ColabGettingStarted.ipnyb so they would be available as a starting point for future notebooks.

**_01/04/20_** Just met with team to review progress. We have been working individually and the decision was made today to combine into a single team so we can share work and code without making it public. My competition submission last night scored 0.60 and am currently placed 76 out of 1074 on the leaderboard!<p>
I have spent the last two weeks working on understanding how data is organized and flows through the program as well as how the baseline model works. I have spent a lot of time looking at more as well as looking at code published by different competitors.<br>
My Colab and Google Drive setup are further refined. Each project and notebook now has separate and persistent versions of library and output files. (see https://github.com/hogo56/BertQA/blob/master/ColabGettingStarted.ipynb). Also added a couple of packages to the SSH code to make the virtual machines more useful to me.
