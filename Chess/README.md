Business needs

    The organization is looking for a solution to predict winner in chess match.
    
Requirements

    python 3.7

    numpy==1.17.3
    pandas==1.1.5
    sklearn==1.0.0

Running:

    To run the demo, execute:
        python predict.py 

    After running the script in that folder will be generated <prediction_results.csv> 
    The file has 'winner_pred' column with the result value.

    The input is expected  csv file in the same folder with a name <games.csv>. The file shoul have all features columns. 

Training a Model:

    Before you run the training script for the first time, you will need to create dataset. The file <train.csv> should contain all features columns and target for prediction Winner.
    After running the script train_model.ipynb  "finalized_model.sav" will be created.
    Run the training script:
        python train.py

    The model accuracy is 99%.
    There is no fraud check.