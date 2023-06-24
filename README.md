
## 🌌 About Me

```csharp
[CreateAssetMenu(menuName = "Kurylo/Create new")]
public class KuryloDev : ScriptableObject {

    List<Alias> _aliases = new(){
        new Alias("Kino"),
        new Alias("Kana"),
        new Alias("Adachi"),
        new Alias("Kurylo"), 

    Dictionary<string, Language> _languageList = new() {
        {"VN" , Language.Vietnamese}, {"JP", Language.Japanese}, {"DE", Language.German},
        {"NL", Language.Dutch}, {"EN", Language.English}, {"CN", Language.Chinese}, 
        {"JSL", Language.SignLanguage}  
    };

    [TextArea]
    Food favFood = Food.MapoTofu;
    Sport favSport = Sport.Badminton;

    Country nationality = Country.Vietnam;
    PersonalityType personality = Type.INFJ;
    Affiliaton affiliation = Affiliation.Angel; 

   [ContextMenu("View Info")]
    public Kurylo GetInfo() => this;
    public bool InRelationship() => false; 
    public Gender GetGender() => Gender.Female;
}
```
