# BaseRepo
A cookie cutter base repo

# Folder Structure

|Folders  |Description  |
|---------|---------|
|/src     |    Source code      |
|/docs    |    Documentation     |
|/tests   |    Test cases      |
|/config  |    Configuration files     |
|/build   |    Build scripts or outputs       |
|/scripts |    Automation scripts (deploy, etc.)    |
|/thirdparty |    Third-party libraries and dependencies    |
|/.github/workflows    |    store GitHub Actions workflow configuration files    |

# Files


|FileName  |Description  |
|---------|---------|
|.env     |    For environment variables. [SHOULD NOT TO BE IN VCS]     |
|LICENSE     |  Legal information about how others can use your project.       |
|Readme.md     |  The first file developers and users see—describe your project, installation steps, and usage.       |
|.gitignore    | Prevent sensitive or unnecessary files from being committed to version control.|



# Best Practices
Language-Agnostic Design:

Follow the principles of modularity, separation of concerns, and scalability.
Document Everything:

Always include a README.md for the repository and README.md files in major subfolders for context.
Version Control:

Use .gitignore to exclude unnecessary files 

Environment-Specific Configs:
Use .env or environment-specific files for sensitive data.