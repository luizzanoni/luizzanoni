## Hello, World! 👋

<div align="center">

<img src="https://user-images.githubusercontent.com/56282554/174655304-d35e92f9-d145-4041-ac20-faf4b8a7adf4.gif">

I'm a Software Developer at <a href="https://interfoc.com.br/" target="_blank">Interfoc Sistemas</a></p>

[![WebSite](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://luizzanoni.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luizgustavozanoni/)

<div align="left">

#### About me in C#
	
``` C#

public ActionResult LuizGustavoZanoni()
{
    var filtro = informacoesSobreMim();

    var luizGustavo = GI.S<LuizGustavoZanoni>()
        .Listar(false, s => s.Id == filtro)
        .Select(s => new
        {
            s.NomeCompleto,
            s.DataNascimento,
            s.Interesses,
            s.Motivacao,
            s.Technologies
        })
        .ToList();

    if (luizGustavo.Any())
    {
        var quemSouEu = luizGustavo.FirstOrDefault();
        Console.WriteLine(
            $"NomeCompleto: Luiz Gustavo Zanoni" +
            $"DataNascimento: 2000/01/27" +
            $"Interesses: music, games, language learning, trips, motorcycle" +
            $"Motivacao:\n" +
		$"{string.Join(
			"Discovering and coding new things"
			"Making life easier and smarter through technology"
			"Innovating and developing technological solutions to make the world a better place"
			"Contributing to society through the creation of intelligent applications and systems")} +
            $"Technologies:\n" +
            	$"{string.Join(
			SQL · GitFlow · PostgreSQL · API REST · Git · C# · HTML5 · CSS · JavaScript · .NET Framework);
    }
    else
    {
        Console.WriteLine("Luiz não existe!");
    }

    return View(luizGustavo);
}

```
  
</div>
