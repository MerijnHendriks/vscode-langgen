# vscode-langgen

Boilerlplate project for generating your own language in Visual Studio Code

## Requirements

- git
- node 12+
- vscode

## Setup

1. `git clone https://github.com/MerijnHendriks/vscode-langgen.git`
2. open `vscode-langgen` in vscode
3. terminal > npm install

## Generate

### 1. Initialize

1. terminal > `npm run langgen:init`
2. select `New Language Support`
3. `press ENTER to start with a new grammar`

### 2. vscode package

**question**                                | **answer**                        | **example**
------------------------------------------- | --------------------------------- | --------------------------------
`What's the name of your extension?`        | `<language>`                      | Duckie Duck
`What's the identifier of your extension?`  | `<language shorname>lang`         | ducklang
`What's the description of your extension?` | `<language> Programming Language` | Duckie Duck Programming Language

### 3. language

**question**      | **answer**                    | **example**
----------------- | ----------------------------- | --------------------------------
`Language id`     | `<language shorname>`         | duck
`Language name`   | `<language>`                  | Duckie Duck
`File extensions` | `.<language shortname>`       | .duck
`Scope names`     | `source.<language shortname>` | source.duck

### 4. git

- `Initialize a git repository?` yes/no
