# johnny-moonjarroh

Conversational engine app to query Peter Attia's The Drive podcast.

(todo) [screencast - "What does Peter think about cold sauna?]

- I used [Whisper](https://github.com/openai/whisper) `small.en` model to transcribe 200 podcast episodes available on YouTube. 
- Instructions for Pinecone & Langchain integration. (todo)
- Web deployment. (todo)

### Notes
Thanks to [Mckay Wrigley](https://github.com/mckaywrigley/wait-but-why-gpt) and [Lance Martin](https://lancemartin.notion.site/lancemartin/Lex-GPT-a3ad671766d34f4a9a078da7adf9d382) for sharing their work. This repo is inspired by their original work.

This app is not a substitute for the detailed and thougthful show notes that Peter and his team provide for each episode. Only a selected subset of publicly available episodes were transcribed.

Model sometimes misspells, understandably, Peter's surname (Atiyah/Atea/Atia etc. instead of Attia). All misspellings were manually corrected.

When using Georgi Gerganov's C/C++ implementation [whisper.cpp](https://github.com/ggerganov/whisper.cpp), model generates repetitive text for one of the episodes. This is a known issue (see [Whisper model card notes](https://github.com/openai/whisper/blob/main/model-card.md#performance-and-limitations)).

