# 💙  Some informations about me

```cs
public class Czz
{
    public static Tuple<string, string, string> Contact()
    {
        string Discord = "fn2913";
        string Telegram = "t.me/betterczz";
        string Website = "GoSec.me";

        return new Tuple<string, string, string>(Discord, Telegram, Website);
    }

    public static Tuple<string, List<string>, int, string> Me()
    {
        string Name = "S...";
        List<string> Speak = new List<string> { "French", "Arabic", "Spanish", "English" };
        int Age = 18;
        string Year = "2005";

        return new Tuple<string, List<string>, int, string>(Name, Speak, Age, Year);
    }

    public static Tuple<Dictionary<string, List<string>>, List<string>, List<string>> Dev()
    {
        Dictionary<string, List<string>> Code = new Dictionary<string, List<string>>
        {
            { "Pro", new List<string> { "Golang", "Python", "C#", "Lua", "JavaScript" } },
            { "Medium", new List<string> { "C", "C++" } }
        };

        List<string> Devs = new List<string> { "Backend", "Software", "Frontend (BAD)" };
        List<string> Editor = new List<string> { "VSCode", "Visual Studio", "CLion", "PyCharm", "IntelliJ Idea" };

        return new Tuple<Dictionary<string, List<string>>, List<string>, List<string>>(Code, Devs, Editor);
    }
}
```


<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=golang,python,cs,lua,js" />
  </a>
</p>

<p align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=c,cpp" />
  </a>
</p>
