To clone this repository open a terminal and run:

	git clone https://github.com/MBEgroupData/machine_learning.git

To set-up your coral device run the following commands:
	
	cd machine_learning
	bash setup.sh

Be sure to disconnect and reconnect your coral device if it was plugged in before running
the setup commands. 

To run a prediction on the coral device using the model in this repository run
the following commnad:

	python3 classify_image.py \
	--model reduced_object_model_edgetpu.tflite \
	--labels labels.txt \
	--input PATH_TO_FILE/FILE_NAME


For example replace PATH_TO_FILE/FILE_NAME with test_images/apple2.jpeg
to run the machine learning model on the apple2.jpeg image in the 
test_images folder of this repository. 
