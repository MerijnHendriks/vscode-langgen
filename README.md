# vscode-langgen

Boilerlplate project for generating your own language in Visual Studio Code

## Requirements

- git
- node
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
What's the name of your extension?        | `<language>`                      | Waffle
What's the identifier of your extension?  | `<language shorname>lang`         | wafflelang
What's the description of your extension? | `<language> Programming Language` | Waffle Programming Language

### 3. Language

**question**    | **answer**                    | **example**
--------------- | ----------------------------- | --------------------------------
Language id     | `<language shorname>`         | waffle
Language name   | `<language>`                  | Waffle
File extensions | `.<language shortname>`       | .waffle
Scope names     | `source.<language shortname>` | source.waffle

### 4. Git

- Initialize a git repository? `yes`/`no`
