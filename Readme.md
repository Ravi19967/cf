### Sample Request
`curl --header "Content-Type: application/json" -d @cf/sample.json -X POST http://localhost:8501/v1/models/image_classification:predict`

### Requirements
* Docker
* ShellScript

### Instructions
* Clone the repo to your root directory
* Run `model_training.sh`
* Go to the jupyter notebook link in the output and run the notebook
* Go to `http://localhost:6006/` after execution of notebook for tensorboard visuals
* Run `model_serving.sh`
* Run the Sample reuqest for results

### Pending
* Version controlling of the ML Models
* Running jupyter notebook instead of script. Used jupyter here for better visibility of code
* Parameter Store of sorts to automatically update the variables
* Logging of results and tracebacks in case of failures