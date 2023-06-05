# ccs_project

This repo contains code used for the 2023 exam in Computational Cognitive Science 2 for MSc programme in IT & Cognition at the University of Copenhagen. The code was used to perform sentiment analysis on comments collected from Facebook.

Group members: Sophia Conrad (mbv834), Katrine Kjørup (dqx858) and Johannes Hermann Palbøl (pvs829).

## Models folder

This is the most important folder for our project. It contains files showing how we trained our different models:

- emojis-only: This model was trained on comments only containing emojis. The Jupyter notebook contains the code used and the csv file contains the data used.
- text-only: This model was trained on comments only containing text. The Jupyter notebook contains the code used and the csv file contains the data used.
- text+emojis: This model was trained on comments containing both text and emojis. The Jupyter notebook contains the code used and the csv file contains the data used.
- text+emojis+reactions: This model was trained on Facebook reactions and comments with text and emojis. The Jupyter notebook contains the code used and the csv file contains the data used.

## helper_scripts

This folder contains a few notebooks that were used for cleaning our data.
