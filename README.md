# Starting


# Showing list
```
dotnet new list
```
# Make a Project Such as
```
 dotnet new console --name helloworld
```
helloworld.csproj
```
using System;

namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello, World!");
        }
    }
}
```
Director this folder
```
cd helloworld
```
# Build this project
```
 dotnet build helloworld.csproj
```
# Director the bin folder
```
 cd  bin\Debug\net10.0
```
# Run .exe file
```
.\helloworld.exe
```
