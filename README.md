```csharp
public class Ensar : SoftwareDeveloper
{
    public string Name => "Ensar";
    public string Username => "ensarce";

    public string Role => "Full-Stack Developer";

    public string[] Interests =>
        new[]
        {
            "Web Development",
            "Mobile Applications",
            "Clean Architecture",
            "RESTful APIs"
        };

    public string[] TechStack =>
        new[]
        {
            "Angular",
            "Java",
            "C#",
            ".NET",
            "SQL",
            "Docker"
        };

    public void CurrentStatus()
    {
        Console.WriteLine("🌱 Currently developing web applications with Angular & Java.");
        Console.WriteLine("🧠 Focusing on clean code and scalable architectures.");
        Console.WriteLine("💞️ Open to collaboration on Angular, .NET and Java projects.");
    }

    public string Contact()
    {
        return "📩 GitHub: github.com/ensarce | LinkedIn: [Your LinkedIn]";
    }
}

```


