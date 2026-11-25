# 05. Pull requests and reviews

## Create a pull request

To proceed with this step, the first thing we need to do is to create/add a new file since we are currently in the newly generated branch. Let's follow these steps:

1. In the **< > Code** tab, located in the repository's header menu, make sure that we are on the branch we named dev in this example.

2. Next, click on the "Add file" dropdown menu and select the option "Create new file".
<br>

![Create a new file](../../images/crear-nuevo-archivo.jpg)
3. In the new view, you will see an empty field with a placeholder text saying "Name your file...". This indicates that we should provide a name for the file. Let's name it `LICENSE.md`.


**Note**: `.md` is a file extension that creates a [Markdown](https://docs.github.com/en/get-started/quickstart/github-glossary#markdown) file. For more information about Markdown, visit [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) in the GitHub documentation or take the [Communicate using Markdown](https://github.com/skills/communicate-using-markdown) course.

<br>

[Licence-template](../../images/licencia-plantilla.jpg)

```
Copyright Notice.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to operate with the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT, OR OTHERWISE, ARISING FROM, OUT OF, OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
<br>

![licence-text](../../images/licencia-texto.jpg)

5. Next, click on the **Commit changes** button. Similar to the previous step where we created the `README` file, a popup window will appear asking for a brief commit message that describes the changes we made. Remember that this message helps others understand what we are adding in our commit. While GitHub provides a default simple message, let's customize it a bit for practice.

<br>
First, in the title, let's write: "Add LICENSE.md file". In the extended description, let's enter: "Create a License file in markdown format that expresses the copyright notice."

6. Last, now we confirm the changes by clicking on the **Commit changes** button.

![licencia commit](../../images/licencia-commit.jpg)

Great! You're already mastering the process of making commits. Isn't it straightforward?

Now that you have committed a change on the `dev` branch, open a pull request: select **Compare & pull request** if it appears, or go to **Pull requests** > **New pull request**. Set **base** to `main` and **compare** to `dev`, add a title and description, and select **Create pull request**. If you created an issue in the previous lesson, include `Closes #<number>` in the description to link it.

## Review a pull request

Reviewing changes gives people a chance to discuss them before they are added to the project. With the pull request open, ask another person to review it before merging.

### Activity: review the changes

1. Ask another person with at least read access to the repository to review your pull request and open the **Files changed** tab.
2. They can comment on a specific line or select **Review changes** and submit a review as **Comment**, **Approve**, or **Request changes**.
3. Read and respond to comments. If changes are requested, push them to the same branch, then ask for another review.
4. Once the review is resolved, continue to the next lesson to learn how to merge the pull request. If its description includes `Closes #<number>`, the linked issue will close when it is merged into the default branch.

You cannot review your own pull request. If you are learning on your own, you can explore the **Conversation** and **Files changed** tabs, but you will need another person with at least read access to practice a review.

See GitHub's guide to [pull request reviews](https://docs.github.com/en/pull-requests/reference/pull-request-reviews).

---

[Back to course index](README.md)
