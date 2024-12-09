<a href="https://bluefrogracing.com/">
    <img src="https://bfr-leap.github.io/artas-sysdoc/icons/ldata-rulebooks.webp" alt="mascot-icon" title="ldata-rulebooks" align="right" height="60" />
</a>

# League Rule Books Repository

## Overview

The **League Rule Books Repository** is a centralized location for storing, maintaining, and distributing rule books for the various leagues covered by the LEAP system. These rule books provide a comprehensive set of guidelines, ensuring fair play, consistency, and clarity across all league events and competitions.

This repository is designed to serve league organizers, participants, and developers by offering easy access to standardized rule documentation in a structured and user-friendly format.

## Repository Structure

The repository is organized as follows:

- **`regulations/`**
  - This directory contains subdirectories for each league, identified by their unique `league_id` (a large number).
  - Each league directory includes:
    - **`default.md`**: The default rulebook to follow for seasons without a specific rulebook.
    - Subdirectories for specific seasons, identified by their unique `season_id` (a large number), containing:
      - **`regulations.md`**: The rulebook for the specific season.
      - Supporting media files (e.g., images, diagrams) stored within the season directory or its subdirectories.

### Example Structure:
```
regulations/
├── 123456789/  # league_id
│   ├── default.md
│   ├── 20230101/  # season_id
│   │   ├── regulations.md
│   │   ├── media/
│   │       ├── diagram.png
│   │       ├── logo.jpg
```

## Purpose

This repository serves the following goals:

1. **Centralized Rule Management:** Maintain a single source of truth for league rules.
2. **Consistency:** Promote uniformity across leagues by providing standardized documentation.
3. **Transparency:** Ensure participants and organizers have clear, easy access to all applicable rules.
4. **Version Control:** Track changes to rule books over time to ensure accountability and historical reference.

## Contribution Guidelines

Contributors are encouraged to follow these guidelines:

1. **File Naming:**
   - Use descriptive, kebab-case names (e.g., `default.md`, `regulations.md`).
   - Organize files within their corresponding `league_id` and `season_id` directories.

2. **File Format:**
   - Use Markdown (`.md`) for text-based rule books.
   - Provide supporting media in appropriate formats (e.g., PNG, JPEG, SVG).

3. **Commit Messages:**
   - Use clear and descriptive commit messages (e.g., "Add default rulebook for League 123456789").

4. **Pull Requests:**
   - Submit pull requests with a detailed description of the changes and their rationale.

5. **Review Process:**
   - Ensure all updates are reviewed by relevant stakeholders before merging.

## Usage Examples

Here are a few examples of how this repository can be utilized:

1. **League Organizers:**
   - Draft and update rule books under the appropriate `league_id` and `season_id` directories.
   - Share finalized rule books with participants through LEAP's web interface or directly via the repository.

2. **Participants:**
   - Access the latest rules for their league and season directly from the repository or through LEAP's documentation system.

3. **Developers:**
   - Integrate rule books into the LEAP system for real-time reference during events.

## License

All rule books and templates in this repository are copyrighted by their original authors. Redistribution, adaptation, or use of these materials requires explicit permission from the copyright holders, unless explicitly stated otherwise within individual files. Supporting documentation and media should similarly adhere to these restrictions unless explicitly marked for public use.

## Contact

For questions, suggestions, or feedback, please contact the LEAP team or submit an issue via the GitHub repository's issue tracker.

