# MPRF
**Code for all Dataset except FL:** https://mailmissouri-my.sharepoint.com/:u:/r/personal/mrpk9_umsystem_edu/Documents/Reserach%20Synch/motion-feature.zip?csf=1&web=1&e=TFxqV9

**Code for FL:** Code for NPS and MVAAOD with weights: https://mailmissouri-my.sharepoint.com/:u:/r/personal/mrpk9_umsystem_edu/Documents/Reserach%20Synch/motion-feature.zip?csf=1&web=1&e=TFxqV9

**Weight:** https://mailmissouri-my.sharepoint.com/:u:/g/personal/mrpk9_umsystem_edu/EffR4lEXePZPo-d3mXtcoQMBmvEZKtDDhbP-pvxGEvXwyw?e=4ee1b1
 
**Test:** python val.py --data <path_to_dataset_config> \
--weights <path_to_weights_file> \
--batch-size <batch_size> --img <image_size> --num-frames <number_of_frames> \
--project <path_to_project_directory> --name <run_name> \
--task <task_type> --exist-ok --save-json-gt

**Train:** python train.py --img <image_size> --adam --batch <batch_size> --epochs <num_epochs> --data <path_to_dataset_config> \
--weights <path_to_weights_file> --hy <path_to_hyperparameters_file> --cfg <path_to_model_config_file> \
--project <path_to_project_directory> --name <run_name> --exist-ok

