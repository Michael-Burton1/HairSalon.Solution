# Clair's Hair Salon

#### By Michael Burton

#### This application allows user to input Clients and Employees in the browser. The  user can then  navigate pages for Clients and Employees to view details about both. along with having full CRUD funtionallity to update the database.

## Technologies Used

* VS Code
* C#
* MS Test
* .NET 5 SDK framwork
* Razor
* MySql


### Prerequisites

* .NET 5 SDK
* A text editor like VS Code
* A command line interface like Terminal or GitBash to run and interact with the console app.
[MySQL Community Server](https://dev.mysql.com/downloads/file/?id=484914)

### Installation

1. Clone this repository: $ git clone https://github.com/Michael-Burton1/HairSalon.Solution.git
2. Navigate to the HairSalon.solution directory on your computer
3. Open with your preferred text editor to view the code 
4. Set up Sql Database using MySQL:
    * Make an appsettings.json file in the HairSalon directory of the project.
    * Add this to your Appsettings.json file


  {
  "ConnectionStrings": {
    "DefaultConnection": "Server=localhost;Port=3306;database=michael_burton;uid=root;pwd=[YOUR PASSWORD];"
    }
  }

* replace [YOUR PASSWORD] with your MySQL password
Open terminal and run this command with your MySQL password replacing [YOUR PASSWORD] : mysql -uroot -p[YOUR PASSWORD]
* Then type in these commands
  * CREATE DATABASE michael_burton;
  * USE michael_burton;
  * CREATE TABLE {clients (ClientId INT, Name VARCHAR(255), PhoneNumber VARCHAR(255), Age INT, StylistId INT)}
  * CREATE TABLE {Stylist (StylistId INT, Name VARCHAR(255), Speciallity VARCHAR(255), PayRate DECIMAL(2)}
  * the two CREATE commands will create tables for Clients and Stylists


5. To run the app:
  * Navigate to the {HairSalon} directory in your command line
  * Run the command: dotnet restore  to restore the dependencies that are listed in {HairSalon.csproj}
  * Run the command: dotnet build   to build the project and its dependencies   
  * Finally, run the command: dotnet run   to run the project!
  


## Known Bugs

* No known bugs

## License

_Licensed under the [MIT License](LICENSE)._

## Contact Information

_Michael Burton (micbur1@gmail.com)_