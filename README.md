# Skillchains
### Active Battle Skillchain Display

*This is a fork of [Ivaar's addon](https://github.com/Ivaar/Skillchains) with updates for newer skills.*

Displays a text object containing Skillchain elements resonating on current target, timer for Skillchain window,
along with a list of Weapon Skills that can Skillchain based on the weapon you have currently equipped. 

    //sc color    -- colorize properties and elements
    
    //sc move     -- displays text box click and drag it to desired location.

    //sc save     -- save settings to current character.

    //sc save all -- save settings to all characters.

The following commands toggle the display information and are saved on a per job basis.

    //sc spell    -- sch immanence and blue magic spells.

    //sc pet      -- smn and bst pet skills.

    //sc weapon   -- weapon skills.

    //sc burst    -- magic burst elements.

    //sc props    -- skillchain properties currently active on target.

    //sc timer    -- skillchain window timer.

    //sc step     -- current weaponskill step information.

More settings related to text object can be found within the settings.xml, generated on addon load.

---

### Installation

1. Download the ZIP file from the green Code menu in the upper right.
2. Open the ZIP file, and extract the folder within to the `addons` folder in the directory where you installed Windower.
3. Rename the folder to `Skillchains` (remove the trailing `-master`).

---

### Usage

- To load Skillchains every time you launch the game, edit the `scripts\init.txt` file in the directory where you installed Windower and add the following line:
    ```
    lua load skillchains
    ```
- To load Skillchains only once, do any of the following:
  - (in the chat window) `//lua load skillchains`
  - (in the Windower console) `lua load skillchains`
  - (in an in-game macro) `/con lua load skillchains`