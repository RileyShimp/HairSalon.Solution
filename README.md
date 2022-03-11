# Hair Salon

#### [Riley Shimp](https://www.github.com/rileyshimp)

## Technologies Used

* C#
* .NET
* CSS
* Bootstrap
* MySQL
* Razor View Engine
* EntityCore
* VSCode

## Description

This is an MVC web application built with C# to help a hair salon manage employees (stylists) and their clients. Users are able to add a list of stylists working at the salon, and for each stylist, add clients who see that stylist. Select a stylist, see their details, and see a list of all clients that belong to that stylist. Users are not able to add a client if no stylists have been added.

## Setup/Installation Requirements

### Step 1
Clone the repository:
``` 
$ git clone https://github.com/RileyShimp/HairSalon.Solution.git 
```
### Step 2
First we'll install .NET, which provides access to the C# language. Follow along with instructions for your operating system provided in the following link: 
https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-c-and-net

### Step 3
Now .NET and C# should be installed and your computer should recognize the `dotnet` command.
Navigate to the `HairSalon.Solution` directory in your computer terminal and then to the `HairSalon` folder.

### Step 4
Create a `appsettings.json` file in the `HairSalon` directory and add the following code, replacing words in brackets accordingly.

```
{
  "ConnectionStrings": {
      "DefaultConnection": "Server=localhost;Port=3306;database=riley_shimp;uid=[USERNAME];pwd=[YOUR-PASSWORD-HERE];"
  }
}

```


## Known Bugs

* none

## License

[MIT](https://opensource.org/licenses/MIT)

Copyright (c) 02/25/2022 Riley Shimp