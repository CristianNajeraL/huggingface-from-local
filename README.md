# huggingface-from-local
Using Hugging Face model from local storage

The purpose of this repo is to show how to load a Hugging Face model from local storage
<br>
Steps:
<br>
* From your project folder download the model from Hugging Face git
  * git clone https://huggingface.co/t5-small
* Load the model into your code
  * tokenizer = AutoTokenizer.from_pretrained("./t5-small")
  * model = TFAutoModelForSeq2SeqLM.from_pretrained("./t5-small")
* Use it as you need it