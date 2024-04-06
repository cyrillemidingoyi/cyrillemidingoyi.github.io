# Table of Contents

- [Table of Contents](#table-of-contents)
- [Installing and Deploying](#installing-and-deploying)
  - [Recommended Approach](#recommended-approach)

# Installing and Deploying

## Recommended Approach

The recommended approach for using **al-folio** is to first create your own site using the template with as few changes as possible, and only when it is up and running customize it however you like. This way it is easier to pinpoint what causes a potential issue in case of a bug. The minimum steps required to create your own site are:

1. Create a new repository using this template. For this, click on [Use this template -> Create a new repository](https://github.com/new?template_name=al-folio&template_owner=alshedivat) above the file list. If you plan to upload your site to `<your-github-username>.github.io`, note that the name of your repository :warning: **MUST BE** :warning: `<your-github-username>.github.io` or `<your-github-orgname>.github.io`, as stated in the [GitHub pages docs](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages#types-of-github-pages-sites).
2. In this new repository, go to `Settings -> Actions -> General -> Workflow permissions` and give `Read and write permissions` to GitHub Actions.

```bash
$ git clone git@github.com:<your-username>/<your-repo-name>.git
```
