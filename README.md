# AskOpenAI


Ask ChatGPT questions from the command line.

This project is a fork of Frank Krueger's excellent [AskGPT](https://github.com/praeclarum/AskGPT), with a few modfications to enable alternate (enterprisey) data sources.

<img width="600" alt="Screenshot" src="https://raw.githubusercontent.com/githubjoneill/AskOpenAPI/master/.github/Ask1.png">

## Usage

```bash
ask what is the meaning of life?
```

## Installation

1. [Install .NET 7](https://dotnet.microsoft.com/download/dotnet/7.0)
1. Compile the application, and then publish to a local folder.
1. Copy the 'publish' folder to a new application folder the target PC.  
1. [Optional step] For best results, edit the user's PATH configufration setting to include that application folder location.
1. Create an OpenAI API key at [https://platform.openai.com/account/api-keys](https://platform.openai.com/account/api-keys)
1. Create a user profile file called `~/.config/AskOpenAPI/apikey.txt` with your OpenAPI key in it
1. [Optional step] To enable a look up results from a SQL Server database, run the applicaton with the command line parameter `--createdbconfig` and then modify that generated file to provide database and table information.


