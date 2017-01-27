# jquery.filterByText
This is a jQuery Plugin to filter the options on a multi select box using a text input

Usage

```
$(multiselect).filterByText(textinput, true);
```

For example:

```
$('.fieldList').filterByText($('#fieldListFilter'), true);
```

The last argument selectSingleMatch is a boolean value, when it's set to true it will select the first option of the filtered results, otherwise it will only filter and wont select any option.
