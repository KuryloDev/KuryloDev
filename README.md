
## 🌌 About Me

```csharp
public class Kurylo : Angel {
    List<Alias> _aliases = new(){
        new Alias("Kino"),
        new Alias("Fenrir"),
        new Alias("Adachi"),
        new Alias("Kurylo"), 
        new Alias("Kanadechi")};

    Dictionary<string, Language> _languageList = new() {
        {"VN" , Language.Vietnamese}, {"JP", Language.Japanese}, {"EN", Language.English}, 
        {"DE", Language.German}, {"NL", Language.Dutch}, {"CN", Language.Chinese} 
    };
    
    Food favFood = Food.MapoTofu;
    Sport favSport = Sport.Badminton;

    Country nationality = Country.Vietnam;
    PersonalityType personality = Type.INFJ;
    Affiliaton affiliation = Affiliation.Angel; 
   
    public Kurylo getInfo() => this;
    public bool inRelationship() => false; 
    public Gender getGender() => Gender.Female;

}
```
