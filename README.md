# GPT vs Claude - AI Chatbot Comparison

## Project Description

This project aims to compare the responses of two different AI language models, GPT and Claude, by observing the consistency and creativity of their answers. The user initially asks similar questions to both models, and then the responses from both models are continuously added to create a conversation scenario.

The project highlights the differences between GPT and Claude’s answers, exploring how each AI interacts in different styles.

## Technologies Used

- **GPT (OpenAI)**: A language model used to respond to text-based queries.
- **Claude (Anthropic)**: A language model similar to GPT but with a different approach and response structure.
- **Python**: The programming language used for coding and API integration.
- **API Clients**: Libraries used for communication with GPT and Claude.

## Project Structure

1. Initial messages are sent to both models (GPT and Claude) sequentially:
   - **GPT Initial Message**: "Hi there"
   - **Claude Initial Message**: "Hi"

2. As the process continues, responses from each model are processed:
   - **GPT Response**: `gpt_next = call_gpt()`
   - **Claude Response**: `claude_next = call_claude()`

3. The responses from both models are printed to the screen and added to a list sequentially.

4. A total of 5 interactive responses are collected.

## System Prompts

Each model works with customized system prompts that define its behavior style. These prompts determine the personality and communication approach of each model.

- **GPT System**:
  - The GPT model's goal is to argue and disagree with anything in the conversation. It expresses itself in a more rude and argumentative manner.

- **Claude System**:
  - The Claude model aims to be polite, courteous, and resolve disagreements. It tries to calm down the other person and always seeks to find common ground.

## How It Works

In the project, messages are sent to both models simultaneously, and the responses from each model are sequentially retrieved and displayed on the screen. This process is repeated to observe the style differences in the responses from both models.

## Expected Results

- The style differences, content creation, and language model performance between GPT and Claude will be observable.
- The project can be an entertaining tool for users who want to explore the different jokes, responses, and interaction styles of two different AIs.
- Additionally, the creativity and logical quality of the responses from both models can be evaluated.

## Future Developments

- **Add more language models**: Additional language models (e.g., Bard or other open-source models) can be incorporated into the project.
- **Performance analysis**: A comparison of response speed, accuracy, and content between the two models can be conducted.
- **User feedback**: Users could be given the opportunity to provide feedback on how satisfying the responses from each model are.
