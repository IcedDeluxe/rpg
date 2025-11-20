# TODO

1. Dialogue Class
    - enum Type: DIALOG,CHOICE,BATTLE_SCENE_TRIGGER
    - variables: String dialogueID, String text, DialogueOption[] options, Dialogue nextDialogue
    // buhat sad ug JSON file pang reference {id : first 10 words sa dialogue}:
    // ang id should be descriptive sa dialogue/part sa story, kuntahay betrayal na part, ang id kay "betrayal-1",
    // "betrayal-2","betrayal-3"
    ex: 
    {
        "scene-1" : "Mao ni first scene...",
        "scene-2" : "Tas next...",
    }

2. DialogueOption class
    - 2 variables, Dialogue nextDialogue and String text

3. Story
    