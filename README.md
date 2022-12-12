## Hello, World! 👋

<div align="center">

<img src="https://user-images.githubusercontent.com/56282554/174655304-d35e92f9-d145-4041-ac20-faf4b8a7adf4.gif">

I'm a Software Developer at <a href="https://m8sistemas.com.br/">M8 Sistemas</a></p>

[![WebSite](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://luizzanoni.vercel.app/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luizgustavozanoni/)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/luiz.gzanoni/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:dev.luizzanoni@gmail.com)



<details>
<summary> More about me:</summary>
<div align="left">


``` C#
public ActionResult LuizGustavoZanoni(int Id)
{
	var luizGustavo = GI.S<LuizGustavoZanoni>()
						.Listar(false, s => s.Id == filtro)
						.Select(s => new 
						{
							s.FullName, s.BirthDate, s.Pronouns, 
							.Interests, s.Motivations, s.Technologies
						})
						.FirstOrDefault();
						
		var quemSouEu = luizGustavo;
		
			Console.WriteLine
			(
				fullName: 'Luiz Gustavo Zanoni',
				birthDate: '2000-01-27',
				pronouns: 'he' | 'him',
				interests: ['music', 'games', 'language learning', 'trips', 'motorcycle'],
				motivation: 
				{
					'Discover and code new things',
					'Making life easier and smarter through tech',
				}
				Technologies:
				'HTML, CSS, dotNET, JavaScript, React, API's, ASP.NET Core, MVC, jQuery'
			)	
}
```
  
</div>
</details>
  
<!--
**luizzanoni/luizzanoni** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
