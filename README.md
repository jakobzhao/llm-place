# Using LLM to Analyze Sense of Place and Make Storymaps

**Author:** Bo Zhao, [jakobzhao@gmail.com](mailto:jakobzhao@gmail.com); **Points Available** = 50

This lab helps you explore how large language models (LLMs) can be used to extract, interpret, and visualize geographic narratives, particularly in terms of the emotional and cultural concept of “sense of place.” Drawing on Chapter 13 from the book *Seattle Walks*, this tutorial walks you through how to automate the identification of key landmarks and how to structure those findings into geospatial formats. The process culminates in an interactive story map that links prose with place, helping us ask: What does it mean when machines try to read geography?

You will:

* Prompt an LLM (Gemini Flash) to extract structured place-based information from a PDF
* Visualize the extracted data as a CSV, GeoJSON, and web map
* Reflect on what kinds of emotional or cultural place attachments are represented
* Publish your own map using GitHub Pages

> **Guiding question:** How do large language models interpret place, memory, and cultural meaning—and what do they get wrong?

Click this button to launch the full lab on Colab:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jakobzhao/llm-place/blob/main/place.ipynb)

The lab includes the following key files:

* `place.ipynb`: A Python notebook that prompts the LLM, parses results, and generates map-ready outputs.
* `capitol_hill.geojson`: GeoJSON output from Chapter 13 of *Seattle Walks*.
* `index.html`: A standalone story map using MapLibre GL JS that reads and visualizes the GeoJSON.

After you execute the notebook, you will have built a fully functional story map that shows how a machine parsed and interpreted urban space. Your task is to use this method to analyze a different text.


* A different chapter from *Seattle Walks*
* Another narrative walk or geographic essay with descriptive text

Then:

1. Replace the PDF input in the notebook with your new text.
2. Prompt Gemini to extract landmarks and place sentiment.
3. Generate your own CSV, GeoJSON, and HTML story map.

### In your reflection, please address:

* What kinds of places were highlighted by the model?
* Were there any hallucinations (i.e., places or meanings that were fabricated)?
* Which parts of the LLM's analysis were insightful or surprising?
* What limitations or biases did you observe?
* How would your reading of the narrative differ from the model’s output?

> This lab encourages you to think critically about what LLMs understand—and what they miss. Some things to consider: LLMs may invent places or associations that don’t exist in the source text. They may mislabel emotional tone or overgeneralize cultural significance. But they may also surface subtle themes you hadn’t noticed before.

Ask yourself: Can LLMs help us notice new patterns in narrative geography, or do they merely flatten nuance?

**Deliverables:** 

Submit your modified notebook, your new map outputs, and your written reflection (300-500 words) to Canvas.

**Note:** Lab assignments are required to be submitted electronically to Canvas unless stated otherwise. Efforts will be made to have them graded and returned within one week after they are submitted.Lab assignments are expected to be completed by the due date. ***A late penalty of at least 10 percentage units will be taken off each day after the due date.*** If you have a genuine reason(known medical condition, a pile-up of due assignments on other courses, ROTC,athletics teams, job interview, religious obligations etc.) for being unable to complete work on time, then some flexibility is possible. However, if in my judgment you could reasonably have let me know beforehand that there would likely be a delay, and then a late penalty will still be imposed if I don't hear from you until after the deadline has passed. For unforeseeable problems,I can be more flexible. If there are ongoing medical, personal, or other issues that are likely to affect your work all semester, then please arrange to see me to discuss the situation. There will be NO make-up exams except for circumstances like those above.
