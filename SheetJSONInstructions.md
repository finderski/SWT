# Savage Worlds Tabbed Character Sheet\r\r

### Now with International Language Support!!\r\r

## Character Sheet\r\r

* The Character Sheet view can be toggled between Wild Card and Mook using the button in the upper left-hand corner (default is Wild Card)\r
* The Mook sheet and the Wild Card sheet are the same sheet, thus allowing universal macros; selecting a character sheet as a Mook will prevent it from rolling a Wild Die when using the buttons on the sheet.
* The banner indicates type of character the sheet is for (Mook vs. Wild Card, unless changed on the Game Settings page)
* The sheet now has a Stat Block button that will whisper the entire stat block of the character to the Chat window—this stat block includes Ability Command Buttons so rolls can be made directly from the Chat window.\r
* The sheet has a configuration section so it can be tweaked to fit the Setting being played\r\r

## Configuration\r\r

To configure the sheet to meet your needs, click the Gear icon. In the configuration section you can:\r\r

* Configure Initiative modifying Edges for the DealInit API Script\r
* Indicate the character has certain rule altering edges (such as Nerves of Steel or Fleet-Footed)\r
* Change the UI in the **UI Tweaks** section\r
  * Select a Background for the sheet\r
  * Select a Logo to match your setting\r
  * Choose a Roll Template for Trait & Damage rolls\r
  * Elect to show dice icons instead of drop down menus.\r
     - This feature is only available for Attributes, Skills, and the Wild Die.\r
     - The enhanced Trait Die Type Drop Down Menu uses the same field names as the regular drop downs, which introduces a risk for potential data loss. To minimize risk use only the standard textual drop down menu OR make periodic notations of all Trait ranks.\r
         + **NOTE:** I've not experienced any problems (except with repeating sections, which is why this hasn't been implemented there yet. But, fair warning.\r
  * Hide the Arcanum tab (shown by default)\r
  * Show Vehicle tab (hidden by default)\r
  * Choose a handwriting font for the Quest Log\r
* Configure the sheet with various Game Settings\r
     - Quick Settings\r
         + Allows you click a supported setting and all the appropriate fields for that setting will automatically be selected for the character sheet.\r
     - Show additional Stats and Fields\r
     - Replace field names with setting specific ones\r
* Configure Optional & Home Brew Rules\r
     - Variable Bonus Damage die type: This allows you to change the standard d6 bonus to something different for people who increase the die type for each additional Raise achieved on the Trait roll\r
     - Choose to not use Power Points\r
     - Option for Skill Specialization\r
     - Roll for extra XP for unspent Bennies\r\r

## Attributes & Skills\r\r

* Skills (Wild Card and Mook)\r
    - All skills from the Savage Worlds Core Deluxe rules are included in the sheet, but are hidden by default. To manage them, click on the \"+/- Core Skills\" button on the Skills tab (right above Fighting) and place a check mark next to each skill you'd like to use.\r
    - The sheet supports the optional Skill Specialization rule. To manage this, click on the \"+/- Core Skills\" button on the Skills tab (right above Fighting) and place a check mark next to \"Use Skill Specialization\"\r
    - Fencing Styles and Schools are supported. click on the \"+/- Core Skills\" button on the Skills tab (right above Fighting) and place a check mark next to \"Fencing Styles & Schools\"\r
* All Trait dice are limited to the standard d4-d12 dice. To accommodate certain Edges that allow one to have a trait die type that has a permanent modifier (ie Professional, Woodsman, etc.) use the modifier box to the right of each Trait die type.\r
* You can mouse over just about any field to get its attribute name.\r
* All field titles follow Roll20's attribute syntax, ie. Agility would be displayed as \"@{agility}\" on mouse-over.\r\r

## The Wild Die\r\r

* The Wild Die is a configurable field to allow for Edges (such as Master) that may alter the Wild Die.\r\r

## Rolls\r\r

* You can mouse over any button to get its ability name.\r
* Roll button titles DO NOT follow Roll20's ability syntax, using the selected token, ie. \"%{selected|STR-check}\", but will only show the attribute displayed like \"@{AgilityRoll}\".\r
* The gm button uses the exact same formula for rolling as the regular button, but will whisper the roll to the GM.\r\r

## Additional Notes\r\r

* Most Repeating Sections have a \"Hide Macro Formula\" checkbox. Unchecking it will reveal a formula you can use to create macros that simulate the roll buttons in that repeating section.\r
* Apply Encumbrance Checkbox (in the skills sections) can be checked to automatically apply any Encumbrance Penalties to a particular skill roll. The standard skills already care for this automatically.\r
* If there's something you want added, or you'd like to report a bug, please contact Finderski in the \"Character Sheets\" forum (putting Savage Worlds in the title will help me notice the post more readily, but isn't strictly necessary).\r\r

---\r\r

## Special Thanks\r\r

I'd like to thank the following for their help in the development of this sheet:\r\r

* Actoba\r
* herrozerro\r
* Brian (CSS wizard)\r
* Sam Marino\r\r

I stole a lot of css/html from them\r\r

* Felipe F\r\r

For implementing the i18n stuff so the sheet can be translated into other languages.