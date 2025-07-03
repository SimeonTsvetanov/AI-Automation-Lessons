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
