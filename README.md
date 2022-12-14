# CLI Completion Bot

Inspired and adapted from [graiz's cbot](https://github.com/graiz/cbot).

Type plain English into cbot and it will output the CLI command as a string, execute the command, or copy it to clipboard. 

## Output command as string
![Example of language completion./Media/](./Media/cbot_display.png)

## Execute command
![Example of execution](./Media/cbot_execute.png)

## Copy command
![Example of copy](./Media/cbot_copy.png)

## Instalation

1. pip3 install openai
2. Get openai key from https://beta.openai.com/account/api-keys
3. Add API as environment variable "OPENAI_API_KEY" or paste plain text in code.
4. Run: ```chmod +x cbot``` in folder with cbot
5. Add cbot to existing $PATH bin
   1. Add new location to $PATH by adding the following to your .bashrc or .zshrc
   2. ```export PATH=/home/usr/cbot_directory_location:$PATH```

Enjoy!