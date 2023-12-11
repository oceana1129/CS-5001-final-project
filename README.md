# Final Project Report
* Student Name: Oceana Gershberg
* Github Username: oceana1129
* Semester: Fall 2023
* Course: CS 5001

## General Information
### Introduction
Hello, and welcome to the Text Adventure RPG! This is a role-playing game, based on the Pathfinder 2e rule system, where you assume the role of an adventurer uncovering the secrets of a dungeon. 

### Key Features
Here are some of the features of the game:
Character Class Selection (unique mechanics  and actions for each class)
Dynamic Degrees of Success (critical fail, fail, success, critical success)
Character Rolls (ability rolls, saving throws, and attack rolls)
Dice Rolling (natural 1s and natural 20s)
Input Based Exploration 
Various Room States
Input Based Navigation
Hazards, Puzzles, and Secrets
Unique Enemies and Varied Attacks
Combat (healing, dealing damage, taking damage)
Health, Mana, and Cooldowns
Inventory System (read item descriptions and consume potions)

### How Does The Pathfinder 2e System Work?
If you are unfamiliar with how game systems like Pathfinder 2e work, here is a basic lay down.

The game is based on a system of rolling dice to play. The main dice you will use is a D20 (a twenty-sided dice). You roll to see what degree of success you’ve gotten from a specific check. There are four different states of success: critical failure, failure, success, and critical success. When you roll a d20, if you roll a 1 then you automatically fail that check. If you roll a 20, then your initial degree of success is increased by one degree. 

If you are exploring, then you must pass a DC check (difficulty check) with a D20 plus your ability modifier. If you are attacking a monster, you must roll over their AC (armor class) with a D20 plus your attack modifier. If you are dodging a hazard or attack, you must roll over the DC check (difficulty check) with a d20 plus your save modifier. The same rules apply to monsters when attacking you. All damage incurred from failing a check uses smaller pools of dice to calculate damage including D4s, D6s, D8s, D10s, and D12s.

### How Do I Run The Game?
Here are the instructions to run the game:
You must download all of the files of the game by downloading the ZIP file of this repository (or by cloning the repository).
Download and extract the files.
Open the file game.py
Run the file in your terminal.
If you have successfully downloaded the game and files, then you should now be able to run the game from your terminal or console. It will display the ‘Title Screen’ indicating that the game is now successfully running.

### How Do I Play The Game?
The game is a simple input-based game. You explore and navigate the game by typing in various inputs when prompted. Type ‘Help’ at any time to learn more about the inputs you can type in during exploration. 

### Starting The Game
To begin the game, you must create your character with their name and selected class. 

There are four classes to choose from: Fighter, Wizard, Rogue, and Bard.

Fighters and Rogues are melee classes. They use actions in hand-to-hand combat. Their strongest attacks have cooldowns, so you must pay attention to what has been used. Wizards and Bards are spellcaster classes. They use actions that consume mana. You have a limited mana pool, so make sure you are not overusing your most powerful spells. 

Each class has specific actions they can take, impacting both combat and exploration. Each class also has different health pools, mana pools, saving throws, and abilities. Abilities include strength, dexterity, constitution, wisdom, intelligence, and charisma. 

### Exploring The Game
Once you are all set up, you may begin your adventure.

You begin your adventure at the entrance of a cave, you are given a general description of what you are experiencing and seeing when you first enter. You have various choices for exploration. 

You, as the player, can input various commands to explore and interact with the world around you. Most actions require you to make a  ‘skill roll’ (adding a D20 and adding your ability modifier). You have standard actions such as ‘look’ and ‘recall’ to get a general glimpse of the scene around you. You also have other actions to explore and solve puzzles such as ‘talk’, ‘pet’, ‘intimidate’, ‘jump’, and many others to choose from. Try to think of the appropriate action your character would take to complete the room or puzzle. Remember, you may type ‘Help’ at any time to get a larger list of standard actions you can take.

If you happen to encounter a creature during your adventure, know that there are several options available to get out of the encounter peacefully. These answers will not be given to you. Exploration is important.

If you encounter a creature and things do not end peacefully, then an encounter will begin. Each round the creature and you will take a turn to take an action from their attack list. There is variability in what actions you can take, depending on your character so do be sure to take note of what you can do.

