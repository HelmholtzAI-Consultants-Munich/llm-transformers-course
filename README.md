# LLMs in Practice: Insights from User and Developer Perspectives. 
This repository contains slides and notebooks for a workshop on Transformers and Large Language Models (LLMs), covering both user and developer perspectives.

Learning objectives:

- Understand the strengths and limitations of LLMs, including practical tips and an overview of current regulations
- Get to know Blablador, Helmholtz’s in-house alternative to other LLM providers
- Discover transformers — the architecture and mechanisms behind powerful LLMs
- Learn how transformers can be applied in your research
- Learn how to fine-tune an LLM for a specific task

## Venue
The course will be fully online:
[Zoom link](https://us02web.zoom.us/j/83387526921?pwd=Uo7BBXz249kCzp2SlkyAg9ZMuYREDw.1)  
Meeting ID: 833 8752 6921  
Passcode: 615095

## Requirements and Setup
We strongly recommend launching the provided notebook with Google Colab in order to execute the code in a self-contained and verified working environment. In this case, no setup is required.

In case you wish not to use Google Colab, you can install and run the notebooks locally by following the guide below. 


#### Download the course content
```
git clone https://github.com/HelmholtzAI-Consultants-Munich/llm-transformers-course.git
```
Or enter the [repository](https://github.com/HelmholtzAI-Consultants-Munich/llm-transformers-course.git) and press `Code` -> `Download ZIP`

#### Create the virtual environment
Enter the directory you have downloaded:
```
cd llm-transformers-course
```
Create the virtual environment.
You can either use a virtual environment or a `conda` environment:
```
# virtual environment
python3 -m venv .venv
source .venv/bin/activate
```
```
# or conda
conda create -n llm_course python=3.13
conda activate llm_course
```
#### Then, follow jupyter notebook installation requirements [here](https://jupyter.org/install).

#### Finally, install the requirements of this workshop by running `pip install -r requirements.txt`.

#### Run the notebook with jupyter
```
jupyter notebook Transformer_finetuning_tutorial.ipynb
```
A browser window will open, navigate to the `.ipynb` file. Alternatively, you can open it with VSCode.

**Warning**: Newer versions of Python sometimes don't work with jupyter notebooks. If you encounter 404 errors when running the notebook, switch to Python 3.11.


## Schedule

<img width="612" height="660" alt="Screenshot 2026-03-20 at 09 58 00" src="https://github.com/user-attachments/assets/dbce65d3-7d8d-4313-beb0-6c84e9ed2ef6" />

## Mentors

- [Karol Szustakowski](mailto:karol.szustakowski@helmholtz-munich.de), Helmholtz Munich 
- [Donatella Cea](mailto:donatella.cea@helmholtz-munich.de), Helmholtz Munich
- Marcela Astrid, Helmholtz Munich
- Corrado Pancotti, Helmholtz Munich
- Leo Kaindl, Helmholtz Munich

## Requirements and Setup

It is possible to either create a local environment and install all the necessary packages (using the requirements.txt file), or to run the notebooks directly in the browser by clicking the **“Open in Colab”** button (**recommended**). This second option does not require any installation, but you will need access to a Google account.

*Add here info about, craete and env, requirement file, small test and how to clone the repo*

## Contributions

Comments and input are very welcome! If you have a suggestion or you think something should be changed, please open an issue or submit a pull request. 

## License

This project is licensed under the MIT License.
