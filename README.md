
## 🌌 About Me

```csharp
public class Kurylo : Angel {
    
    List<Alias> Aliases = new(){
        new Alias("Kino"),
        new Alias("Fenrir"),
        new Alias("Adachi"),
        new Alias("Kurylo"), 
        new Alias("Kanadechi")};

    Dictionary<string, Language> _languageList = new() {
        {"VN" , Language.Vietnamese}, {"JP", Language.Japanese}, {"EN", Language.English}, 
        {"DE", Language.German}, {"NL", Language.Dutch}, {"CN", Language.Chinese} 
    };
    
    Food FavFood = Food.MapoTofu;
    Sport FavSport = Sport.Badminton;

    Affiliaton Class = Affiliation.Angel; 
    Country Nationality = Country.Vietnam;
    PersonalityType Personality = Type.INFJ;
   
    public Kurylo getInfo() => this;
    public Gender getGender() => Gender.Female;
    public bool inRelationship() => true; 
}
```
