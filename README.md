# Blazor In VS CODE Documention
LINK https://medium.com/p/656f68a3384c
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

## How to Contribute

* Please read and follow the steps in [CONTRIBUTING.md](CONTRIBUTING.md) file.
* You may want to look out for issues labeled [good first issue] to find some initial tasks to tackle.
