- 👋 Hi, my name is Egor, I'm a .NET developer.
- 👀 I'm interested in web applications, bots and desktop programs.
- 📫 My telegram: @Incendia23.

``` C#
Incendia? incendia = await _uow.IncendiaRepository.Value.GetAsync(14112003);
if(incendia == null) throw new IncendiaIsBusyException();
Coffee coffee = new Moccachino(1);
incendia.DoJob(coffee);
await _uow.IncendiaRepository.Value.UpdateAsync(incendia);
await _uow.SaveChangesAsync();
```
<!---
lncendia/lncendia is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
