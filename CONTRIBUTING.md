# Contributing

Thank you for helping improve this sequence-to-function paper list.

## How to Add a Paper

1. Open `README.md`.
2. Choose the most relevant section:
   - `S2F-For-Plant`
   - `S2F-Review`
   - `S2F-OneHot-Model`
   - `S2F-Other-Model`
   - `S2F-Model-Interpretation`
   - `S2F-Application`
3. Add the paper in reverse chronological order within that section.
4. Use the same table format as the existing entries.

## Paper Entry Format

Use this format for regular paper sections:

```md
| Year | Paper | Venue | Note |
| --- | --- | --- | --- |
| 2025 | [Paper Title](https://doi.org/...) | Journal or Conference | One concise sentence describing the contribution. |
```

For `S2F-OneHot-Model` and `S2F-Other-Model`, use the list format already shown in `README.md`:

```md
- **[Paper Title](https://doi.org/...)** - 2025, Venue
  - One concise sentence describing the contribution.
  <details>
  <summary>Series description</summary>

  **Series:** Input -> model -> output

  One short description of the sequence-to-function modeling task.

  </details>
```

## Plant Model Details

If you add or update plant model metadata, edit `S2F_Plant_Model_Details.md` directly. Keep the table compact and GitHub-readable.

Recommended fields:

```md
| Year | Model | Purpose | Object | Input | Encoding | Architecture | Output | Web | Type | Reference |
```

## Requirements

- Add papers that are directly relevant to sequence-to-function modeling or applications.
- Prefer DOI, publisher, PubMed, arXiv, bioRxiv, or official project links.
- Keep descriptions factual and concise.
- Avoid duplicate entries across sections unless the paper clearly belongs in more than one role.
- Do not commit raw bibliography exports or local working tables such as `.csv` or `.txt` files.

## Description Guidelines

A good note should answer one of these questions:

- What sequence input is modeled?
- What function, phenotype, activity, or molecular property is predicted?
- What model or method is introduced?
- What biological application does the paper enable?

Keep notes to one sentence when possible.

## Pull Request Title

Use a clear title such as:

```text
Add paper: Paper Title
Update section: S2F-For-Plant
Fix metadata: S2F_Plant_Model_Details
```

## Before Submitting

- Check that Markdown tables render correctly on GitHub.
- Check that links resolve.
- Check that `.csv` and `.txt` files are not included in the commit.
- Keep unrelated formatting changes out of the pull request.
