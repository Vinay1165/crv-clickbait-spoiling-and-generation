1. Open the either ./Milestone2/Baseline.ipynb or ./Milestone3/Final.ipynb

2. Run the Environment section
	 	
	a. You can set the model by change the model_name variable. You can find the list of the model in the corresponding notebook.
	
	
	b. You can the the type_of_data to 'phrase' or 'passage' to choose which kind the spilor you want to generate.	

3. Run the Data Preprocessing section


	a. There are two line that get the train.jsonl and validation.jsonl directory path.Please set the right Path.
  
4. Run the tokenization section

6. Run the training section(take lots of time)


	a. If you don't want to trained the model, you can jump to step 6.
	
	
	b. You can save your trained model to your own path by setting variable output_dir.
	
	
	c. For milestone 3, if you want to train
	
	
		-bert model, set the 'model' variable equal to 
		
		
			BertForQuestionAnswering.from_pretrained(model_name).to(device)
			
			
		-Deberta model, set the 'model' variable equal to 
		
		
			DebertaForQuestionAnswering.from_pretrained(model_name).to(device)
			
			
		-Roberta model, set the 'model' variable equal to 
		
		
			RobertaForQuestionAnswering.from_pretrained(model_name).to(device)
			
			
			
6. Run the evaluation section


	a. Set the model_dir to your trained model.
	

	b. For milestone 3, as same as above, set the 'model' variable equal to the corresponding one
	
