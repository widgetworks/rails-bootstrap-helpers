# Rails Bootstrap Helpers

## Version 0.1.2

* Rails 6/ruby2.7.2 (with bootstrap 2, I know..) fix for frozen string literal in options_helper#append_class! (side effect: always sets :class now)

## Version 0.1.0

### New/Changed Features
* Renamed option "placement" to "position" for `bs_popover_button`
* Add new form tag helper `bs_submit_tag`
* Add new button `bs_collapsible_button`
* Add new tag helper `bs_content_tag`
* Add new helper `accordion`
* Add new options helper `append_class!`
* Add new button helper `button_group`
* Add support for tooltips to button helpers
* Add new helper `action_link_to`
* Add new helper `iconic_icon`
* Add new helper `row_link_to`
* Add new tabbable navigation helper `tabbable`
* Add "inline" HTML class to inline buttons
* Add new dropdown button helper `bs_dropdown_button_to`

### Bugs Fixed
* "class" option not being passed through button helpers
* "class" option not being passed through icon helper

## Version 0.0.1
### New/Changed Features
* Initial releases