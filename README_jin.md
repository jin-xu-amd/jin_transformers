=============
run command:
=============
run_mlm.py  --model_name_or_path bert-large-uncased --dataset_name wikitext --dataset_config_name wikitext-2-raw-v1 --do_train --max_steps 50 --logging_steps 1 --output_dir out_test --overwrite_output_dir --per_device_train_batch_size 8  --max_seq_length=384 --do_eval  --fp16 --skip_memory_metrics=True

=============
output trace*.json 
will be saved in /tmp/ directory
