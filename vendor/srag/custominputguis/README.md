Custom Input-GUI's

### Usage

#### Composer
First add the following to your `composer.json` file:
```json
"require": {
  "srag/custominputguis": ">=0.1.0"
},
```

And run a `composer install`.

If you deliver your plugin, the plugin has it's own copy of this library and the user doesn't need to install the library.

Tip: Because of multiple autoloaders of plugins, it could be, that different versions of this library exists and suddenly your plugin use an older or a newer version of an other plugin!

So I recommand to use [srag/librariesnamespacechanger](https://packagist.org/packages/srag/librariesnamespacechanger) in your plugin.

### Input-GUI's
* [CheckboxInputGUI](./src/CheckboxInputGUI/doc/CheckboxInputGUI.md)
* [DateDurationInputGUI](./src/DateDurationInputGUI/doc/DateDurationInputGUI.md)
* [GlyphGUI](./src/GlyphGUI/doc/GlyphGUI.md)
* [HiddenInputGUI](./src/HiddenInputGUI/doc/HiddenInputGUI.md)
* [LearningProgressPieUI](./src/LearningProgressPieUI/doc/LearningProgressPieUI.md)
* [MultiLineInputGUI](./src/MultiLineInputGUI/doc/MultiLineInputGUI.md)
* [MultiSelectSearchInputGUI](./src/MultiSelectSearchInputGUI/doc/MultiSelectSearchInputGUI.md)
* [MultiSelectSearchInput2GUI](./src/MultiSelectSearchInputGUI/doc/MultiSelectSearchInput2GUI.md)
* [NumberInputGUI](./src/NumberInputGUI/doc/NumberInputGUI.md)
* [ProgressMeter](./src/ProgressMeter/doc/ProgressMeter.md)
* [PropertyFormGUI](./src/PropertyFormGUI/doc/PropertyFormGUI.md)
* [ScreenshotsInputGUI](./src/ScreenshotsInputGUI/doc/ScreenshotsInputGUI.md)
* [StaticHTMLPresentationInputGUI](./src/StaticHTMLPresentationInputGUI/doc/StaticHTMLPresentationInputGUI.md)
* [TableGUI](./src/TableGUI/doc/TableGUI.md)
* [Template](./src/Template/doc/Template.md)
* [TextAreaInputGUI](./src/TextAreaInputGUI/doc/TextAreaInputGUI.md)
* [TextInputGUI](./src/TextInputGUI/doc/TextInputGUI.md)
* [ViewControlModeUI](./src/ViewControlModeUI/doc/ViewControlModeUI.md)
* [Waiter](./src/Waiter/doc/Waiter.md)
* [WeekdayInputGUI](./src/WeekdayInputGUI/doc/WeekdayInputGUI.md)

### Requirements
* ILIAS 5.3 or ILIAS 5.4
* PHP >=5.6

### Adjustment suggestions
* Adjustment suggestions by pull requests
* Adjustment suggestions which are not yet worked out in detail by Jira tasks under https://jira.studer-raimann.ch/projects/LINP
* Bug reports under https://jira.studer-raimann.ch/projects/LINP
* For external users you can report it at https://plugins.studer-raimann.ch/goto.php?target=uihk_srsu_LINP
