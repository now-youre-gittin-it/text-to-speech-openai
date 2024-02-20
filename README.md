Create AI-generated audio based on given input text.

### Key advantage 
The audio O/P is of superior quality compared to generic TTS (text-to-speech) engines that may stumble over multi-lingual tokens in a given text and may not incorporate suitable voice modulations depending on the tone of the text.

### Approach 

Using tts-model-1 of Open AI's Audio API.

A request to the API includees 3 inputs:
1. Model name (tts-model-1, which follows the Whisper speech recognition model developed by OpenAI)
2. Voice (one of six preexisting AI-generated voice options)
3. Input (text that needs to be converted to speech. E.g. new article/book excerpt)

The API output is an MP3 file that gets locally stored in the specified system path.
