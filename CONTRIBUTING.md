## Contributing

Hi there! We're thrilled that you'd like to contribute to this project. 
Your help is essential for keeping it great.

Contributions to this project are released to the public under the project's open source license.

Please note that this project is released with a Contributor Code of Conduct. 
By participating in this project you agree to abide by its terms.

As a contributor, here are the guidelines we would like you to follow:

 - [Code of Conduct](#coc)
 - [Issues and Bugs](#issue)
 - [Feature Requests](#feature)
 - [Submission Guidelines](#submit)
 - [Sign Your Work](#dco)
 - [Resources](#resources)

## <a name="coc"></a> Code of Conduct

Help us keep this project open and inclusive.
Please read and follow our [Code of Conduct][coc].

## <a name="issue"></a> Found a Bug?

If you find a bug in the source code, you can help us by [submitting an issue](#submit-issue) to our [GitHub Repository][github].
Even better, you can [submit a Pull Request](#submit-pr) with a fix.

## <a name="feature"></a> Missing a Feature?
You can *request* a new feature by [submitting an issue](#submit-issue) to our GitHub Repository.
If you would like to *implement* a new feature, please consider the size of the change in order to determine the right steps to proceed:

* For a **Major Feature**, first open an issue and outline your proposal so that it can be discussed.
  This process allows us to better coordinate our efforts, prevent duplication of work, and help you to craft the change so that it is successfully accepted into the project.

  **Note**: Adding a new topic to the documentation, or significantly re-writing a topic, counts as a major feature.

* **Small Features** can be crafted and directly [submitted as a Pull Request](#submit-pr).

## <a name="submit"></a> Submission Guidelines

### <a name="submit-issue"></a> Submitting an Issue

Before you submit an issue, please search the issue tracker. An issue for your problem might already exist and the discussion might inform you of workarounds readily available.

We want to fix all the issues as soon as possible, but before fixing a bug, we need to reproduce and confirm it.
In order to reproduce bugs, we require that you provide a minimal reproduction.
Having a minimal reproducible scenario gives us a wealth of important information without going back and forth to you with additional questions.

A minimal reproduction allows us to quickly confirm a bug (or point out a coding problem) as well as confirm that we are fixing the right problem.

We require a minimal reproduction to save maintainers' time and ultimately be able to fix more bugs.
Often, developers find coding problems themselves while preparing a minimal reproduction.
We understand that sometimes it might be hard to extract essential bits of code from a larger codebase, but we really need to isolate the problem before we can fix it.

Unfortunately, we are not able to investigate / fix bugs without a minimal reproduction, so if we don't hear back from you, we are going to close an issue that doesn't have enough info to be reproduced.

You can file new issues by selecting from our [new issue templates][new-issue-templates] and filling out the issue template.

If you found a bug that you consider better discuss in private (for example: security bugs), consider first send an email to TechnoWong@outlook.com.

**We don't have formal bug bounty program for security reports; this is an open source application and your contribution will be recognized in the changelog.**

### <a name="submit-pr"></a> Submitting a Pull Request (PR)

If you want propose a change or bug fix with the Pull-Request system
firstly you should carefully read the **[DCO](#dco)** section and format your
commits accordingly.

If you intend to fix a bug it's fine to submit a pull request right
away but we still recommend to file an issue detailing what you're
fixing. This is helpful in case we don't accept that specific fix but
want to keep track of the issue.

If you want to implement or start working in a new feature, please
open a **question** / **discussion** issue for it. No pull-request
will be accepted without previous chat about the changes,
independently if it is a new feature, already planned feature or small
quick win.

If you're new to Git, we recommended [this guide](https://docs.github.com/en/get-started/quickstart/contributing-to-projects) by Github.

Follow that guide up to the end of the [Creating a branch to work on](https://docs.github.com/en/get-started/quickstart/contributing-to-projects#creating-a-branch-to-work-on) section, 
then check out the below content. Once you're finished making your changes, 
see the rest of the guide for how to commit and pull-request them.

Here are a few things you can do that will increase the likelihood of your pull request being accepted:

- Follow standards for style and code quality.
- Write tests.
- Keep your change as focused as possible. If there are multiple changes you would like to make that are not dependent upon each other, consider submitting them as separate pull requests.
- Write a [good commit message][conventionalcommits].

## <a name="dco"></a> Developer's Certificate of Origin (DCO)

The sign-off is a simple line at the end of the explanation for the patch. Your
signature certifies that you wrote the patch or otherwise have the right to pass
it on as an open-source patch. The rules are pretty simple: if you can certify
the below (from [developercertificate.org](http://developercertificate.org/)):

    Developer's Certificate of Origin 1.1

    By making a contribution to this project, I certify that:
    
    (a) The contribution was created in whole or in part by me and I
        have the right to submit it under the open source license
        indicated in the file; or
    
    (b) The contribution is based upon previous work that, to the best
        of my knowledge, is covered under an appropriate open source
        license and I have the right under that license to submit that
        work with modifications, whether created in whole or in part
        by me, under the same open source license (unless I am
        permitted to submit under a different license), as indicated
        in the file; or
    
    (c) The contribution was provided directly to me by some other
        person who certified (a), (b) or (c) and I have not modified
        it.
    
    (d) I understand and agree that this project and the contribution
        are public and that a record of the contribution (including all
        personal information I submit with it, including my sign-off) is
        maintained indefinitely and may be redistributed consistent with
        this project or the open source license(s) involved.

Then, all your code patches (**documentation are excluded**) should
contain a sign-off at the end of the patch/commit description body. If 
you set your `user.name` and `user.email` git configs, you can sign your
commit automatically with `git commit -s`.

This is an example of the aspect of the line:

	Signed-off-by: Your Name <your@email.example.org>

Please, use your real name (sorry, no pseudonyms or anonymous
contributions are allowed).

## <a name="resources"></a> Resources

- [How to Contribute to Open Source](https://opensource.guide/how-to-contribute/)
- [Contributing to projects](https://docs.github.com/en/get-started/quickstart/contributing-to-projects)
- [Using Pull Requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
- [GitHub Support](https://support.github.com/)

[github]: ./
[coc]: ./CODE_OF_CONDUCT.md
[conventionalcommits]: ./CONVENTIONAL_COMMITS.md
[new-issue-templates]: ./issues/new/choose
