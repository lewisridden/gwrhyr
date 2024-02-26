# Gwrhyr, ([interpreter of languages.](http://ipa-reader.xyz/?text=Gwrhyr&voice=Gwyneth))
A Dactyl-family keyboard with an opposed thumb cluster featuring a HAT switch design.

# Project rationale
Thumbs operate in opposition to the rest of the hand, thus it makes sense for the thumb cluster of the keyboard to exist on a plane matching this angular distinction. Further, to minimise travel of the thumb within the key cluster to solve the perceived limitation in many ergonomic designs whereby the single digit serves a large radius of keys to provide utility, a multi-way HAT switch is utilised as a main component of the thumb cluster, in addition to a single traditional switch to maximise use density for the thumb. 

## Lessons from the Iris layout
Gwrhyr seeks to extend and iterate on several of the ergonomic lessons learnt from designing and using the Iris keyboard. The most effective design choices that I found were successful in the Iris were as follows;

1. Don't require users to tuck their thumbs. Placing utility in a way that requires thumbs move under the hand requires either a rotation or angling of the hand or an uncomfortable extension of the thumb.
2. Organic semi-rest positions are key for both comfort and utility in the thumb cluster.
3. Don't require nested layers for reasonable utility, useful keys should ideally be either at the fingers or _one held modifier at most_ away. While there are both flat and keywell boards that have been purpose-designed for embedded modifier schemes such as [Miryoku's home row mods, Suraj N. Kurapati's bilateral improvements to which are linked](https://sunaku.github.io/home-row-mods.html), this is not one of them. In Gwrhyr the dense mods are in the new thumb cluster, with all keys accessible from rest/neutral position without notable extension.

## Keywell design benefits
Moving to a keywell design allows for solving several design challenges that are unlikely to be entirely resolvable on a single-plane keyboard design. 

1. Gwrhyr uses a thumb cluster on a tight angle to the main keywell to solve for thumb opposition
2. Gwrhyr accounts for pinky length disparity by using a smaller radius on the outermost columns handled by these digits. Further, to account for the position on the hand, there is an enhanced stagger on these columns.
3. A more aggressive tenting angle is present to allow for both a more neutral rest for the hand and a more natural radius of motion for the thumb to be present while acting on the keys.
4. Using a HAT switch on the thumb cluster allows for maximum density of controls without additional motion of the thumb. The HAT is placed in such a way that the switch is accessible to and along the conventional axis of the thumb, reachable without being out of the way, and angled to be usable in all directions. HAT switches for thumb control have been shown to be effective on designs such as the [Fulcrum](https://github.com/dschil138/Fulcrum)


##

Gwrhyr runs in a similar vein and design intent to the [DMOTE](https://github.com/veikman/dactyl-keyboard) keyboard by Viktor Eikman and other forks of Tom Short's [ManuForm variant](https://github.com/tshort/dactyl-keyboard) of Matthew Adereth's original [Dactyl](https://github.com/adereth/dactyl-keyboard) keyboard which use an opposed thumb cluster. The main keywells were generated using [rianadon](https://github.com/rianadon/Cosmos-Keyboards)'s Cosmos beta. 

# License
Copyright © 2015–2023 Matthew Adereth, Tom Short, Lewis Merriman et al.

This repository's models are distributed under the GNU AFFERO GENERAL PUBLIC LICENSE Version 3.
The QMK firmware found in the `firmware` directory is distributed under [GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.html).
