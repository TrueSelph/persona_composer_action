# Persona Composer Action

![GitHub release (latest by date)](https://img.shields.io/github/v/release/TrueSelph/persona_composer_action)
![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/TrueSelph/persona_composer_action/test-action.yaml)
![GitHub issues](https://img.shields.io/github/issues/TrueSelph/persona_composer_action)
![GitHub pull requests](https://img.shields.io/github/issues-pr/TrueSelph/persona_composer_action)
![GitHub](https://img.shields.io/github/license/TrueSelph/persona_composer_action)

Generates and updates the persona interact action prompt and configurable attributes based on biodata.

## Package Information

- **Name:** `jivas/persona_composer_action`
- **Author:** [V75 Inc.](https://v75inc.com/)
- **Architype:** `PersonaComposerAction`

## Meta Information

- **Title:** Persona Composer Action
- **Group:** core
- **Type:** action

## Configuration

- **Singleton:** true

## Dependencies

- **Jivas:** `^2.0.0`
- **Actions:**
  - `jivas/langchain_model_action`: `^0.0.1`
  - `jivas/persona_interact_action`: `^0.0.1`

This package, developed by V75 Inc., is designed to generate and update prompts and configurable attributes for persona interact actions using user biodata. As a core action, it is essential for dynamically shaping and modifying persona attributes and responses based on user information. It is a singleton and requires the Jivas library version 2.0.0, along with dependencies on the `langchain_model_action` and `persona_interact_action`.

---

## How to Use

Below is detailed guidance on how to configure and use the Persona Composer Action.

### Overview

The Persona Composer Action provides an abstraction layer for dynamically generating and updating persona attributes and prompts based on biodata. It supports:

- **Customizable attributes** for persona configuration.
- **Integration** with Jivas actions for seamless persona updates.
- **Dynamic prompt generation** based on user-provided biodata.

---

### Configuration Structure

The configuration consists of the following components:

### `biodata` and `attributes`

Defines the biodata and attributes for the persona.

```python
biodata = "Brief description of the persona, including name, role, and temperament."
attributes = {
    "name": "John Doe",
    "role": "Software Engineer",
    "emotional_state": "happy",
    # Additional attributes...
}
```

---

### Example Configurations

### Basic Configuration for Persona

```python
biodata = "John is a software engineer with a calm and optimistic temperament."
attributes = {
    "name": "John",
    "role": "Engineer",
    "emotional_state": "optimistic",
    "strengths": "problem-solving, teamwork",
    "motivations": "learning new technologies",
}
```

### Best Practices
- Ensure biodata is concise and descriptive.
- Validate attributes to match the persona's intended characteristics.

---

## 🔰 Contributing

- **🐛 [Report Issues](https://github.com/TrueSelph/persona_composer_action/issues)**: Submit bugs found or log feature requests for the `persona_composer_action` project.
- **💡 [Submit Pull Requests](https://github.com/TrueSelph/persona_composer_action/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your GitHub account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/TrueSelph/persona_composer_action
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to GitHub**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details open>
<summary>Contributor Graph</summary>
<br>
<p align="left">
    <a href="https://github.com/TrueSelph/persona_composer_action/graphs/contributors">
        <img src="https://contrib.rocks/image?repo=TrueSelph/persona_composer_action" />
   </a>
</p>
</details>

## 🎗 License

This project is protected under the Apache License 2.0. See [LICENSE](./LICENSE) for more information.