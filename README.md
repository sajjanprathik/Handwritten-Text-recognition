
# Handwritten Text Recognition




## AIM
Handwritten Text Recognition (HTR) system implemented with TensorFlow (TF) and trained on the IAM off-line HTR dataset. The model takes images of single words or text lines (multiple words) as input and outputs the recognized text. 3/4 of the words from the validation-set are correctly recognized, and the character.



    
## Command line arguments
- --mode: select between "train", "validate" and "infer". Defaults to "infer".
- --batch_size: batch size.
- --data_dir: directory containing IAM dataset (with subdirectories img and gt).
- --fast: use LMDB to load images faster.
- --line_mode: train reading text lines instead of single words.
- --img_file: image that is used for inference.
- --dump: dumps the output of the NN to CSV file(s) saved in the dump folder. Can be used as input for the CTCDecoder.
## python libraries
- matplotlib==3.2.1
- numpy==1.19.5
- argparse
- opencv-python==4.4.0.46
- path==15.0.0
- tensorflow==2.4.0
## References

 - [Build a Handwritten Text Recognition System using TensorFlow](https://towardsdatascience.com/build-a-handwritten-text-recognition-system-using-tensorflow-2326a3487cd5)
 - [handwritten character recognition using Deep-Learning](https://drive.google.com/file/d/1uuJKOctH5TFTd6-zzjZ8akQNfkbmHmkm/view?usp=sharing)
