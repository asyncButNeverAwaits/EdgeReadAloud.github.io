# Warning
Personal project. Use at your own risk, feature might break in future.

# Why
- Open a large-size text file (e.g. book) in Microsoft Edge and listening with Read Aloud is laggy.
- Finding out where I last left off is troublesome.

# Feature
- Save text file in browser IndexedDB
- Save read progress to github repository
- Autosave when Read Aloud stop reading
- Personalisation settings (theme, font size, scroll position)
- Save settings to github repository
- PWA, able to add as shortcut to your mobile

# Configuration
## Repository path
Create a new repository for progress and setting storage.

Paste your repository path, for example:

input `EdgeReadAloud/progress` for repository `https://github.com/EdgeReadAloud/progress`

Create `progress.json` and `setting.json` in the repository.

## Personal Access Token
Refer GitHub Doc: [Creating a fine-grained personal access token
](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token#creating-a-fine-grained-personal-access-token)

Repository access -> `Only select repositories` -> Select your repository for progress and setting storage

Permissions -> Repository permissions -> Contents -> Read and write

Overview should show
```
 Read access to metadata
 Read and Write access to code
```

Generate token and paste it.
