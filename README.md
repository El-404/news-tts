# news-tts

## Project goal
- Create a way for busy people to stay somewhat connected with the news.

## Scope
- A single command that reads a json file from Media Bias.

## Version 2 prospective
- Json parser/extractor
- Links to articles
- User prompts

## Tech stack
- Bash/scripting
- Media bias news api
- curl and file redirection
- json files (raw data from media bias)
- tts engine (likely espeak-ng)


# Usage

    ./readNews.sh # reads data from based on the default subject
Change the default subject by creating an environment variable

    export DEAFULT_NEWS_SUBJECT = # WIP

## Flags

    ./readNews.sh -s # WIP
Reads data relating to the subject # WIP

| flag         | long                | description                                 |
|--------------|---------------------|---------------------------------------------|
| -s [subject] | --subject=[subject] | Finds a story based on the provided subject |