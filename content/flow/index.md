---
title: Flow
menu: main
weight: 10
---

# Inboxes

## Thought Tank Inbox

You can use the flow state `inbox` for new notes. Then we new you are aware that these notes need editing. We show notes with the `inbox` state here and remove them from the lists below.

{{< flow/inbox >}}

## Further Inboxes

* [Pocket, articles tagged with inbox](https://app.getpocket.com/tags/inbox/all)
* [Apple iCloud Notes](https://www.icloud.com/notes/)

Add your own inboxes here.

## Connecting Notes

Connecting Notes is an important aspect of a vital zettelkasten.
The following notes might not be linked sufficiently.

{{< flow/unlinked-notes threshold="0" >}}

### Links with Outdated Title in Link

To provide stable but readable markdown links we suggest to link notes using `[#](/notes/<id> "<title>")` and autogenerate the link code for you.
However the title in the (generated link) is the one at the time of linking.It might change later.
While the link still works as expected, reading the raw link in an editor might be missleading. 
We detect these outdated links for you. You might want to fix it.

{{< flow/links-with-outdated-title >}}

### Implicit Connections by Keywords

The table below lists notes with missing keywords. Detecting related notes heavily depend on keywords. So If you do not list keywords, we cannot find related notes.

{{< flow/missing-keywords >}}