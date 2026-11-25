# Self-assessment: GitHub fundamentals

These are original questions for reviewing the course concepts. They are not official questions and do not represent a certification exam. Once a target certification is selected, each question can be mapped to its public objectives.

Try to answer before opening each explanation.

## Git and GitHub

### 1. Which statement best describes the relationship between Git and GitHub?

- A. Git is a website hosting platform, and GitHub is a file format.
- B. Git is a version control system; GitHub is a platform for hosting Git repositories and collaborating.
- C. Git and GitHub are two names for the same application.

<details>
<summary>Show answer and explanation</summary>

**Answer: B.** Git records and manages change history. GitHub provides services for hosting Git repositories and collaborating on them.

</details>

## Repositories, commits, and branches

### 2. What does a repository usually contain?

- A. Project files and their change history.
- B. Only the latest version of each file, without history.
- C. Pull requests only.

<details>
<summary>Show answer and explanation</summary>

**Answer: A.** A repository contains project files and the history of changes tracked by Git.

</details>

### 3. What is the purpose of creating a branch?

- A. To work on changes in isolation before proposing them to another branch.
- B. To erase the history of the default branch.
- C. To turn an issue into a file.

<details>
<summary>Show answer and explanation</summary>

**Answer: A.** A branch lets you develop changes without directly modifying the target branch, such as `main`.

</details>

### 4. What does a commit represent?

- A. A conversation about a task.
- B. A recorded set of changes in the repository history.
- C. An independent copy of the repository under another account.

<details>
<summary>Show answer and explanation</summary>

**Answer: B.** A commit saves changes in Git history and usually includes a message describing them.

</details>

## Issues and pull requests

### 5. When should you create an issue?

- A. To document or discuss a task, problem, or improvement.
- B. To automatically merge a branch.
- C. To save a project version without history.

<details>
<summary>Show answer and explanation</summary>

**Answer: A.** Issues help organize work and discuss problems or proposals; they do not change files by themselves.

</details>

### 6. What does a pull request let you do?

- A. Propose changes from a branch for review and discussion before integrating them.
- B. Change the password of every collaborator.
- C. Create a local copy of the repository in a browser.

<details>
<summary>Show answer and explanation</summary>

**Answer: A.** A pull request compares changes between branches and supports review and discussion before merging them.

</details>

### 7. What does selecting **Request changes** in a review mean?

- A. The reviewer is asking for changes before the pull request is integrated.
- B. The pull request is merged immediately.
- C. The related issue is deleted.

<details>
<summary>Show answer and explanation</summary>

**Answer: A.** The review communicates that changes are expected before approval. The author can respond and push commits to the same branch.

</details>

### 8. What does `Closes #12` in a pull request description do?

- A. It closes the issue when the pull request is merged into the default branch.
- B. It closes the repository to new contributions.
- C. It automatically creates a branch named `12`.

<details>
<summary>Show answer and explanation</summary>

**Answer: A.** Keywords such as `Closes` link a pull request to an issue and close it when the change is merged into the default branch.

</details>

## Merging changes

### 9. What happens when a pull request is merged?

- A. The proposed changes are integrated into the target branch.
- B. All repository history is deleted.
- C. The repository is converted into an issue.

<details>
<summary>Show answer and explanation</summary>

**Answer: A.** Merging integrates changes from the source branch into the target branch. The merge method can vary depending on repository settings.

</details>

### 10. Who can submit a formal review of your pull request?

- A. The author must approve their own pull request.
- B. Another person with at least read access to the repository.
- C. Any visitor, regardless of permissions.

<details>
<summary>Show answer and explanation</summary>

**Answer: B.** Anyone with read access can review and comment on the proposed changes. The pull request author cannot review their own pull request.

</details>

---

[Back to course index](README.md)
