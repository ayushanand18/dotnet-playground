# A .Net Apps Playground
```
    .Net 6.0
--------------------
SDK Version: 6.0.404
```
## Directory Information
directory|description
---------|-------------------
`MyApp`  | A .Net console app
`WebApp` | A .Net Blazor App

## Installation Steps
1. To install .Net on Ubuntu follow the steps
    ```sh
    sudo apt-get https://packages.microsoft.com/config/ubuntu/<version>/packages-microsoft-prod.deb 
    # replace <version> with your version, e.g. 20.04
    sudo dpkg -i packages-microsoft-prod.deb # depackage the binary
    rm packages-microsoft-prod.deb # remove since we no longer need it
    sudo apt-get update # update to apply the changes
    sudo apt-get install -y dotnet-sdk-6.0 
    # you can also install 7.0 but 6.0 is more supported on linux at the moment
    ```
    and you are done!
2. You can also check your installation by running
    ```sh
    dotnet
    ```
    or list all SDKs
    ```sh
    dotnet --list-sdks
    ```
    or list all runtimes
    ```sh
    dotnet --list-runtimes
    ```
## Courses
1. [A good course on C# by Microsoft Learn](https://learn.microsoft.com/en-us/users/dotnet/collections/yz26f8y64n7k07)
2. [A good course on .NET for IoT on LinkedIn Learning](https://www.linkedin.com/learning/introduction-to-iot-with-dot-net-core/intro-to-iot-with-dot-net-core?autoplay=true)

Made with ❤️ by Ayush!
