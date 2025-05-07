# Contributing to Everything Backend Engineering Core Concepts Q/A Bank

Thank you for your interest in contributing to **Everything Backend Engineering Core Concepts Q/A Bank**!

This project thrives on community contributions, and we welcome your help in making it a valuable resource for junior backend engineers. Whether you’re adding new questions, improving answers, or providing code samples, your efforts make a difference.

## 📋 How to Contribute

Follow these steps to contribute:

1. **Check Existing Issues**:

   - Browse the [GitHub Issues](https://github.com/wendeee/everything-backend-qa-bank/issues) to see if your idea or question is already being discussed.
   - If not, open a new issue to propose a question, suggest improvements, or report errors.

2. **Fork the Repository**:

   - Fork the repository to your GitHub account.
   - Clone your fork locally: `git clone https://github.com/wendeee/everything-backend-qa-bank.git`

3. **Create a Branch**:

   - Create a new branch for your changes (e.g., `git checkout -b feature/add-http-question`)
   - Use descriptive branch names (e.g., `fix/auth-answer`, `add/microservices-question`).

4. **Add or Update Content**:

   - Follow the repository structure and guidelines below to add questions, answers, or code samples.
   - Place new questions in the appropriate topic directory (e.g., `/questions/networking/http`).
   - Ensure code samples are in the `code/` subdirectory, named by language (e.g., `node.js`, `python.py`).

5. **Test Your Changes**:

   - Verify that markdown files are readable and code samples are correct.
   <!-- - If possible, run the validation script: `node scripts/validate-questions.js` (once implemented). -->

6. **Commit and Push**:

   - Write clear commit messages ( e.g., `git commit -m "Add question on HTTP statelessness with Node.js example"`)
   - Push your branch: `git push origin feature/add-http-question`

7. **Submit a Pull Request**:
   - Open a pull request (PR) against the `main` branch of the original repository.
   - Describe your changes in the PR description, linking to the relevant issue if applicable.
   - A maintainer will review your PR, provide feedback, and merge it once approved.

## 📝 Question and Answer Guidelines

To ensure consistency and quality, please follow these guidelines when adding or updating questions:

### Question Format (`question-answer.md`)

Use this template for each `question-answer.md` file:

```markdown
# [Question Title]

## Question

[State the question clearly, e.g., "How does the HTTP protocol handle statelessness, and how does this impact backend design?"]

## Answer

[Provide a concise, beginner-friendly explanation, 200-500 words. Cover key concepts, practical implications, and examples.]

## Example

[If applicable, reference code samples in the `code/` directory, e.g., "See `code/node.js` for a token-based authentication example."]

## Follow-Up Questions

- [List 1-3 potential follow-up questions interviewers might ask, e.g., "How would you handle session management in a high-traffic application?"]

## References

- [Link to official documentation, articles, or resources, e.g., "MDN: HTTP Protocol"]
```
