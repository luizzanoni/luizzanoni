## Hello, World! 👋

<div align="center" target="_blank">

<img src="https://user-images.githubusercontent.com/56282554/174655304-d35e92f9-d145-4041-ac20-faf4b8a7adf4.gif">

I'm a Software Developer at <a href="https://interfoc.com.br/">Interfoc Sistemas</a></p>

[![WebSite](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://luizzanoni.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luizgustavozanoni/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/luiz.gzanoni/)
[![Whats](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5549999241385)

<div align="left">

#### About me in C#
	
``` C#
public ActionResult LuizGustavoZanoni()
{
	var luizGustavo = GI.S<LuizGustavoZanoni>()
			    .Listar(false, s => s.Id == filtro)
			    .Select(s => new 
			    {
				    s.FullName, s.BirthDate, s.Pronouns, 
				    s.Interests, s.Motivations, s.Technologies
			    })
			    .ToList();
						
		if(luizGustavo.HasValue())
		{			
			var quemSouEu = luizGustavo;
				Console.WriteLine
				(
					FullName: 'Luiz Gustavo Zanoni',
					BirthDate: '2000-01-27' | '23 years',
					Pronouns: 'he' | 'him',
					Interests: 'music, games, language learning, trips, motorcycle',
					Motivation: 
					{
					    'Discover and code new things',
					    'Making life easier and smarter through tech',
					}
					Technologies:
					{
					    'HTML, CSS, dotNET, JavaScript, React, APIs, ASP.NET Core, MVC, jQuery'
					}
				)
		} else 
			Console.WriteLine("Luiz não existe!");

    return luizGustavo;
}
```
  
</div>
