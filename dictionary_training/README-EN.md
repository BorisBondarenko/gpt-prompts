# Dictionary Training

## Description

This file is designed to help train vocabulary in three languages. The training is conducted in a verbal interaction format using ChatGPT, where the participant practices translating words between these languages.

## Setup and Training Instructions

1. Upload the file to ChatGPT: First, you need to upload the file from the **/prompt** directory, which is located next to this README file.
2. Initiate the prompt: After uploading, instruct ChatGPT to read the prompt located in this file along with the dictionary. This setup is essential to start the session.
3. Random word selection: After initiating the prompt, ChatGPT will randomly select words from the table for translation.
4. Translation to English: The participant is asked how the word is translated into English. For example, "Do you know how to say 'Database' in English?".
5. Translation to Czech: If the English translation is correct, the participant is asked how the word is translated into Czech.
6. Pronunciation correction: If the pronunciation or translation is incorrect, the participant is provided with the correct version and asked to repeat it. The participant has up to three attempts to correct their response.
7. Automatic transition to the next word: After completing one cycle, a new word is randomly selected for translation.
8. Training completion check: If all the words in the table have been covered, the participant is informed, and asked if they want to repeat the training.

## Customization

- Languages: You can customize the languages used for training. By default, Ukrainian, English, and Czech are used.
- Number of words per day: The number of words trained per day can also be customized. You can choose between 10 to 20 words per day, or any other number according to your needs.

## Table Format

The table contains three columns:

- English (British): the word in English
- Czech: the word in Czech
- Ukrainian: the word in Ukrainian

## Example Table

| English (British)  | Czech            | Ukrainian         |
|--------------------|------------------|-------------------|
| database           | databáze         | база даних        |
| server             | server           | сервер            |
| frontend           | frontend         | фронтенд          |
| backend            | backend          | бекенд            |
| framework          | framework        | фреймворк         |
| deployment         | nasazení         | розгортання       |
| API                | API              | API               |
| debugging          | ladění           | відлагодження     |
| repository         | úložiště         | репозиторій       |
| source code        | zdrojový kód     | вихідний код      |
| continuous integration | průběžná integrace | безперервна інтеграція |
| pull request       | požadavek na stažení | запит на витягування |
| version control    | správa verzí     | керування версіями|
| code review        | kontrola kódu    | перевірка коду    |
| hosting            | hosting          | хостинг           |

## Training Goal

This training file helps to improve language skills in English and Czech, based on the native Ukrainian language. This approach allows participants to effectively expand their vocabulary and improve pronunciation, especially in the field of development and programming.

## Usage

The file necessary for working with ChatGPT, which contains both the prompt and the dictionary, is located in the **/prompt** directory next to this README.md file. This directory includes files in multiple languages. Simply download the required file, then regularly update it with your own vocabulary.

To activate the new information, you just need to update this file in ChatGPT.
