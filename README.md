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
Create the virtual environment. The course needs **Python 3.12 or newer**.
You can either use a virtual environment or a `conda` environment:
```
# virtual environment
python3.12 -m venv .venv
source .venv/bin/activate
```
```
# or conda
conda create -n llm_course python=3.12
conda activate llm_course
```
#### Install the requirements of this workshop by running `pip install -r requirements.txt`.
This includes Jupyter, so no separate installation is needed.

#### Check the installation
Open `verify_install.ipynb` and run it. It prints which Python your kernel is using and imports the packages the notebooks need, so you can confirm the setup before the course starts.

#### Run the notebook with jupyter
```
jupyter notebook Transformer_finetuning_tutorial.ipynb
```
A browser window will open, navigate to the `.ipynb` file. Alternatively, you can open it with VSCode.


## Solutions
Notebook solutions are now available. Please see the solutions notebook for solutions to the exercises.


## Schedule

<img width="612" height="660" alt="Screenshot 2026-03-20 at 09 58 00" src="https://github.com/user-attachments/assets/dbce65d3-7d8d-4313-beb0-6c84e9ed2ef6" />

## Mentors

- [Karol Szustakowski](mailto:karol.szustakowski@helmholtz-munich.de), Helmholtz Munich 
- [Donatella Cea](mailto:donatella.cea@helmholtz-munich.de), Helmholtz Munich
- Marcela Astrid, Helmholtz Munich
- Corrado Pancotti, Helmholtz Munich
- Leo Kaindl, Helmholtz Munich

## Contributions

Comments and input are very welcome! If you have a suggestion or you think something should be changed, please open an issue or submit a pull request. 

## License

This repository contains both source code and teaching materials, which are licensed separately:

- **Code** (notebooks, scripts, and other software) is licensed under the MIT License. See the `LICENSE` file.
- **Teaching materials** (slides, figures, and written explanations) are licensed under the Creative Commons Attribution 4.0 License. See the `LICENSE-CONTENT` file.

[https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