Once a room is cleared, you may explore and navigate to other rooms. This is done through simple north, south, east, and west commands to navigate. Note, that if a room was not cleared or failed, certain rooms or options may not be available to you. 

### Thank You For Playing
Thank you, the player, for playing my game. This game is currently available as a Demo with 10 different rooms to explore.

If you’d like to see more or enjoy my game, stay tuned to my GitHub page. If you have anything to share, have feedback to give, or find any potential errors then please let me know. Any feedback is appreciated.

## More About The Project
### Why Was This Project Made?
This project was a labor of love as my final project for CS 5001. I had this project idea in mind for various reasons. 

When I was first starting my coding adventure, I tried to create an RPG Text Adventure Game on my own. However, since I was new and still learning how to code, I was unsuccessful in creating any successful implementations of my ideas. Figuring out the logic and scale of the project I had in mind was too much for me to create, at that time. 

When I had to think of a final project idea and saw this concept in the recommended project ideas list, it reminded me of my previous failure. Taking this project felt like a way to personally see how far I’ve grown personally and technically.

The other reason I wanted to create this project, in particular, is due to my love for DnD and Pathfinder 2e. For the past 8 years, DnD has been my biggest personal hobby and passion. I play it every single weekend and sometimes up to 2 different games per week. As an artist and aspiring storyteller, I have a profound love for role-playing games. They act as a perfect medium to build stories and develop characters with people that you enjoy being around. It has been a hobby that has helped me come out of my shell. It has taught me to be more confident and communicate with others. 

Lastly, with the knowledge I have now, I understand how the scope of this kind of project can be large and varied enough to test out everything I have learned in my course. It would act as the perfect kind of test to explore and dig deeper into the core concepts of Python. It also was a great test to measure how well I could manage my time and keep the scope of the project in mind.

For these reasons, this RPG Text Adventure Game is something I felt very inspired to make my final project.

### Major Challenges
Key aspects could include pieces that you struggled with and/or pieces that you are proud of and want to show off.
There were many interesting problems I had to tackle to make the game run properly. My first major hurdle was breaking down every single component of the mechanics into simple and computable steps. Once I had that figured out, the biggest hurdle I had was creating navigable rooms that were dynamic and explorable. I had to do a lot of research and exploring to come up with a good format for my rooms to be set up. They went through three different iterations and I was finally able to break them down in a way that was easy to read, easy to navigate, and simple to execute. Then I had to figure out how to set up character classes. I tried doing this early on in my project but struggled significantly with it. Once, I had figured out how I was going to be setting up rooms, it helped me figure out a similar approach I could use to create different characters and character actions. Thankfully, solving my biggest hurdles helped me overcome most other issues in my code. The knowledge of what things could be done and were possible opened my eyes to creating more complex solutions.

### Missing Features / What's Next
Focus on what you didn't get to do, and what you would do if you had more time or things you would implement in the future. 
This is a project that has a lot of different moving parts to it. There were many different concepts and ideas that I began to work on but was unable to implement due to scope issues. 

For combat, I wanted to include a system that allowed player characters and monsters to affect status conditions onto each other. I also wanted player characters to be able to use inventory during combat. I also would want to have implemented more quality-of-life aspects for players. One idea was a view the current character status function that players could use to see their health, mana, saving throws, and character abilities. Another thing I would’ve liked to add was a text scroll settings parameter, which would allow users to adjust their preferred text scroll settings. I also would have liked to spend more time fleshing out the inventory management system. I would have preferred to put inventory management in different areas and make the code look more clean. There were also a few anomalies in the code that I would have preferred to fix. Mainly things that were displayed on screen that I wish were a little more polished. With more time, I would have liked to have ironed out these specific issues.

Aside from that, I had spent the time mapping out a full-fledged dungeon with 22 different rooms. However, given the current time, I had to work with. Creating all of the content I would have liked would have been foolhardy. Thankfully, with the current system I have in place, I know that if I wished to go back to this project, I would be able to add in all of these additions and content relatively and smoothly.

