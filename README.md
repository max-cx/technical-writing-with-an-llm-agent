# README

This README is for the `git@github.com:max-cx/technical-writing-with-an-llm-agent.git` repository.

## Getting started with using an LLM agent in technical writing

Using an LLM agent can save a technical writer time on some subtasks and streamline work by eliminating some delays.

Click a heading below to expand its section.

<details>
<summary>

### Prerequisites

</summary>

* You have a paid subscription to use an up-to-date LLM agent that uses an appropriate LLM version and is approved by your project, for example:

    * [Claude Code](https://code.claude.com/docs) (terminal)
    * [Cursor](https://cursor.com/docs/) (desktop)

Note that you can select the latest, more expensive LLM version for very complex text-processing tasks, while using a simpler, cheaper LLM version for uncomplicated automation-like tasks.

</details>

<details>
<summary>

### Your mental and brain health

</summary>

When using AI, monitor your mental wellness. Extensive daily usage of AI can carry risks to mental and brain health that are not yet well understood. Extensive reliance on an LLM agent might be habit-forming and result in skill erosion and brain atrophy as described in some recent studies:

* [MIT media lab research: Your Brain on ChatGPT: Accumulation of Cognitive Debt when Using an AI Assistant for Essay Writing Task](https://arxiv.org/abs/2506.08872)
* [AI is giving workers the illusion of expertise — and quietly making them worse at their jobs](https://www.businessinsider.com/ai-making-workers-feel-smarter-but-worse-at-their-jobs-2025-12)
* [Experimental evidence of the effects of large language models versus web search on depth of learning](https://pubmed.ncbi.nlm.nih.gov/41163786/)
* [Microsoft Research: The Impact of Generative AI on Critical Thinking: Self-Reported Reductions in Cognitive Effort and Confidence Effects From a Survey of Knowledge Workers](https://www.microsoft.com/en-us/research/publication/the-impact-of-generative-ai-on-critical-thinking-self-reported-reductions-in-cognitive-effort-and-confidence-effects-from-a-survey-of-knowledge-workers/)
* [Microsoft Research Blog: Rethinking AI in Knowledge Work: From Assistant to Tool for Thought](https://www.microsoft.com/en-us/research/articles/rethinking-ai-in-knowledge-work-from-assistant-to-tool-for-thought/)

</details>

<details>
<summary>

### General tips for using an LLM agent for technical writing

</summary>

Here are some basic tips for you to get into the mindset of using an LLM agent for technical writing:

* The LLM agent can perform free-form single-conversation tasks and structured repeated tasks.

* As a technical writer, you often have to decide on a case-by-case basis which subtasks require a human UX perspective or can be done quickly manually. Identify which subtasks appear tedious and time-consuming and can be handled with assistance from an LLM agent. Whether a subtask is handled manually or with assistance from an LLM agent can vary across different issues, so the same kind of subtask might be more suited to manual resolution in one issue but LLM-agent-assisted resolution in another.

* A locally installed Claude Code TUI or Cursor GUI, whichever interface type you prefer, offers additional features over browser-based web applications such as Google Gemini. At your request, the locally installed LLM agent can operate on files in the local filesystem, including local Git clones. It can read content files, read files with your personal reusable prompts, create or edit single or multiple files, and save its prompt output such as reports or scripts as local files. Using a locally installed LLM agent daily can spare you from many mouse clicks to copy and paste and from having to create or edit files manually every time. You don't need to switch to your editor to locate the line where you need to paste the text that the LLM agent generates; the LLM agent itself can save its suggestion in the relevant file on the relevant line.

* You can ask the LLM agent to suggest improvements to your prompt text to optimize it for regular use.

* You can use the LLM agent as a permanently available source of Linux operating system literacy and advice. This is particularly important if you don't have a developer's level of Linux expertise as a technical writer.

* You can ask the LLM agent to assist you with installing and troubleshooting local technical-writing tools such as Vale.

* If you use Bash scripts, you can ask the LLM agent to write or modify a Bash script for you.

* You can always ask a locally installed LLM agent to save your prompt dialogue, for example the last entered prompt and response, to a file, with or without specifying a file path and file name.

</details>

<details>
<summary>

### Using the LLM agent to discover relevant engineering knowledge

</summary>

You can use the LLM agent for topic discovery and gaining an understanding of various aspects of the technical subject matter. You can ask the LLM agent questions ranging from conceptual to procedural knowledge.

Imagine that a new engineering intern has just joined your project and is now available 100% of the time to answer any of your questions and explain to you anything that you need whenever you need and for as long as you need. The LLM can answer many SME-grade questions, allowing you to skip a wait for an SME and understand the topic beyond the limits of an SME's availability to discuss the topic with you. For example, you can ask questions about the components, workings, and usage of a software application. While considering the LLM as a SME, treat its responses with caution as if it were a new engineering intern, who is generally well informed and has a can-do attitude but can easily err on the specifics:

* Query the LLM agent as a source of general SME knowledge.

  Note: The Google Gemini web application performed well in this task.

* Where relevant, you can ask the LLM agent for tips about configuring the software application you document in order to test the software application as a user and document a procedure.

* Where relevant, give the LLM agent a URL or file path to codebase PRs or upstream docs repositories and code repositories.

And as with any information you receive from a new engineering intern, you have to double-check it with the experienced engineers on your team who know the software you are documenting.

</details>

<details>
<summary>

### Using the LLM agent while creating and developing your draft

</summary>

You can collaborate on the draft with the LLM agent as if it were a quick and well-informed yet easily erring intern whom you micromanage and delegate granular tasks to:

* You can consult the LLM agent about terminology usage, markup language syntax, and ask it for grammar advice.

* You can ask the LLM agent to clarify a style rule for you based on your project's style guides.

* You can ask the LLM agent to operate on all or parts of your draft. Depending on what you are drafting, you can ask it for text generation or editing as granular as a single word or as global as covering multiple files.

* You can ask the LLM agent to come up with a list of several, say 5 or 10, alternative rewriting suggestions for a specific piece of text that you identify to it.

* When you pick one of the LLM agent's suggestions, you can improve on it yourself or ask the LLM agent to improve it according to your feedback.

* Ask the LLM agent to perform operations on text files, such as save the suggested change for you in the PR file you are working on.

* At any time, you can resume manual authoring, make your own edits, and again ask for the LLM agent's review.

* Finally, you can review the Git diffs and commit the draft changes yourself.

NOTE: The Google Gemini web application performed well in this task.

</details>

<details>
<summary>

### Using the LLM agent for peer-reviewing your own work

</summary>

Prerequisites:

* You have configured your sources of project style guidance. An example `CLAUDE.md` file is included here for users running a Linux operating system and working on OpenShift docs. For more details, see the section "Configuring your sources of project style guidance".

The LLM agent can quickly peer-review your work whenever and as often as you need. If you have sufficient experience, the LLM agent can help you skip human peer reviews and avoid a delay of waiting in a human peer review queue. Moreover, the LLM agent can free up your time as a peer reviewer by enabling other authors to use the LLM agent for peer-reviewing their own work.

Procedure:

1. Start a new session. Ask the LLM agent to review the content that you specify in the prompt. While you can provide a text snippet, it's more convenient to mention files staged in Git or the files in the last commit in the current branch or another specific branch. For example, you can ask the LLM agent as follows: `Perform a peer review on the files in the last commit of the local clone of the /openshift-docs/ repository.` As configured, the LLM agent saves its review report in a Markdown file.

2. At this point, you have two options: Either you continue the current prompt session and open the saved review report in your editor alongside the prompt window. Or, which you can also do later, start a new session and ask the LLM agent to read the review report file it created.

3. Go through the review points with the LLM agent, one by one. Ask it to suggest edits to fix only those review points that make sense to you. You can ask it to skip or ignore any review points that you don't agree with. Collaborate with it on fixing the files as if you were chatting with a remote intern who is doing the work for you. You can tell it if you agree with its suggested fix. You can ask it to come up with a list of several alternative rewriting suggestions. You can ask it to improve the suggestion of your choice. For any edit, you still have two options: you can ask the LLM agent to edit the files for you, or you can edit the files manually yourself.

Here are some example prompts that you might be typing as you collaborate with the LLM agent on fixing the issues identified by it during its latest review of your work:

```
Fix the critical issues in the file
...
give me a few alternative wording suggestions for line 53
...
ok, update the file with your suggestion 2
...
ignore issue 7
...
for issue 8, show me the diff of your suggested change
...
remove the last sentence in your suggestion
...
ok, update the file
...
About the issue on line 16, replace "you will need" with "you have" and show me your updated suggestion as a diff
...
Is the updated suggestion grammatically correct?
...
OK, update the file like this. 
...
Fix the issue on line 91 as you suggested
```

* After fixing all of the discovered issues, and to make sure that there are no more remaining issues, you can ask the LLM agent to run one more round of review.

* You can attach the review report file, which the LLM agent generated for the final peer review round, to your issue. This way, you can keep a written record of the peer review.

* Finally, you can review the Git diffs and commit the review changes yourself.

Note: The Google Gemini web application failed basic tests when asked to review a PR when a PR link was provided in the prompt.

</details>

<details>
<summary>

### Using the LLM agent for merge reviews

</summary>

Prerequisites:

* You have configured your sources of project rules for merging a PR. An example `CLAUDE.md` file is included here for users running a Linux operating system and working on OpenShift docs. You can configure such sources of your PR merge rules by following the tips in the section "Configuring your sources of project style guidance". For example, see the section `# Claude Instructions for Merge Reviews` in the example `CLAUDE.md` file for how this style guidance is added to the file with instructions for the LLM agent. In this file, you can specify trigger phrases, for example `merge review`, for prompting the LLM agent. 

You can use the LLM agent for your PR merge reviews on your own content, thus skipping a PR merge review queue. You can also use the LLM agent to speed up your merge reviews of other writers' PRs. And if it's a rule for your technical writing team that another writer must perform a merge review that is as thorough as a peer review, then as a merge reviewer, you can also trigger a full peer review by the LLM agent as part of your merge review. For more information on that, see the section "Using the LLM agent for peer-reviewing your own work".

Procedure:

1. Enter a configured trigger phrase such as `merge review` in the prompt of the LLM agent to perform a merge review on the content that you specify in the prompt. The LLM agent generates a merge review report file.

2. Open the merge review report file that the LLM agent generated.

3. Update the PR if needed.

4. You can attach the merge review report file to your issue to keep a written record of the merge review.

Note: The Google Gemini web application failed basic tests when asked to review a PR when a PR link was provided in the prompt.

</details>

<details>
<summary>

### Troubleshooting the LLM output

</summary>

* If the LLM agent makes a determination that appears nonsensical to you, ask the LLM agent to explain to you why it made such a determination.

* If any data that the LLM agent provides appears implausible to you, ask the LLM agent for a URL to the source of this data. Then you open that webpage in your browser and use the browser search feature (**Ctrl**+**F**) to find the relevant information by a keyword. If the LLM agent is unable to provide a URL to the source of this data, then you can use an online search engine to double-check.

* For technical data accuracy, always rely on a human review by a human SME such as a developer or QE.

</details>

<details>
<summary>

### Configuring your sources of project style guidance

</summary>

Before you configure sources of project style guidance, you can make an inventory of the existing files that contain this information, which can be Git repositories, text files in a markup language such as Markdown or AsciiDoc, or PDF files. If your project already uses online Git repositories that are dedicated to project style guidance, those repositories can continue to be used as they are. Technical writers on your project can clone these style guidance repositories on their machines so that a locally installed LLM agent can read them in the filesystem.

If your team already includes product-specific style guidance in files inside the product docs repository, these files can continue to be used. Simply add them as style guidance sources for the locally installed LLM agent to read from your local clone of the product docs repository. While an LLM agent is currently unable to read PDF files, as a short-term workaround, in-house produced PDF files can be converted to text on your machine specifically for the LLM agent. If you are using a paid subscription for the LLM agent, it is supposed to only read local files and not use them as training data.

You or other humans on your project can prepare and maintain one or more Markdown files such as `CLAUDE.md` that specify both the mentioned sources of project-level and team-level style guidance and the checklists for peer reviews and merge reviews. These Markdown files can be read and used both by humans and by LLM agents. These Markdown files can be hosted in a separate Git repository or inside the docs repository, whichever is more convenient. This way, every technical writer on your project can clone these Markdown files locally and use them when prompting the LLM agent for recurring instructions.

The advantage of centralizing the sources of style guidance and checklists for peer reviews and merge reviews into project-level and team-level LLM-agent-friendly Markdown files is that maintainers can improve and update them. The maintainers can do so thanks to feedback from a body of writers, who can open issues and even PRs. This allows all writers to benefit with least effort, not requiring LLM expertise from every single writer, while all writers can start using an LLM agent to do their work.

A locally installed LLM agent enables writers to use it to review their work against any single source of style guidance or against all of multiple sources of style guidance at once. Here are some ways of configuring the sources of style guidance so that a locally installed LLM agent can use them in addition to the human writers who are already using them:

* The LLM agent can detect grammar, spelling, and punctuation errors, so you can always ask it to quickly check your draft for such obvious errors. For example, see the section `# Claude Instructions for Quick Reviews` in the example `CLAUDE.md` file for how you can specify trigger phrases, for example `quick review`, for prompting the LLM agent.

* If your project's style guidance is already available as Vale styles, you can continue to use and maintain Vale even if you start using an LLM agent. You can ask the LLM agent to run Vale on local staged files or on the files in the last commit in the current branch or another branch, and analyze Vale output, and ignore false positives, and suggest changes and show the diffs of its suggestions, and update the files for you with your approval. You can also add this task to the file with instructions for the LLM agent.

  For example, see the section `# Claude Instructions for Vale Reviews` in the example `CLAUDE.md` file
  for how such style guidance is added to the file with instructions for the LLM agent. In this file,
  you can specify trigger phrases, for example `Vale review`, for prompting the LLM agent.

* If your project's style guidance is available as Git repositories, clone those repositories so that the LLM agent can read them as local files, for example:

  ```
  $ cd ~/ && \
  mkdir review && \
  cd review && \
  git clone git@github.com:redhat-documentation/supplementary-style-guide.git && \
  git clone git@github.com:redhat-documentation/modular-docs.git
  ```

  For example, see the sections `# Claude Instructions for SSG Reviews` and
  `# Claude Instructions for Mod Docs Reviews ` in the example `CLAUDE.md` file
  for how such style guidance is added to the file with instructions for the LLM agent.
  In this file, you can specify trigger phrases, for example `ssg review` and `mod docs review`,
  for prompting the LLM agent.

* If your project distributes style guidance only in in-house PDF files, download and prepare the latest-version files for use by the LLM agent. It cannot read PDF files, but it can read large text files that have been split into chunks:

  ```
  $ pdftotext -layout <path>/<pdf_style_guide>.pdf <path>/<pdf_style_guide>.txt # convert the PDF file to a text file
  $ wc -l <path>/<pdf_style_guide>.txt # see the total number of lines in the text file
  $ split -l 2000 -d -a 3 -e --verbose <path>/<pdf_style_guide>.txt <dir_for_chunks>/<pdf_style_guide>.txt # chunk the file into smaller files sized not greater than 2000 lines each
  ```

  For example, see the section `# Claude Instructions for PDF Style Reviews` in the example `CLAUDE.md` file
  for how such style guidance is added to the file with instructions for the LLM agent.
  In this file, you can specify trigger phrases, for example `pdf review`, for prompting the LLM agent.

* Add product-specific style guides to the file with instructions for the LLM agent. In this example, the product-specific style guidance is maintained in two locations: as a list of human-readable criteria `- [ ]` in the `CLAUDE.md` file and as files in the docs repository, and thus the LLM agent can read it as files in the local clone of that repository:

  ```
  ~/openshift-docs/contributing_to_docs/doc_guidelines.adoc
  ~/openshift-docs/contributing_to_docs/term_glossary.adoc
  ~/openshift-docs/contributing_to_docs/contributing.adoc
  ~/openshift-docs/contributing_to_docs/contributing_user_stories.adoc
  ```

  For example, see the section `# Claude Instructions for OCP Reviews` in the example `CLAUDE.md` file
  for how such style guidance is added to the file with instructions for the LLM agent.
  In this file, you can specify trigger phrases, for example `ocp review`, for prompting the LLM agent.

* If your project uses multiple sources of style guidance, then the file with instructions for the LLM agent can contain a prompt trigger phrase, for example `peer review`, for a compound peer review that includes all of your sources of style guidance. This way, you can ask the LLM agent to review your work against any single source of style guidance or against all of the sources of style guidance. For an example of this, see the section `# Claude Instructions for Peer Reviews` in the example `CLAUDE.md` file.

* An LLM agent is currently unable to see a preview and as a result cannot detect rendering issues in the preview. So you must continue to review the rendered preview manually and with great care.

</details>
