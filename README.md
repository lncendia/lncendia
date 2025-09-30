- 👋 Hi, my name is Egor, I'm a .NET Backend Developer with over 4 years of experience.
- 👀 I specialize in building robust backend solutions using ASP.NET, Entity Framework, MongoDB, and PostgreSQL. I also have experience working with frontend technologies like React and TypeScript to create seamless full-stack applications.
- 🌱 I'm interested in developing web applications, focusing on efficient architecture and scalable solutions.
- 📫 You can reach me on Telegram: @Incendia23.

``` C#
Incendia? incendia = await _uow.IncendiaRepository.Value.GetAsync(14112003);
if (incendia == null) throw new IncendiaIsBusyException();
Coffee coffee = _coffeeFactory.Create();
incendia.DoJob(coffee);
await _uow.IncendiaRepository.Value.UpdateAsync(incendia);
await _uow.SaveChangesAsync();
```
<!---
lncendia/lncendia is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

![](https://github-readme-stats.vercel.app/api/top-langs/?username=lncendia&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)
