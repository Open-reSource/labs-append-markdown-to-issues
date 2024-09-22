# [Labs] Automatically append Markdown to issues

This repository contains a GitHub workflow allowing to append a reminder of the Contributing Guidelines for each newly created issue as stated by:

```yml
on:
  issues:
    types: [opened]
```

Thanks to the [julien-deramond/update-issue-body](https://github.com/julien-deramond/update-issue-body) GitHub Action, the workflow will append the Markdown sentence to the issue body automatically.

You can see the result in https://github.com/Open-reSource/labs-append-markdown-to-issues/issues/17 and https://github.com/Open-reSource/labs-append-markdown-to-issues/issues/18 that have been modified by the workflow.

<img width="927" alt="Screenshot 2023-05-17 at 21 15 03" src="https://github.com/Open-reSource/labs-append-markdown-to-issues/assets/17381666/79a0eeb5-a988-46fc-bc0d-b191c82ae568">

<img width="913" alt="Screenshot 2023-05-17 at 21 15 13" src="https://github.com/Open-reSource/labs-append-markdown-to-issues/assets/17381666/ad7991aa-8bff-4d32-b40e-2a43b95c9760">

## Steps to install it in your repository

1. Create a new worfklow in `.github/worfklows` (name doesn't matter)
2. Copy and paste the content of [`.github/workflows/append-markdown-to-issues.yml`](.github/workflows/append-markdown-to-issues.yml) in your workflow file and adapt its content to your needs

You can copy and paste this repository's workflow content in your own repository if you want to do the same thing for enforcing your own Contributing Guidelines for example, or adapt it to your needs.

## Sponsors of Open {re}Source

<p align="center">
  <img src='https://cdn.jsdelivr.net/gh/Open-reSource/sponsors/sponsors.svg'/>
</p>
