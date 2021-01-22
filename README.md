# Yoyo.ThemePicker

An Umbraco package that create a the theme picker property editor

## Contribution Guidelines

If you'd like to contribute to this package, you'll first want to get in install local. The following steps will help you get set up.

1. Clone the repo
2. Open the Visual Studio solution and restore the nuget packages. This will install a local version of Umbraco for you in the `Website` folder.
3. You will need to manually build the `Website` folder as it is excluded for the main build task.
4. You can run the test Umbraco site any way you wish, whether it's setting it up in IIS or running it via Visual Studio or VS Code.
5. On the install screen for Umbraco, I recommend using the starter theme to help get you started quicker.
6. You'll now want build the solutions, this will automatically copy the package into the correct location.
7. Go to settings in the Umbraco backoffice and create yourself a new `Theme picker` data type and use it where ever you would like to test it.

### Committing

Before you make your first commit, make sure you install the npm modules for this package by running `npm i`. This will configure some rules around commit messages that will help to keep things consistent.
