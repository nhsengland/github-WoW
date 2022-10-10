# Recommendations for Github repositories

Here is a list of recommended content to include for project repositories to enable best practice and contributions.

### Changelog
A markdown file in your repository that tracks noteable changes to the code.  Recommendation is to use [semantic versioning](https://semver.org/spec/v2.0.0.html) which reflects `Breaking changes`, `New features`, and
`Fixes` clearly. 

### Contributing file
A piece of text that encourages contributions in the forms of raising new issues and submitting pull requests.  Include reference to the code of conduct and any guidance about branching strategy or style of commit messages to help contributions be made is a standardised way. 

### .gitignore
A file which lists any local file types that should be ignored when a push is made from a local clone back to Github.  This helps protect data files and large outputs from being accidentally uploaded but shouldn't be relied on as the only protection.

### model card
When your code contains a piece of code which someone else may use or reproduce then it's best to make clear the intended use for the code and any known limitations.  One way to do this is to use a model card stating:
- model details 
- Intended use
- Out-of-scope usage
- Training data
- Performance and Limitations
- Notes to the user

### templates for pull requests
to support contributions being submitted in a standardised form you can include a pull request template for fixes and new features.  This will then help contributors know what information to include to support these requests. 
