# Cultures Conestoga Mall Delivery Menu Plan

This document contains the instruction for setup the special menu on SkipTheDishes.

* [Main Menu](/menu.md)
* [Menu Structures Overview](#menu-structrues-overview)
* [Modifier](#modifier)
* [Modifier References](#modifier-references)

Last Update: Apr 18, 2019

## Menu Structures Overview

- **Section Title** [link to section photo](#section-title)
  - Section Pictrue (if applicable)
  - Section Description (if applicable)

  - **Item Title** *Price* [link to item photo](#item-title)
    - Item Description
      - Item Modifiers Tags (if applicable)
      - Item Modifier Title (if applicable)
      - Item Modifier Description (if applicable)
      - Modifier Option *price*

## Modifier

Modifier is a group of options, it is a tool for customers to leave instructions for their orders.

Each modifier are defined by a tag, started by ```modifier_```. A modifier may used for multiple times. There are two kinds of modifiers in this menu:

- **In-Menu Modifier** (See Menu Structures for details)
- **Tagged Modifier**

A **Tagged Modifier** may be used for several times. This modifier will be called by it's tag name. The tag name could be found in the modifier reference page.

These modifiers have three main class: ``Required``, ``Type`` and ``Multiple``.

``Required`` class describe the necessity of the modifier.
> *values*
``true``: this modifier is required when added to the menu
``false``: this modifier is optional when added to the menu

``Type`` class describe the type of the modifier.
> *values*
``radio``: display as a radio button - <input type="radio">
``checkbox``: display as a check box - <input type="checkbox">
``text``: display as a open typing box - <input type="text">

``Multiple`` class describe the number of selections that customers can made.
> *values*
``false``: customers could select only **one** option from the modifier.
``numbers``: customers could select **``numbers``** options from the modifier. e.g. If the ``number`` is 2, it means customers could select two options from the modifier.
``true``: customers could select **unlimited** options from the modifier.

### Modifier Structure Overview

- Item Modifier Title
  Modifier Description (if applicable)
  - Modifier Option *Price*

### Modifier References

[``<modifier_bread>``](/modifier/modifier_bread.md)
[``<modifier_bread_burger>``](/modifier/modifier_bread_burger.md)
[``<modifier_cheese_extra>``](/modifier/modifier_cheese_extra.md)
[``<modifier_coffee>``](/modifier/modifier_coffee.md)
[``<modifier_coffee_cond>``](/modifier/modifier_coffee_cond.md)
[``<modifier_combo_drinks>``](/modifier/modifier_combo_drinks.md)
[``<modifier_combo_drinks>``](/modifier/modifier_combo_drinks.md)
[``<modifier_combo_side>``](/modifier/modifier_combo_side.md)
[``<modifier_marketplace_size>``](/modifier/modifier_marketplace_size.md)
[``<modifier_protein_extra>``](/modifier/modifier_protein_extra.md)
[``<modifier_protein>``](/modifier/modifier_protein.md)
[``<modifier_smoothie>``](/modifier/modifier_smoothie.md)
[``<modifier_smoothie_vegan>``](/modifier/modifier_smoothie_vegan.md)
[``<modifier_toppings_extra>``](/modifier/modifier_toppings_extra.md)