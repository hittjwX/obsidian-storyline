# How To Publish Your Manuscript In StoryLine

## Overview

- The [Obsidian StoryLine plug-in](https://community.obsidian.md/plugins/storyline) offers a modern, offline workspace where your plot grid, worldbuilding, and draft sty connected in real time.
- Similar functionality is available as a stand alone application [StoryLine Scribe](https://storylinescribe.com/), which can read writing created in the Obsidian StoryLine plug-in.
- The purpose of this document is to help you go from writing to publishing your manuscript. These formats are foundational for print on demand, digital publishing, or ePub conversion.
- You will publish your manscript when sending it for review, submitting it to a publisher, or to ciculate for editing. StoryLine focuses on the structure, craft, and workflow of your writing primarily.

## Compatibility With Distribution

StoryLine can create simple PDF, Markdown, Microsoft, and HTML exports. When publishing your Manuscript choose `Content` type "Manuscript (scene text order)" from export window. If in doubt, give a Microsoft Word document to your publisher or literary agent.

- If you already publish with [Pandoc](https://pandoc.org/MANUAL.html), export first to Markdown. Add your Pandoc specific front matter to the exported file. Compile on the command line. 
- If you already publish with [Lightning Source](https://www.lightningsourceus.com/) print-on-demand. Export from StoryLine as Microsoft Word. Format then export to PDF. Open in Adobe PDF to add cover properly sized spine for the number of pages. https://www.ingramcontent.com/publishers-page/print-on-demand-faqs 
- TBD, Amazon Kindle Direct Publishing (KDP), https://kdp.amazon.com/en_US/help/topic/G202172740
- TBD, IngramSpark, https://www.ingramspark.com/hubfs/downloads/file-creation-guide.pdf
- TBD, [LuLu](https://www.lulu.com/) print-on-demand books. https://www.lulu.com/publishing-toolkit/

Exports from StoryLine are formatted on Letter sized paper. Courier font, simple headings and formatting. Manuscripts are submitted to literary agents, published for reading groups, and to send to editors.

If you want a more polished format, use a Markdown or HTML export with a third-party book formatting tool, or use [StoryLine Scribe](https://storylinescribe.com/). StoryLine Scribe gives you control over formatting.

## Structure Your Writing

For your manuscript to layout in a meaningful way Markdown formatting in StoryLine is important.

StoryLine Navigator and Kanban doesn't show hiearchy in your writing. Each card is scene based.

- Use `#` for scenes that represent Act headings.
- Use `##` in your scene for Chapter headings.
- Use `###` for Sections within a Chapter.

The scene order is determined by `Sequence` which is available by dragging and dropping Kanban cards. Or edit directly by clicking on the card.

All regular Markdown gets rendered in previews. LaTeX and Mermaid doesn't preview but can be rendered using Pandoc.

 