## GUIDE – How to Use the Timeline on Weebly
Log in to your Weebly site editor.
Go to the page where you want to insert the timeline.
Drag an “Embed Code” block into the page.
Open the file “timeline.html” included in this package.
Copy the entire content and paste it into the Embed Code block.
Edit your timeline events inside the <script> section, in the block starting with const events = [...].

## Each event must include three fields:
date: the event date (e.g., "12/05/2025")
description: a short description (e.g., "Grand Opening")
position: either "left" or "right" to choose the timeline side

##Important Notes:
Only the last event in the list should NOT end with a comma ,
All previous events must end with a comma after the closing brace },

## Example: Timeline Events Definition

You can edit your timeline by modifying the JavaScript block like this:

```js
const events = [
  { date: "12/05/2025", description: "Grand Opening", position: "left" },
  { date: "02/06/2025", description: "Free gaming", position: "right" },
  { date: "20/06/2025", description: "Summer Festival", position: "left" }
];
```
