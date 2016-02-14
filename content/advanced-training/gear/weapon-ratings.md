+++
date = "2016-02-10T13:33:43-05:00"
tags = ["weapons"]
title = "Play Style Weapon Ratings"

[images]
  backdrop = ""
  icon = ""
  main = "/images/general/guns.jpg"
  thumbnail = ""
+++

Based on the specs of each weapon in Rainbow Six Siege, we developed algorithms to evaluate a weapons score relative to various play styles. Below are the different play styles and a description of what is considered in determining a weapons score for each one.

You can view all of the weapons with ratings on the [Operator Gear]({{< ref "advanced-training/gear/index.md#primary-weapons" >}}) page.
<!--more-->

## Score Properties

- Maximum value possible is 100
- Minimum value possible is 0
- The higher the score, the potentially more effective the weapon will be for the relative role
- Scores of 80 - 100 should be very effective for the relative role

## Weapon Scores

Each weapon score below has been designed to predict the effectiveness of a weapon when used in a role or play style. The score evaluates the importance of certain attributes that promote the relative role, e.g. giving a higher score to a weapon for having an [ACOG Sight]({{< ref "acog-sight.md" >}}) if it is to be used for sniping.

### Marksman Score

A marksman is someone who generally stays back at a farther distance from the rest of the team. Its an operator who carefully lines up their sights on the target and takes the shot. They need a weapon with a long range scope and to be able to drop an enemy with one to three hits as their opportunity to get the shot may not last long.

For this score, we rank weapons based on the following attributes:

- higher score if available [ACOG Sight]({{< ref "acog-sight.md" >}})
- higher score the higher the damage output

{{% scores "marksman" %}}

View all weapons with ratings on the [Operator Gear]({{< ref "advanced-training/gear/index.md#primary-weapons" >}}) page.

### Rogue Score

A rogue operator is someone who needs stealth and mobility to successfully navigate near enemy operators. They sneak into position and listen, waiting for an enemy to come within range for an ambush. The operator has to take them out and immediately sneak back into hiding or make haste for a new position.

For this score, we rank weapons based on the following attributes:

- higher score if available [Suppressor]({{< ref "suppressor.md" >}})
- higher score for higher rate of fire
- higher score for higher mobility

{{% scores "rogue" %}}

View all weapons with ratings on the [Operator Gear]({{< ref "advanced-training/gear/index.md#primary-weapons" >}}) page.

### Support Score

A support specialist is someone who is up on near the front line with the rest of the assault team. They need a weapon that can shred walls and barricades providing suppressive or cover fire for teammates, allowing them to adjust their positions or move in to aid an injured squad mate.

For this score, we rank weapons based on the following attributes:

- higher score the higher the ammo capacity
- higher score for higher rate of fire

{{% scores "support" %}}

View all weapons with ratings on the [Operator Gear]({{< ref "advanced-training/gear/index.md#primary-weapons" >}}) page.
