# Google Keep takeout

Converts Google Keep JSON files downloaded from [Google Takeout](https://takeout.google.com/) to new markdown files. Markdown filenames are organized by subdirectory matching the Google Keep note's label name. All JSON properties are easily accessible, making it simple to customize the export.


### Usage

Run the script inside your "Takeout" folder, in the same directory as the "Keep" folder that contains the JSON notes.
```sh
python export.py
```

Markdown files will be created in a new "markdown" folder, also residing in the Takeout folder.


### Sample result

For the Google Keep note "groceries" tagged with the label "shopping lists", you can expect the following result:

Filename: "/markdown/shopping lists/groceries.md"
```
### Groceries
Last edited: Monday July 13, 2020, 10:08:21 AM

- [ ] nduja
- [ ] nutella
- [ ] ichnusa
- [ ] ravioli
- [x] pesto genovese
- [x] viennetta
```
