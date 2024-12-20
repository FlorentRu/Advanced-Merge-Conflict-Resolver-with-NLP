# Advanced-Merge-Conflict-Resolver-with-NLP

This project is an NLP-powered tool for resolving merge conflicts in software development. By recording changes and leveraging natural language processing (NLP), the tool identifies, tags, and suggests resolutions for conflicts, reducing the manual effort required during the merging process.

## Key Features

- Change Recording: Logs changes to code in real time for precise tracking.
- NLP-Based Comparison: Uses advanced NLP algorithms to identify similarities and differences between conflicting files.
- Conflict Tagging: Tags changes as SIGNIFICANT, MINOR, or NEW ADDITION for better clarity.
- Automation-Friendly: Works seamlessly with Git repositories, IDEs, and CI/CD pipelines.
- Google Colab Support: Designed to run efficiently on Google Colab, with file upload/download functionality.

## Demo Workflow

1- Upload Files: Upload base_code.txt (main branch code) and conflict_code.txt (conflicting branch code) through the Colab interface.
2- Tag Changes: The script uses NLP to analyze changes and assign tags based on the severity and type of conflict.
3- Download Results: Outputs a tagged file (resolved_tags.txt) with clear annotations for each line of conflicting code.

## File Structure
### bash
#### Copy code
#### merge-conflict-resolver/

│

├── README.md               # Project documentation

├── merge_resolver.py       # Main Python script for local execution

├── requirements.txt        # Python dependencies

├── base_code.txt           # Example base code file

├── conflict_code.txt       # Example conflicting code file

