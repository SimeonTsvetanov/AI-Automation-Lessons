# Fundamentals

## Main Topics

1. **What is a workflow?**
2. **Mastering the basics**
3. **Data transformation**
4. **Your first automation**

---

## New Project: Collecting and Editing Data from Emails

- Using Gmail, set up new Auth2.0 from Google Console:
  - Enable: Drive, Calendar, Sheets, Gmail
  - Create AUTH Client with the OAuth Redirect URL provided by the n8n element
  - **P.S.**: Don't forget to add your email for the test client (not in video, but required for it to work!)
- Create "Set Email Values" node to access only the needed values
- Use "Convert to Markdown" (e.g., convert HTML to markdown as in the example)
- Post email data using Airtable (create a new table for it)
- now in order for me to keep track ie created a sample invoice so that i can analyze it using the flow.
  - note \*\*\* When adding attachments place close attention to what the names of the attachments are: attachment / data or others...
- i had to add custom code using ai to make clearer text:

    ```javascript
    const dirtyText = item.json.text;

    // Remove all special characters except commas and periods.
    // Also removes newlines, tabs, and multiple spaces.
    const cleanText = dirtyText
      .replace(/[\r\n]+/g, ' ')      // Replace newlines with space
      .replace(/[^\w\s.,]|\t/g, '')  // Remove everything except words, spaces, commas, periods
      .replace(/\s+/g, ' ')          // Replace multiple spaces with single space
      .trim();                       // Remove leading/trailing spaces

    // Update the text field with cleaned version
    item.json.text = cleanText;

    return $input.all();
    ```

*** REMEMBER THAT if we have more actions (branches from the same parent) the one that is above will be executed first!!!

by the end of second stage we have covered: if, loops and merge blocks.