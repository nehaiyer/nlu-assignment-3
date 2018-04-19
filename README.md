# nlu-assignment-3


Model file: seq_label_model_3
Input files: train.txt, dev.txt, test.txt
Tagged output file generated on test.txt: tagged_test_output.txt
Config file: config.conf

Required Packages:
  Theano v0.7
  lasagne v0.1

Following command was used to train the model:
  python sequence_labeling_experiment.py config.conf

Following command prints the tagged output on test file:
  python print_output.py labels seq_label_model_3 test.txt
