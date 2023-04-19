# Getting Started.

Hey there! Welcome to the community! While it may seem daunting to get started, especially if you're new to coding or contributing to open-source, don't worry! We understand that learning new technologies and collaborating with others can be a challenge, but it's also an incredibly rewarding experience that can benefit you in many ways.

Even though it might be tough to jump in at first, remember that you're not alone in this journey. With some effort and a positive attitude, you'll soon find yourself thriving in this exciting and welcoming community. So come on in, join the fun, and let's create something amazing together!
## A beginner's guide on how to contribute.

1. Go to the ```'Start-here.md'``` file in this directory for a brief introduction to open source and its significance

2. Click the ```'Fork'``` button on the [GitHub page of this repository](https://github.com/Open-Source-Africa/getting-started-guide).

![Fork project](assets/screenshots/fork-project.png)

3. Create a local copy of your forked repository by ```cloning``` it to your computer.

![Clone project](assets/screenshots/clone-project.png)

For example, enter this command in your terminal:

```bash
git clone https://github.com/<your-github-username>/getting-started-guide.git
```
**Note:** Change ``<your-github-username>``

>Find out additional information on [how to fork](https://help.github.com/en/github/getting-started-with-github/fork-a-repo) and [cloning a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

4. Navigate to the project directory:

```bash
   cd getting-started-guide
   ```
5. To prevent merge conflicts, synchronize your fork before making any modifications:

```bash
git remote add upstream https://github.com/Open-Source-Africa/getting-started-guide.git
git pull upstream main
```
6. Once you've added the upstream and verified that all files are current, the next step is to create a new branch before making any changes. There are two methods to do this:

```bash
git checkout -b <branch-name>
```

```bash
git branch <branch-name>
git switch <branch-name>
```

7. Open the ``Contributors.md`` file in your text editor and include your name in the document.

> **IMPORTANT NOTE:** Include your name somewhere in the middle of the file to reduce the risk of encountering a merge conflict, rather than at the beginning or end.

> It is important to refrain from editing or deleting other individuals from the list, even if it's to correct their formatting, as this can impede the merging of your pull request.

8. Use ``git add`` and ``git commit`` (with a clear commit message, if feasible) to include the modifications:

```bash
git add Contributors.md
git commit -m "Add <your-github-username>"
```
9. Push your changes to your repository:
```bash
git push origin <branch-name>
```

10. Navigate to the GitHub page of your fork and create a pull request.

> Find additional information about pull requests on the [GitHub help documentation](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).


**Note:** This is a space for experimentation, and we promote taking risks and learning from failures. Utilize this environment as a platform for practice and relish collaborating with others on projects that you create together. A large number of folks have attained practical know-how on "teamwork" by participating in such initiatives.