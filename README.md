# agStudio
Autogen Studio Test

> ### Setup a virtual environment
> #### Option a: venv
> You can create a virtual environment with venv as below:
>
>      $ python3 -m venv agStudio
>      $ source agStudio/bin/activate

> The following command will deactivate the current venv environment:
>
>      $ deactivate
>
> #### Option b: conda
> Another option is with Conda. You can install it by following this doc, and then create a virtual environment as below:
>
>      $ conda create -n agStudio python=3.10  # python 3.10 is recommended as it's stable and not too old
>      $ conda activate agStudio
>
> The following command will deactivate the current conda environment:
>
>      $ conda deactivate
>
### Create a conda env

      $ conda create -n agStudio python=3.11

### Activate conda env

      $ conda activate agStudio

## pip install
      $ pip install autogenstudio


## export Open AI key
      $ export OPENAI_API_KEY={KEY}

 ## set port
       $ autogenstudio ui --port 8081


# LOCAL SETUP
## Ollama and liteLLM
[Ollama](https://ollama.ai/)
[LiteLLM](https://github.com/BerriAI/litellm)