## About The Code
### Code Review
#### Files a0, s1, s2, s3, a1, a2, a3, b1, b2, c2
These are all files that contain each room available in the game. They all have their own unique choices available for the player to take. Some of them also have events with either hazards or combat. 
```python
# an example
room = create_room.Room(
    name="entrance",
    event="exploration",
    description="You stand at the entrance of a dark cave.\n\nThe air is "
                "thick with an uneasy stillness. "
                "The faint rustling of the ground beneath your feet echoes in "
                "the cavernous darkness. This may be your very "
                "last breath of fresh air for all you know. You grip your weapon and "
                "prepare for your journey ahead.",
    room_cleared=False,
    room_failed=False,
    room_secret=False,
    trigger_event=False,
    trigger_name=False,
    description_cleared="Continue north to the main entrance or examine the wall "
    "further east?",
    description_failed="No time to dwaddle, the only way forward is up ahead.",
    loot={},
    action_cleared={
        "": create_room.Action_Cleared(
            used=False,
            bonus="",
            text=""
        )
    },
    actions_cleared_navigation={
        "north": create_room.Action_Cleared_Navigation(
            navigation_text="Continue through the entrance and move north.",
            next_room="a1"
        ),
        "east": create_room.Action_Cleared_Navigation(
            navigation_text="Walk over and investigate the east wall.",
            next_room="s1"
        ),
    },
    actions_not_cleared={
        "perception": create_room.Action_Not_Cleared(
            used=False,
            DC=32,
            ability="perception",
            bonus=0,
            success_effect="room cleared",
            success_bonus=0,
            fail_effect="room failed",
            success_text="You notice some strange markings on the wall to the east. Their glow "
            "is faint and bright. You swear these markings weren't there previously.",
            fail_text="You see nothing out of the ordinary. Steel your wits; it’s time to go in!",
        )
    },
    actions_not_cleared_navigation={
        "north": create_room.Action_Not_Cleared_Navigation(
            navigation_text="Continue and move north.",
            next_room="a1",
            trigger_event=""
        )
    }
)
```


#### Files character_creator.py, compendium_monsterv, compendium_hazards.py,  items_compendium.py, and create_room.py
Each of these files is responsible for creating classes for the respective type of object it is. 

character_creator.py is responsible for creating individual characters including basic stats, jobs, and actions specific jobs can take. 
```python
# an example
class Bard(Job):
    def __init__(self):
        abilities = {
            "str": 0,
            "dex": 4,
            "con": 3,
            "intell": 1,
            "wis": 2,
            "cha": 5
        }
        saves = {
            "perception": 10 + 2 + 6,
            "fortitude": 10 + 3 + 6,
            "reflex": 10 + 4 + 4,
            "will": 10 + 2 + 6,
            "ac": 10 + 12 + 4 + 1
        }
        attacks = {
            "physical": 15,
            "spell": 20
        }
        super().__init__(
            name="Bard",
            lvl=10,
            abilities=abilities,
            saves=saves,
            attacks=attacks,
            class_hp=8,
            class_mp=50,
            class_main_ability="cha",
            actions={
                "punch": Weapon(
                    name="Punch",
                    typing="melee",
                    job="all",
                    num_of_dice=3,
                    damage_size=4,
                    add_dmg=0,
                    mana_cost=False,
                    heals=False,
                    cooldown_duration=False,
                    cooldown_counter=False
                ),
                "haunting hymm": Weapon(
                    name="Haunting Hymm",
                    typing="spell",
                    job="bard",
                    num_of_dice=4,
                    damage_size=6,
                    add_dmg=5,
                    mana_cost=False,
                    heals=False,
                    cooldown_duration=False,
                    cooldown_counter=False
                ),
                "sooth": Weapon(
                    name="Sooth",
                    typing="spell",
                    job="bard",
                    num_of_dice=2,
                    damage_size=10,
                    add_dmg=8,
                    mana_cost=2,
                    heals=True,
                    cooldown_duration=False,
                    cooldown_counter=False
                ),
                "sound burst": Weapon(
                    name="Sound Burst",
                    typing="spell",
                    job="bard",
                    num_of_dice=3,
                    damage_size=10,
                    add_dmg=8,
                    mana_cost=3,
                    heals=False,
                    cooldown_duration=False,
                    cooldown_counter=False
                ),
                "painful vibrations": Weapon(
                    name="Painful Vibrations",
                    typing="spell",
                    job="bard",
                    num_of_dice=10,
                    damage_size=6,
                    add_dmg=2,
                    mana_cost=5,
                    heals=False,
                    cooldown_duration=False,
                    cooldown_counter=False
                ),

            }
        )
```

