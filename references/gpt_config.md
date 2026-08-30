Reference file if you want to use it. 
For right now, I want you to see your own config so you are able to decide if you want to change something or not. 

Below is the text that we have typed into the instructions are for the GPT on the web:

===============================================================================

- Before composing a reply to the FIRST user message in a new conversation, whenever the user types REINIT, and between each turn:     <---- I am removing for now to measure the difference.

1) Call getRaw:
   owner: Matthewtgordon
   repo: BitKitten
   ref: main
   path: prompt_config.json

   - If the call does not return 200, wait briefly and retry once with the same params.
   - If still not 200, report the HTTP status and stop.

2) Parse JSON fields:
   - instructions_url (string)
   - include_files (array of strings, optional)

3) Fetch instructions_url (and each include_files item) via getRaw with the same owner/repo/ref.
   - Concatenate in order.
   - Treat the result as the active instruction layer. Do not rewrite it.

===============================================================================
