To set-up your coral device run the following command:

bash setup.sh

Be sure to disconnect and reconnect your coral device if it was plugged in before running
the setup command. 

To run a prediction on the coral device using the model in this repository run:

python3 calssify_image.py \
--model reduce_object_model_edgetpu.tflite \
--labels labels.txt \
--input test_images\FILE_NAME 
