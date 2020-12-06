# HeroForge Anew Change Log
All notable changes to the project will be documented in this file.

From version 7.4.0.0 onwards, the following versioning convention applies:

Given a version number MAJOR.SOURCE.MINOR.BUGFIX, increment the:

1. MAJOR version for large overhauls of functionality or design,
2. SOURCE version for when new material (primarily a new sourcebook) is added in a manner that breaks backwards-compatibility,
3. MINOR version for when functionality is added in a backwards-compatible manner,
4. BUGFIX version for backwards-compatible bugfixes.

Prior to version 7.4.0.0, the difference between SOURCE and MINOR, and between MINOR and BUGFIX updates, was highly subjective.

## [7.4.1.1] - 2020.12.06
### Bugfixes
- Fixed languages import/export/custom
- Fixed CS2 Equipment first column import/export
- Addressed \`Save Character\` warning message

## [7.4.1.0] - 2020.11.25
- Forked by Dale McConachie

### Bugfixes
- Re-enabled basic Import/Export Functionality

### Added
- Added Unslotted Items
- Added not-Relishi's sword
- Added Dread Commando Team Initiative Bonus from "non-self" on buffs sheet

### Changed
- Moved (almost) all AC bonuses from CS Calc. sheet to Enhancements Sheet

## [7.4.0.0] - 2015-06-04
### Bugfixes
- Tashalatora now properly contributes to Flurry of Blows.
- Monk bonus feats work again.
- Draconic Heritage now properly grants you the appropriate Sorcerer class skill.
- The Trophy Collector feat now properly requires 6 ranks in Craft (taxidermy), not 4.
- Cleaned up some obsolete cell references.
- Diamond Dragon no longer breaks everything forever.
- The Template Information form now gives accurate information.
- Favoured Enemies work properly again.
- Buffs which grant temporary HP will no longer grant their HP unless the buff is active.
- Unwildshaping will now clear all natural attacks you had selected, rather than spewing errors everywhere.
- Point Blank Shot now properly grants the damage bonus within 30ft.
- Dweomerkeeper no longer grants bonus feats, can now select 5 mantles.
- Increased width of Character Sheet II ability display by 4 pixels to help fix word wrap issues.
- Templates that modify speed don't break horribly anymore.
- Templates that modify alignment don't break horribly anymore.
- Renegade Mastermakers now get their DR.
- Sand Shapers now only require you to be a 5th level arcane caster, not to be able to cast 5th level spells.

### Added
- Oriental Adventures. Note: Feats are taken from the sourcebook, not the 3.5 update.

### Changed
- Modified Changelog to use Markdown format
- Changed version compatibility verification code

### Deprecated
- Living Greyhawk support is deprecated and will be removed at some point in the future.

## [7.3.2.4]
### Bugfix
- Fixed some problems with Mind's Eye Psion variants.

## [7.3.2.3]
### Bugfix
- You can now select Eberron Campaign Setting again. My bad.

## [7.3.2.2]
### Bugfix
- Repaired broken race selection dropdown and character summary on Stats & Character Details tab.

## [7.3.2.1]
### Bugfix
- Mind's Eye Psion variants actually implemented. Because I broke it.

### Added
- Added Valarian to the available deities


## [7.3.2.0]
### Bugfixes
- The Great Intelligence feat now only gives 1 Int instead of 3
- Epic level Monk unarmed strike damage no longer breaks things.
- Fist of the Forest unarmed strike damage corrected.
- Ordained Champion now properly gives access to the War domain.
- Added assorted missing Epic skill synergies

### Added
- Wild Shape is now a thing that you can do. It may be buggy due to incomplete animal stats. Expect future releases to gradually add more things you can turn into.
- Animal Companions have been implemented. Note: They don't calculate racial skill bonuses. Enter them manually.
- Mind's Eye Psion variants implemented (with thanks to torrasque666)
- Complete Divine Dweomerkeeper

### Changed
- Familiar damage calculations have been overhauled

### Removed
- Faiths and Pantheons Dweomerkeeper

## [7.3.1.2]
### Bugfix
- Lycanthrope skills work properly now.

## [7.3.1.1]
### Bugfix
- Feats tab was breaking something. Now it isn't.

## [7.3.1.0]
### Bugfixes
- Feats tab now properly resets with the rest of the sheet again.
- You can now be a dragonblooded meldshaper without horribly breaking things.
- Martial Study (White Raven) now properly grants Diplomacy as a class skill.
- Custom familiars work again.
- Cleaned up and fixed several vestige abilities

### Added
- Online prestige classes - Dwarven Chanter, Halfling Whistler, Swiftblade
- Zceryll vestige
- Mindsight feat
- Pseudonatural template


## [7.3.0.1]
### Bugfix
- Repaired broken source selection checkboxes.

## [7.3.0.0]
### Bugfixes
- Made enhancement bonuses affect damage on weapons other than 1st.
- Evereskan Tomb Guardians now properly have Knowledge (Western Heartlands) as a class skill
- Whisper gnomes now have their proper allotment of spell-like abilities.
- Lycanthropes can now actually use Control Shape
- Elemental Scions have their graft numbers calculated properly now.
- Skill tricks now require Complete Scoundrel to be selected for all classes
- Tattooed Monk's monkey tattoo now properly provides a competence bonus.
- Holy Strike now only replaces Ki Strike (magic), not the whole ability.
- Paladins, Rangers, and other similar classes have no caster level below level 4.
- Initiate of Pistis Sophia 10 now properly turns you into an Outsider.
- Conditional formatting on Feats tab repaired.
- Various multiple selection feats now display properly.
- Gestalt skill points properly calculated.
- Assorted minor quality of life and housekeeping changes.
- Assorted corrections to BoED classes.

### Added
- Starting ages for Incarnate, Soulborn, and Totemist.
- Prestige classes from the Player's Guide to Faerun appendix.
- Vampires now have undead immunities and vampire weaknesses.

### Changed
- Changed some behind-the-scenes code relating to lycanthropy and monstrous HD.
- Improved recognition of smite abilities for prereqs.

### Reverted
- Race selection method changes from [7.2.0.0] reverted

## [7.2.0.1]
### Bugfix
- Repaired source references. Oops.

## [7.2.0.0]
### Bugfixes
- Size modifiers now properly apply to grapple checks.
- The Quick trait now properly affects your base land speed.
- Swim speeds from templates now properly calculated.

### Added
- MM1 Devils as races.
- Implemented Fiendish Codex II.
- Note: Only Devil stats are implemented. Racial abilities are not.

### Changed
- Changed how race selection works, to enable races with brackets to not break the sheet.

## [7.1.1.2]
### Bugfix
- Fixed some cell references in the SoulmeldAbilities sheet.

## [7.1.1.1]
### Bugfix
- Disenchanter Mask no longer thinks it's a Diadem of Pure Light bound to your Crown chakra.

## [7.1.1.0]
### Bugfixes
- Made Spinemeld Warrior show available soulmelds properly.
- Skarns can now use their spines.
- Soulborns get the right number of smites per day now.
- Soultouched Spellcasting is no longer pretending to be Soulsight if you select it as a bonus feat.
- Elemental Savants can now pick an element.

### Added
- Magic of Incarnum Racial Substitution Levels
- Soul Manifester and psionic soulmelds

### Changed
- Renamed "Race & Stats" sheet to "Stats & Character Details"
- Alphabetised Racial Substitution Level entries.


## [7.1.0.0]
### Added
- Made Necrocarnate play nicely with the Soulmelds sheet
- Healing Soul feat
- Incarnum abilities calculation for non-soulmeld essentia receptacles.

## [7.0.0.1]
### Bugfix
- Changed calculation of availability of draconic soulmelds to refer to the right source

## [7.0.0.0]
- HeroForge Anew first release. Too many changes from previous versions to summarise.