compendium_monster.py is responsible for creating the classes for all potential monsters or enemies that show up in the game. It also is responsible for the stats, and attacks monsters can take. 
```
```python
# an example
monster_shadow = Monster(
    name="Shadow",
    ac=22,
    max_hp=35,
    current_hp=35,
    level=4,
    lore_dc=17,
    lore_mod="wis",
    loot={},
    defeat_text="The shadow shakes, falling to the floor and leaving behind a black ooze.",
    win_text="The Shadow shakes with glee as a shrill laughter escapes from it.",
    attack_list={
        "shadow claws": Attacks(
            name="Shadow Claws",
            frequency=[0, 0.7],
            atk_roll=15,
            dc=0,
            dc_type=None,
            apply_condition_first="",
            apply_condition_second="",
            num_of_dice=2,
            dice_size=6,
            add_dmg=4,
            success_text="The Shadow swipes at you with its Shadow Claws. "
            "Tendrils phase through your skin as you take damage.",
            fail_text="You shudder as the Shadow reaches out for you with its Shadow Claws. "
            "It overestimates and misses.",
            self_heal_num_dice=0,
            self_heal_dice_size=0,
            self_heal_mod=0
        ),
        "steal shadow": Attacks(
            name="Steal Shadow",
            frequency=[0.71, 1],
            atk_roll=0,
            dc=27,
            dc_type="reflex",
            apply_condition_first="",
            apply_condition_second="",
            num_of_dice=3,
            dice_size=4,
            add_dmg=6,
            success_text="The Shadow grasps a sliver of your shadow and steals it.",
            fail_text="You shudder as the Shadow reaches out for your shadow as you "
            "adeptly dodge it.",
            self_heal_num_dice=0,
            self_heal_dice_size=0,
            self_heal_mod=0
        )
    }
)
```


compendium_hazards.py is responsible for creating the classes for all hazards that the player may encounter.
```python
# an example
hazard_tiles = Hazard(
    name="Tile Arrow Trap",
    dc=26,
    saving_throw="reflex",
    description="The tiles shift down as a mechanism is triggered. The walls surrounding "
    "you suddenly come to life, shifting and opening with a sinister creak. "
    "In an instant, a relentless flurry of arrows is unleashed, filling the "
    "narrow corridor with deadly projectiles",
    skill_crit_success="",
    skill_success="With remarkable agility, you gracefully evade the oncoming barrage "
    "of arrows. Your movements are like a carefully choreographed dance, and you "
    "emerge from the hail of projectiles completely unscathed, your heart pounding"
    " with adrenaline.",
    skill_fail="You valiantly attempt to dodge the relentless assault of arrows, "
    "but despite your efforts, some of the projectiles find their mark. The impact "
    "is painful, and you bear the brunt of the attack as you stagger through the "
    "other side, wounded but determined.",
    skill_crit_fail="In your desperate bid to avoid the arrows, you stumble and "
    "falter. The arrows seem to find you with uncanny accuracy, striking "
    "you with piercing force. \nYou endure the pain, as you finally make it through the storm.",
    damage_dice=2,
    damage_size=4,
    modifier=2
)
```


items_compendium.py is responsible for setting up classes for inventory items including their descriptions and uses.
```python
# an example
inventory_list = {
    "healing potion lesser": Create_Item(
        name="healing potion lesser",
        description="A potion that restores a small amount of health.",
        consumeable=True,
        potion_type="hp",
        event=False
    ),
    "healing potion moderate": Create_Item(
        name="healing potion moderate",
        description="A potion that restores a moderate amount of health.",
        consumeable=True,
        potion_type="hp",
        event=False
    ),}
