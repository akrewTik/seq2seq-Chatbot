# seq2seq-Chatbot

cd /media/deeplearning/data/
source activate venv
python train.py --datasetdir=datasets/csv
python train.py --datasetdir=datasets/cornell_movie_dialog

python train.py --checkpointfile=models\dataset_name\model_name\checkpoint.ckpt


python chat.py models/csv/20181120_015151/best_weights_training.ckpt
python chat.py models/csv/20181120_081615/best_weights_training.ckpt


