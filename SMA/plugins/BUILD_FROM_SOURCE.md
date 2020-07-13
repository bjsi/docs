#### Building from source

##### Prerequisites

- Install Visual Studio 2019 or higher.
- Select the following  VS components during the install:
  + .NET desktop development
  + .NET Core cross-platform development

##### Guide

1. Clone the project using git.

  `git clone <repo url>`

2. Open the cloned project folder.

3. Double click on the solution (BetterDoubleClick.sln) to open the project in Visual Studio 2019.

4. Right click on the solution file in the **Solution Explorer**:

![Image of Solution Explorer](https://github.com/bjsi/docs/blob/master/SMA/plugins/images/solution-explorer.png)

5. Select **Build Solution**:

![Image of Build Solution Option](https://github.com/bjsi/docs/blob/master/SMA/plugins/images/build-solution.jpg)

6. Check that the build succeeded by confirming that the following folder exists and is not empty:

`C:\Users\<YOUR USERNAME>\SuperMemoAssistant\Plugins\Development`

7. Close Visual Studio and run SuperMemoAssistant.
