# ChatGPT Text-to-Speech Integration

This project demonstrates the integration of OpenAI's ChatGPT API with text-to-speech capabilities using Python libraries such as `gtts` and `playsound`. It allows users to have interactive conversations with the ChatGPT model and converts the textual responses into spoken audio for a more engaging experience.

## Prerequisites

- Python 3.9.6
- OpenAI library (`openai`) - Install using `pip install openai`
- `gtts` library for text-to-speech conversion - Install using `pip install gtts`
- `playsound` library for audio playback - Install using `pip install playsound`

## Getting Started

1. Clone this repository: `git clone https://github.com/RishavJain21/RGPT.git`
2. Install the required dependencies
3. Obtain an OpenAI API key from the [OpenAI website](https://openai.com/docs/).
4. Update the `OPENAI_API_KEY` variable in the code with your OpenAI API key.
5. Run the code using the command: `python main.py`

## Usage

1. Upon running the code, you will be prompted to enter your message as a user.
2. The code will send your message to the ChatGPT model using the OpenAI API and receive a response.
3. The response will be printed as text and converted into spoken audio using text-to-speech conversion.
4. The audio will be played back using the `playsound` library.
5. The process repeats, allowing for a continuous conversation with the ChatGPT model.
6. To exit the program, press `Ctrl+C` or terminate the execution.

## Configuration

- `OPENAI_API_KEY`: Replace this variable with your actual OpenAI API key. It is necessary to authenticate your requests to the OpenAI API.

## Limitations

- The current code utilizes the `gpt-3.5-turbo` model, which incurs API costs based on usage. Please refer to the OpenAI pricing documentation for details on pricing.
- Ensure you have a stable internet connection to communicate with the OpenAI API.

## Acknowledgements

- This project was developed using the OpenAI GPT-3.5 model and the community-supported libraries `gtts` and `playsound`.
- Special thanks to the developers and contributors of these projects for their valuable work.
