# Cryorithm™ | Documentation

- [Legal](legal) _(Placeholder)_
- [Milestones](milestones)
- [Organization](organization)

## Style

This section provides style guidelines for organizing and maintaining the documentation
repository of our GitHub organization, Cryorithm™. Our approach involves creating a
directory for each documentation page, which not only contains the markdown file
but also any related assets. This structure ensures that all relevant materials are
grouped together and easily accessible, while GitHub's automatic rendering of
`README.md` files simplifies navigation and presentation.

### Directory Structure

Each new documentation topic should have its own directory under the `docs`
directory. The name of the directory should clearly reflect the topic or content
it represents. This helps in maintaining a clean and organized repository, making
it easier for team members to find and refer to different documentation sections.

### Naming Conventions

- **Directories**: Names should be concise yet descriptive. Use hyphens to separate
  words (e.g., `user-guide`, `installation-instructions`).
- **Files**: Each directory should contain a `README.md` file. This file will
  automatically be rendered by GitHub when navigating to the directory, serving as
  the main document for the topic.

### Documentation File (README.md)

The `README.md` file serves as the central document within each directory. It should
comprehensively cover the topic of the directory, including text, images, links, and
other necessary documentation components.

#### H1 Headers

For the main header (H1) of each `README.md` file, adopt a structured hierarchical
format that reflects the organization of the documentation. This format should
include the organization name, followed by the broader documentation category, and
then the specific topic. The structure should be:

```
# Cryorithm | [Category] | [Specific Topic]
```

##### Examples:

- `# Cryorithm™ | User Guides | Installation`
- `# Cryorithm™ | API Documentation | Authentication`

This structured approach to headers helps in maintaining a uniform appearance across
all documentation, making it easier for readers to understand the context and
hierarchy of the information presented.

### Including Assets

Within the directory of each topic, include a subdirectory named `assets` to store
images, diagrams, or other relevant files. Refer to these assets in your `README.md`
using relative links. This method keeps the main directory clean and ensures that all
related files are stored together with their respective documentation.

#### Example of Asset Inclusion

If you have an image `setup.png` in the `assets` folder within the
`installation-instructions` directory, you can include it in your `README.md` like
so:

```markdown
![Setup Instructions](assets/setup.png)
```

### Note on Trademark Usage

The trademark symbol (™) should appear after "Cryorithm" at its first occurrence in
major sections of documentation or public-facing materials where brand identity needs
emphasis^1.

^1 In other instances within continuous text bodies or informal communications within
GitHub repos (e.g., issues discussions), it's sufficient without repetitive use unless
legally advised otherwise.

### Summary

By following these guidelines, we can ensure that our documentation is not only
well-organized but also consistent and easy to navigate. This structured approach
allows team members and external users alike to quickly find the information they
need.
