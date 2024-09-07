# Parameter Efficient Fine Tuning Techniques Analysis
* In this repo I've explored the usage of LORA and Prompt Tuning techniques from the PEFT library to fine tune LLAMA 2 7B on summarization task
* For LORA we are finetuning all linear layers
* Instead of prompt tuning we could also use p-tuning or prefix tuning in PEFT
* For both tasks, we can see improvements after just fine tuning on a small number of steps
* To reproduce the results please specify your Hugging Face Access Token in the notebook
