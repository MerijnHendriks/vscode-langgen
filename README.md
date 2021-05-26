# vscode-langgen

Boilerlplate project for generating your own language in Visual Studio Code

## Requirements

- git
- node 12+
- vscode

## Setup

1. open vscode
2. terminal > `git clone https://github.com/MerijnHendriks/vscode-langgen.git`
3. terminal > `npm install`
4. terminal > `npm run langgen:init`

## Generate

### 1. Initialize

**question**                                  | **answer**
--------------------------------------------- | -----------------------------------------
What type of extension do you want to create? | `New Language Support`
URL or file to import, or none for new?       | `press ENTER to start with a new grammar`

### 2. VSCode package

**question**                              | **answer**                        | **example**
----------------------------------------- | --------------------------------- | --------------------------------
What's the name of your extension?        | `<language>`                      | Duckie Duck
What's the identifier of your extension?  | `<language shorname>lang`         | ducklang
What's the description of your extension? | `<language> Programming Language` | Duckie Duck Programming Language

### 3. Language

**question**    | **answer**                    | **example**
--------------- | ----------------------------- | --------------------------------
Language id     | `<language shorname>`         | duck
Language name   | `<language>`                  | Duckie Duck
File extensions | `.<language shortname>`       | .duck
Scope names     | `source.<language shortname>` | source.duck

### 4. Git

- Initialize a git repository? `yes`/`no`
