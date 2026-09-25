# GitHub Publish Instructions

The portfolio has been prepared locally, but the current machine is authenticated to GitHub as a different account. To publish this repository, sign in as the repository owner and push the prepared `main` branch.

## Target Repository

https://github.com/khalilsaeed2040-spec/Android_Development_Lab

## Option 1 - GitHub Desktop

1. Open GitHub Desktop.
2. Sign in as the owner of `khalilsaeed2040-spec/Android_Development_Lab`.
3. Add the local repository folder:

```text
C:\Users\Admin\Documents\Codex\2026-09-26\new-chat\work\Android_Development_Lab
```

4. Publish or push the `main` branch to:

```text
https://github.com/khalilsaeed2040-spec/Android_Development_Lab
```

## Option 2 - Command Line

Run these commands after signing in with the correct GitHub account:

```powershell
cd C:\Users\Admin\Documents\Codex\2026-09-26\new-chat\work\Android_Development_Lab
git push -u origin main
```

If Git asks for login details, use the GitHub account that owns the repository.

## Option 3 - Upload ZIP Through GitHub Web

If command-line pushing is not available:

1. Open the prepared package:

```text
C:\Users\Admin\Documents\Codex\2026-09-26\new-chat\outputs\Android_Development_Lab_portfolio_package.zip
```

2. Extract it.
3. Open the GitHub repository in the browser.
4. Use **Add file > Upload files**.
5. Upload the extracted contents.

This option is easier but does not preserve the prepared local commit history.

## Important Before Final Submission

- Add the Android Developer profile URL.
- Add completed Android Studio source-code projects in each `Source-Code` folder.
- Replace analysis and reflection templates with the student's own writing.
- Decide whether student name and ID should be public in the repository README.

