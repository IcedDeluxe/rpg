# TODO
- Implement Save & Load feature
- Use java serialization (ObjectOutputStream and ObjectInputStream)
- SaveLoad.java should have these 2 methods:
    void save(Player player, String profileName)
    Player load(String profileName)

    - Serialize a Player object, then write it in saves/profile1.sav
    - Deserialize saves/profile1.sav back into a player object
- Dis is how save and loading works

*Save:*
GameState.player --as input in--> SaveLoad.save() --calls--> ObjectOutputStream --output-to--> saves/profileName.java

*Load:*
SaveLoad.load() --calls--> ObjectInputStream --output--> GameState.player = output
