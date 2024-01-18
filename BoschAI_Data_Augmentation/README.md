The augmented data is created using the below repository:

https://github.com/boschresearch/boschai-cnc-shared-task-ranlp2023/tree/master/augmented_data


Run the code:
python code/augment.py --input=data/output_cleaned_train_subtask2.txt --output=data/eda_3_output_cleaned_train_subtask2.txt --num_aug=1 --alpha_sr=0.4 --alpha_rd=0.0 --alpha_ri=0.5 --alpha_rs=0.0
