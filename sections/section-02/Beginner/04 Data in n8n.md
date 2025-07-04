# 04 Data in n8n

[Data in n8n Video](https://www.youtube.com/watch?v=2YfWuNziPE4&ab_channel=n8n)

- [ ] Watched video

## Notes

## Data Structures in n8n

### JSON

JSON (JavaScript Object Notation) is a structured data format that uses key-value pairs enclosed in curly braces, where each value can be a string, number, boolean, array, or nested object.

### Lists/Arrays

Lists in n8n are ordered collections of items enclosed in square brackets, where each item can be accessed by its position (index) starting from 0.

### Working with JSON

To work with JSON data in n8n, you can access values using dot notation (e.g., `{{$json.fieldName}}`) or bracket notation (e.g., `{{$json['fieldName']}}`) in expression fields.

### Working with Lists

To work with lists in n8n, you can access individual items using index notation (e.g., `{{$json.items[0]}}`) or iterate through them using nodes like "Split In Batches" or "For Each".

we have added edit field node to add new column in the sheet. As Full name concatenating the first and second name with it.