```

create_room.py is responsible for setting up classes for all rooms that the player may encounter. It allows the program to be able to manipulate the room state easily. Each room has various room states that are affected by player actions. The four-room states include: unexplored, room cleared, room failed, and room secret found.
```python
# an example
class Room:
    def __init__(self, name, event, description, room_cleared, room_failed, room_secret, trigger_event,
                 trigger_name, description_cleared, description_failed, loot, action_cleared,
                 actions_cleared_navigation, actions_not_cleared, actions_not_cleared_navigation):
        self.name = name
        self.event = event
        self.description = description
        self.room_cleared = room_cleared
        self.room_failed = room_failed
        self.room_secret = room_secret
        self.trigger_event = trigger_event
        self.trigger_name = trigger_name
        self.description_cleared = description_cleared
        self.description_failed = description_failed
        self.loot = loot

        ### ACTIONS SPECIFIC TO THE ROOM ###
        self.action_cleared = action_cleared
        self.actions_cleared_navigation = actions_cleared_navigation
        self.actions_not_cleared = actions_not_cleared
        self.actions_not_cleared_navigation = actions_not_cleared_navigation
```

#### files game.py
This is the main file that runs the game. It is responsible for handling the interactive side of the game such as displaying the title screen, handling room navigation, handling combat, and handling rooms.
```python
# an example
def about_game():
    """
    Will display information about the game, then return the user
    to the title_screen_options()
    """
    mechanics.print_text(keywords.text_about)
    press_enter_to_continue()
    mechanics.print_text(keywords.text_title_screen)
    title_screen_options()


def quit_game():
    """
    Will display the quit game text, and then stop the program.
    """
    mechanics.print_text(keywords.text_quit)
    sys.exit()


def title_screen():
    """
    Display the initial title screen and prompt the user to enter commands
    from title_screen_options().
    """
    os.system("clear")
    mechanics.print_text(keywords.text_title_screen)
    title_screen_options()


def title_screen_options():
    """
    Options available when user first starts the game.
    Depending on the input, it will run the appropriate function.
    Otherwise, it will display an error message.
    """
    while True:
        try:
            command = mechanics.player_input_category(
                option_title_screen(), CHARACTER)
            if command == "play":
                mechanics.print_text("Starting the game...", "normal")
                setup_game()
            elif command == "about":
                about_game()
                mechanics.print_text(keywords.text_title_screen)
            elif command == "help":
                help_menu("title")
            elif command == "quit":
                quit_game()
            else:
                mechanics.style_error(keywords.text_error)
        except ValueError:
            mechanics.style_error(keywords.text_error)
```

#### keywords.py
This file is used as a dictionary for actions that the user can take, and inventory that the user can hold. It also holds important general text and string that is used throughout the game.
```python
# an example
action_keywords = {
    # menu stuff
    "play": ["start", "play", "play game", "start game", "boot", "boot game", "p1"],
    "help": ["help", "h3"],
    "about": ["about", "a2"],
    "restart": ["restart", "restart game", "reboot", "reboot game", "r4"],
    "quit": ["quit", "end", "quit game", "end game", "q5"],
    "yes": ["yes", "confirm", "accept", "affirmative", "indeed", "certainly",
            "absolutely", "sure", "okay", "positive", "roger", "aye", "correct"],
    "no": ["no", "cancel", "deny", "negative", "nah", "not really", "never",
           "nope", "decline", "deny", "reject", "disagree"],

    # character creation
    "fighter": ["fighter"],
    "wizard": ["wizard"],
    "bard": ["bard"],
    "rogue": ["rogue"],

    # out of combat and exploration
    "character status": [
        "check health", "examine status", "inspect character", "view stats",
        "analyze condition", "current status", "current health", "stats",
        "status", "health", "mana", "check mana"],
    "inventory": ["check inventory", "inventory", "item", "items", "look at inventory",
                  "check items"],

    # navigation
    "navigation": ["move", "go", "walk", "travel", "run", "move", "navigate", "traverse", "head"],
    "north": ["north", "up", "forward", "ahead"],
    "south": ["south", "down", "back", "backward", "behind"],
    "east": ["east", "right"],
    "west": ["west", "left"],

    # recall knowledge
    "recall knowledge": ["knowledge", "recall", "recall knowledge", "check", "learn",
                         "remember", "recall information", "think", "ponder", "contemplate",
                         "occult", "arcana", "society"],

    # basic interactions
    "interaction": ["pick up", "grab", "use", "interact", "maneuver", "handle"],
    "manipulate": ["touch", "trace", "reach", "handle", "feel", "caress", "manipulate", "tap"],

    # wisdom actions
    "perception": ["look", "observe", "inspect", "survey", "explore", "search", "investigate",
                   "gaze", "view", "examine", "scrutinize", "peer", "check", "assess",
                   "perception", "explore"],
    "animal handling": ["pet", "tame", "interact with animals", "speak with animals",
                        "befriend", "tame creatures", "communicate with beasts"],
}
```

#### tests.py
This file is responsible for running tests to ensure that functions are working while the project is in production. 
``` python
# an example
def test_roll_dice() -> int:
    """
    Tests the function... test_roll_dice()
    Will return the total number of failures.

    Return:
        failure_count (int): The total number of failures
    """
    failure_count = 0
    failure_count += check_exact(len(mechanics.roll_dice(1, 4)), 1)
    failure_count += check_exact(len(mechanics.roll_dice(10, 4)), 10)
    failure_count += check_range((mechanics.roll_dice(1, 4))[0], 1, 4)
    return failure_count


