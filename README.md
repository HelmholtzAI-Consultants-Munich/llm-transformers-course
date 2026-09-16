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
[Zoom link](https://zoom.us/j/98382888189?pwd=gI0mQoxXOYT5OYSnbdpB7bD38WTeNb.1)  
Meeting ID: 983 8288 8189  
Passcode: 272044

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


## Schedule

The course runs over two half-days.

### Day 1

| Time | Session | Duration |
|---|---|---|
| 09:00 - 09:15 | Welcome | 15 min |
| 09:15 - 10:45 | Introduction to Language Modeling | 1 h 30 min |
| 10:45 - 11:00 | Break | 15 min |
| 11:00 - 12:00 | Blablador: concept, models description. Optional: integration in VS Code | 1 h |
| 12:00 - 12:30 | Q&A | 30 min |

### Day 2

| Time | Session | Duration |
|---|---|---|
| 09:00 - 09:15 | Welcome | 15 min |
| 09:15 - 10:15 | Attention, self-attention, transformer architecture | 1 h |
| 10:15 - 10:30 | Break | 15 min |
| 10:30 - 10:45 | Pre-training vs fine-tuning and foundation models (introduction for the hands-on session) | 15 min |
| 10:45 - 12:15 | Hands-on: fine-tune a model on a downstream task (in breakout rooms) | 1 h 30 min |
| 12:15 - 12:30 | Q&A, wrap-up and conclusion | 15 min |

## Mentors

- [Karol Szustakowski](mailto:karol.szustakowski@helmholtz-munich.de), Helmholtz Munich 
- [Donatella Cea](mailto:donatella.cea@helmholtz-munich.de), Helmholtz Munich
- Marcela Astrid, Helmholtz Munich

## Contributions

Comments and input are very welcome! If you have a suggestion or you think something should be changed, please open an issue or submit a pull request. 

## License

This repository contains both source code and teaching materials, which are licensed separately:

- **Code** (notebooks, scripts, and other software) is licensed under the MIT License. See the `LICENSE` file.
- **Teaching materials** (slides, figures, and written explanations) are licensed under the Creative Commons Attribution 4.0 License. See the `LICENSE-CONTENT` file.

[https://creativecommons.org/licenses/by/4.0/](https://creativecommons.org/licenses/by/4.0/)
