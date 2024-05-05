# Cryorithm™ | Style | Documentation

This page provides style guidelines for organizing and maintaining the documentation repository
of our GitHub organization, Cryorithm™. Our approach involves creating a directory for each
documentation page, which not only contains the markdown file but also any related assets. This
structure ensures that all relevant materials are grouped together and easily accessible, while
GitHub's automatic rendering of `README.md` files simplifies navigation and presentation.

## Directory Structure

Each new documentation topic should have its own directory under the `docs` directory. The name
of the directory should clearly reflect the topic or content it represents. This helps in
maintaining a clean and organized repository, making it easier for team members to find and
refer to different documentation sections.

## Naming Conventions

- **Directories**: Names should be concise yet descriptive. Use hyphens to separate words (e.g.,
  `user-guide`, `installation-instructions`).
- **Files**: Each directory should contain a `README.md` file. This file will automatically be
  rendered by GitHub when navigating to the directory, serving as the main document for the topic.

## Documentation File (README.md)

The `README.md` file serves as the central document within each directory. It should
comprehensively cover the topic of the directory, including text, images, links, and other
necessary documentation components.

### H1 Headers

For the main header (H1) of each `README.md` file, adopt a structured hierarchical format that
reflects the organization of the documentation. This format should include the organization name,
followed by the broader documentation category, and then the specific topic:

```
# Cryorithm | [Category] | [Specific Topic]
```

#### Examples:

- `# Cryorithm™ | User Guides | Installation`
- `# Cryorithm™ | API Documentation | Authentication`

## Including Assets

Within each documentation folder:
- Create a subdirectory named `assets`.
- Store images, diagrams or other relevant files here.
- Reference these using relative links in your READMEs to keep everything organized.

### Example of Asset Inclusion:

```markdown
![Setup Instructions](assets/setup.png)
```

## Note on Trademark Usage

The trademark symbol (™) is appended after "Cryorithm" at its first occurrence in major sections
to emphasize brand identity^1.

^1 In less formal communications within GitHub repos (e.g., issues discussions), its use can be
minimized unless legally advised otherwise.

## Depth Limitation in Indexing

Maintain index depth no more than two levels deep:
- Content deeper than two levels must be documented further within those respective
  directories/documents rather than expanded at higher levels.