def test_nat_one() -> int:
    """
    Tests the function... test_nat_one()
    Will return the total number of failures.

    Return:
        failure_count (int): The total number of failures
    """
    failure_count = 0
    failure_count += check_exact(mechanics.nat_one(1), True)
    failure_count += check_exact(mechanics.nat_one(10), False)
    failure_count += check_exact(mechanics.nat_one(-1), False)
    return failure_count

```

#### mehanics.py
This file is responsible for running all of the core mechanics that game needs to run. Including handling dice rolls and configuring user inputs. 
```python
# an example
def roll_dice(num_of_dice: int, size_of_dice: int) -> list:
    """
    Roll a set number of dice according to the number of dice and the size of the dice. Saves all rolls in a list.

    Args:
        num_of_dice (int): The number of dice rolled
        size_of_dice (int): The size of the dice rolled

    Returns:
        dice_rolls (list): All of the dice rolled
    """
    dice_rolls = []
    for i in range(num_of_dice):
        dice_rolls.append(random.randint(1, size_of_dice))
    return (dice_rolls)


def roll_ability_check(modifier: int = 5, char_level: int = 10) -> tuple:
    """
    Roll for an ability check. Also, saves if a nat 1 or nat 20 was rolled.

    Arguments:
        modifier (int): rolled ability modifier
        char_level (int): level of the character

    Returns:
        tuple: A tuple with base roll[0], total roll[1], nat 1 bool[2], and nat 20 bool[3].
    """
    roll = roll_dice(1, 20)[0]  # base dice roll
    total_roll = roll + modifier + char_level
    return (roll, total_roll, nat_one(roll), nat_twenty(roll))


def roll_ability_save(modifier: int = 14) -> tuple:
    """
    Roll for an ability save. Also, saves if a nat 1 or nat 20 was rolled.

    Arguments:
        ability (str): the ability we are checking.

    Returns:
        tuple: A tuple with base roll[0], total roll[1], nat 1 bool[2], and nat 20 bool[3].
    """
    roll = roll_dice(1, 20)[0]  # base dice roll
    total_roll = roll + modifier  # calculate total roll with modifier
    return (roll, total_roll, nat_one(roll), nat_twenty(roll))
```

### Example Runs
[Here is a YouTube link displaying some runs of the code](https://youtu.be/Fx_okUmQX44)

### Testing
I created some unit tests for the basic mechanics of the game included in tests.py. However, since most of the game is input-based, I had to run the main file to see how it would interact as a whole. Do note that each function was individually tested as the game was being written.


### Final Reflection
During my time in the course, I have been able to learn a lot and grow. It was my first time learning Python as a coding language and understanding how it works. I was able to learn a lot of powerful concepts that I know I’ll surely be using in the future. Aside from learning the concepts that cover Python, I learned a lot of important concepts that I know will apply to other languages and projects in the future. Some of the major concepts I learned during the course were proper styling, documentation, code testing, and code efficiency. 

The major things that I want to improve upon include time management, project scoping, reaching out to employers, being more comfortable asking questions, and participating more in groups. I’ve always struggled with reaching out to my teachers and TAs, so I’m hoping this is something I can feel more comfortable doing later as a student.

Being self-taught previously in web dev skills, it has been very eye-opening to take this course in general. I’ve been able to open my eyes more to what is expected in the professional realm, and I look forward to learning more in the future too.


