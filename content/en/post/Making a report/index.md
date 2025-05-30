---
title: Creating a report
summary: I create reports in Markdown. Here's a quick guide to creating reports. The photo shows an example of the report structure.
date: 2025-05-01

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
  
authors:
  - admin
tags:
  - Academic
---

{{< toc mobile_only=true is_open=true >}}

## Main sections of the report
When making a report, it is important to include the following mandatory sections:
####  Purpose of the work
- A brief description of why the work is being carried out. For example:
The purpose of the work is to familiarize yourself with the basic commands of the Linux shell and learn how to create scripts.
#### Task
- A list or text indicating what needs to be done during the laboratory. This can be either a text description or a list:
```
**Task:**
1. Install the 'htop` package.
2. Create a script `backup.sh `.
3. Set up a cron task.
```
#### Theoretical introduction
- An explanation of the key concepts and approaches needed to complete the work. Here you can use lists, highlights, headers, links:
```
**Terms:**
*Shell* is a UNIX command shell. *Script* is a file with a set of commands.
```

#### Progress of the work
- A detailed description of the execution steps with explanations, code, command outputs and, if necessary, images.
You can insert screenshots as follows:

```
![Результат выполнения скрипта](images/script_output.png)
```
To insert the code, use three apostrophes at the top indicating the language before the code and three apostrophes after the code.

```bash
echo "Hello, world!"
```
#### Conclusions: what has been done, what has been learned, what difficulties have you encountered. For example:

During the work, the basic shell commands were mastered and an automatic backup script was created. Now I understand how cron works and can automate simple tasks.

### Useful Markdown Elements

Headlines: #, ##, ### — for the logical structure.

Code: triple quotes or single backtracks (`) are used to insert the code.

Lists: -, * or 1. — for bulleted and numbered lists.

Links:
```
[GitHub](https://github.com)

Images:
![Description](path_or_URL)
```
## Results

Making a report is an important part of any job. Markdown is an easy—to-learn markup language that is ideal for creating reports, especially in technical and academic disciplines. It allows you to create structured, readable and easily converted to PDF or HTML documents.
---










