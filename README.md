# TodoApi
TodoApi is a web service created in .NET Core 2.1, PostgreSQL 10 &amp; Visual Studio Code on macOS

### Set up

1. Get the [Mac C# SDK](https://www.microsoft.com/net/download)
    (verify this by executing dotnet on your terminal - you should see output text)
2. Get [VSCode](https://code.visualstudio.com/)
3. Open VSCode and install the following extensions
  * C#
  * C# Extensions
  * C# XML Documentation Comments
  * Code Runner
4. Clone this repo with: 
    $ git clone git@github.com:laxmansahni/TodoApi.git
5. Open folder TodoApi in your VSCode editor
6. Install postgres (if you haven't got it already) with 
    $brew install postgresql and start with
    $brew services start postgresql
7. Run the sql migration scripts with:
    dotnet ef database update    
8. Run your server with: 
    dotnet run
    (verify this by hitting http://localhost:5000)


