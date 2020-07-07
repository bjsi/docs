## ${TEMPLATE} Plugin for SuperMemoAssistant

### Features

-
-
- Extensible? Link to the extensibility section of the Manual

### Installation

#### SMA Web (Recommended)
- TBA

#### Manual Installation

##### Prerequisites

- Install Visual Studio 2019 or higher.
- Select the following  VS **components**  during the install:
+ .NET desktop development
+  .NET Core cross-platform development

##### Step-by-step Guide

1. Clone the project.
`git clone ...`
2. Open the cloned project folder.
3. Double click on the solution (.sln extension) file to open the project in Visual Studio 2019.
4. Right click on the solution in the solution
5. Check that the build succeeded by checking the following folder for the built project files:
`C:\Users\<YOUR USERNAME>\SuperMemoAssistant\Plugins\Development`
6. Close Visual Studio and run SuperMemoAssistant.

### Manual

#### Usage

#### Configuration

##### Settings

> You can access the settings of any SuperMemoAssistant plugin by pressing Ctrl+Alt+Shift+O and clicking the gear icon.
-
-
-

#### Extensibility

> ${TEMPLATE} Plugin leverages the power of SuperMemoAssistant's *Plugin Service Architecture* to easily support plugin extensions.

### Contributing Guide

#### Issues and Suggestions

See the contribution guide for information on how to report issues or make suggestions.

#### Code Contributions

Pull requests are welcome!

1. Firstly, go through the manual installation guide above.
2. You will also require [Git Hooks for VS](https://marketplace.visualstudio.com/items?itemName=AlexisIncogito.VisualStudio-Git-Hooks) which is used to enforce a consistent code style.
> Note: you do not need to build the entire SuperMemoAssistant project to make changes to or debug a plugin.
3. See the code contribution guide here for pull request instructions.
4. If you need help, don't hesitate to get in touch with me (Jamesb) on the SMA discord channel.
