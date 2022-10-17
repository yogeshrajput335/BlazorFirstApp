### List of DOTNET Framewoek
> dotnet --list-sdks
##### Ensure that a version that starts with 6 is listed. If none is listed or the command isn't found, install the most recent .NET 6.0 SDK.
[https://dotnet.microsoft.com/en-us/download]
###  Create a new Blazor app
> dotnet new blazorserver -f net6.0
##### If Visual Studio Code prompts you to install required assets, select Yes.
###  Run the app
> dotnet watch run

###  Modify a component
[Parameter]
###  Create the ToDo page
> dotnet new razorcomponent -n Todo -o Pages
```
     @page "/todo"
```

### REFRENCE
```
https://learn.microsoft.com/en-us/training/paths/build-web-apps-with-blazor/

```
> dotnet new gitignore
