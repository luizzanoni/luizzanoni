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
        var interesses = string.Join(", ", quemSouEu.Interesses);
        var motivacao = string.Join("\n", quemSouEu.Motivacao);
        var technologies = string.Join(" · ", quemSouEu.Technologies);

        Console.WriteLine(
            $"NomeCompleto: {quemSouEu.NomeCompleto}\n" +
            $"DataNascimento: {quemSouEu.DataNascimento:yyyy/MM/dd}\n" +
            $"Interesses: {interesses}\n" +
            $"Motivacao:\n{motivacao}\n" +
            $"Technologies:\n{technologies}"
        );
    }
    else
    {
        Console.WriteLine("Luiz não existe!");
    }
    return View(luizGustavo);
}

```
  
</div>
