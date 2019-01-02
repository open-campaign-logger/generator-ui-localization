# generator-ui-localization
## A repository for localization files for the Generator UI

These are the language translation files for the new Generator-UI. It contains captions, titles, hints, etc. as strings.

For each language we have a seperate JSON-File. On the left side on each line is the internal description of that string and the right side contains the actual string:

### Example: 
 ```
"listview.categories": "Categories",
```
For translation you have to change only the right string between the quotes:

```
"listview.categories": "Here is the new translation!",
```

If you like to make a new translation, we would suggest that you download the suiting JSON-File, rename it to the according country abbreviation (see list below) and then change the strings.
Please preserve the JSON formatting so it is easier to validate the files.

Either you can contact us to get added as collaborateur to get write access to the develop branch or you can fork and pull request the develop branch to apply changes.

#### Country Abbreviations:

See https://en.wikipedia.org/wiki/ISO_3166-1#Current_codes

Please take Alpha-2 Code in lowercase.

#### Example:
Iceland	IS => "is.json"
