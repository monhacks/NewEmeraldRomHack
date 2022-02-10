# Pokémon Emerald

This is a rom hack of Pokemon Emerald using pokeemerald-expansion as its base: https://github.com/rh-hideout/pokeemerald-expansion.

# TODO

- implement ability description label in the summary screen.
- Include ORAS dex Pokemon like Budew and Dusknoir.
- New Pokemon moves.
	- animations for new moves
	- Add the new moves to the move tutors lists.
- Remove the OHKO moves.
- Expand and add new areas, including adding some new wild Pokemon for the area.
- Rework aspects of the Battle Frontier. Change the Battle Palace to be themed around inverse type matchups. Rework the battle Pokemon list. 
- Add methods to make training easier. Super vitamins (giving 60 EVs per stat), IV boosters and nature mints to be added and accessable.
- Add credits of people whos tutorials and work you have used in the game.

# Changelog

- Many post gen 3 features from pokeemerald Expansion are in this ROM.
- Pokemon can have up to 3 active abilities, dependant on their species. Many Pokemon have had their ability set updated (TODO: make a list of ability stat changes somewhere).
- New moves and abilities (listed below).
- Some vanilla abilities updated to make them more useful (listed below).
- Berry tree drop rates are tripled.
- Number of Feebas spots is tripled.
- TMs have infinite use.
- Ice types have their special defense boosted by 50% in hail.
- Removed badge boosts
- Pokemon will attempt to learn a new move upon evolution.
- Level up requirements of many Pokemon have been tweaked. Starters evolve a little later. Pokemon with unnecessarily late evolutions (like the fossils, Rufflet, Deino) evolve earlier (TODO: list them below).
- Changes to learnsets of some Pokemon (TODO: make list).

# New Abilities

- Volume Up: Power of sound based moves have increased by 33%. Used by Loudred/Exploud.
- Lava Body: Attackers who make contact will get inflicted with burn. Used by Slugma/Magargo.
- Wildfire: Sp.Atk raises one stage after fainting an opponent. Used by Quilava/Typlosion.
- Miracle Blossom: User and ally restore 1/8 HP at the end of every turn. Used by Bayleef/Meganium/Xerneas.
- Scorching Heart: Power of Fire type moves increased by 50%. Used by Solrock/Groudon/Solgaleo.
- Ice Affinity: Power of Ice type moves increased by 50%. Used by Lunatone/Kyogre/Piplup/Prinplup/Empoleon/Lunala.
- Aquatic: Power of Water type moves increased by 50%. Used by Dhelmise/Clobbopus/Grapploct.
- Gardener: Power of Grass type moves increased by 50%. Used by Floette/Florges.
- Prickly Thorns: Effectively like Rough Skin. Used by Cacnea/Cacturne.
- Aura Sense: User shudders if opponent has super-effective move. Also ignores evasive boosts from target. Used by Riolu/Lucario.
- Soul Siphon: Contact from user steals 1/8 HP from target and heals for the same amount. Used by Duskull/Dusclops/Dusknoir/Palossand/Dhelmise/Corsola(Galarian).
- Bad Luck: Opponent cannot land crits and less likely to land status moves against user. Used by Spiritomb/Cofagrigus.
- Wickedness: User super-effective moves do 25% more damage. Used by Hitmonchan/Mismagius/Braixen/Delphox.
- Spinning Body: User's physical moves remove field hazards and raise speed one stage. Used by Pineco/Forretress/Hitmontop.
- Evergreen: User takes half damage from Ice type moves and is immune to hail. Used by Grotle/Torterra/Skiddo/Gogoat.
- Hematophagy: Healing effects from drain moves increased by 50%. Used by Zubat/Golbat/Crobat/Yveltal.
- Swordmaster: Power of sword/blade moves increased by 33% (Leaf Blade/X-Scissor/Sacred Sword/Razor Shell/Secret Sword/Solar Blade/Behemoth Blade). Used by Leafeon/Dewott/Samurott/Cobalion/Terrakion/Verizion/Keldeo/Fomantis/Lurantis/Zacian.
- Supercooled: User's Ice type moves are super-effective against Water types. Used by Lapras/Glaceon/Aurorus.
- King's Might: User doesn't need to recharge on moves like Hyper Beam and Giga Impact. Used by Slaking.
- Pleasant Dreams: Heals sleeping Pokemon 1/4 HP every turn. Used by Cresselia.
- Wish Maker: User creates a wish on entry. Used by Jirachi.
- Heart Swap: If user makes contact with target, stat changes are swapped. Used by Manaphy.

# Updated Abilities

- Trace: copies the opponent’s highest rated ability that the user doesn’t already have.
- Receiver: copies fainted ally’s strongest ability that the user doesn’t already have.
- Neutralising Gas: Neutralises target abilities unless it is a banned ability like Stance Change.
- Mummy: replaces all the contact attacker’s abilities with just the Mummy ability.
- Wandering Spirit: replaces each respective ability with the attacker if hit by a contact move unless it is a banned ability.
- Neutralizing Gas: Nullifies other Pokemon abilities. User abilities still active.
- Shell Armor/Battle Armor: Also reduces damage of neutral effective moves by 25%.
- Sand Veil: Increases Sp.Def instead of evasion by one stage.
- Snow Cloak: Increases Defense instead of evasion by one stage.
- Slow Start: Timer tuned down to 1 turn from 5.
- Sweet Veil: Also ignores evasion boosts from target.
- Corrosion: Also makes user's poison moves super effective against steel types.
- Solar Power: No longer decreases HP. Power modifier changed to 25% from 50%.
- Normalize: Buffed to 30% from 20%.
- Liquid Voice: Also powers up sound moves by 20%.
- Cursed Body: Now always disables the move for just the next turn.
- Suction Cups: Also traps target when user strikes it with a contact move.
- Keen Eye: Also increases move accuracy by 30%.
- Illuminate: Also ignores opponent evasion boosts.
- Damp: Also grants user immunity to powder based moves and abilities.
- Multitype: Also includes Adaptability and Filter effects.
- Victory Star: User and ally accuracy set to 100%.

# New Moves

- War Dance: User have their own attack and speed rise by 1 stage and attempts to confuse the opponent. Learned by Sentret/Furret/Yungoos/Gumshoos via level up.
- Flint Blade: 75 BP, 100% Acc, Rock type, increased crit ratio. Boosted by Swordmaster ability. Learned by Leafeon/Dewott/Samurott/Cobalion/Terrakion/Verizion/Keldeo/Fomantis/Lurantis/Zacian/Rockruff/Lycanroc/Gigalith/Onix/Steelix/Omanite/Omastar/Kabuto/Kabutops/Aerodactyl/Anorith/Armaldo/Shieldon/Bastiodon/Binacle/Barbaracle/Rhyhorn/Rhydon/Rhypherior/Aggron/Kleavor/Seviper.
- Flare Crash: 100 BP, 100% Acc, Fire type, reduces user's speed by one stage. Learned by Flareon/Growlith/Arcanine/Ponyta/Rapidash/Quilava/Typhlosion/Entei/Torkoal/Tepig/Pignite/Emboar/Heatmor/Litten/Torracat/Incineroar/Scorbunny/Raboot/Cinderace/Charmeleon/Charizard/Combusken/Blaziken/Numel/Camerupt/Vulpix/Ninetales/Monferno/Infernape/Heatran/Litleo/Pyroar/Houndour/Houndoom/Carkoal/Coalossal/Groudon/Luxio/Luxray/Phanpy/Donphan/Absol/Skuntank/Zebstrika/Darmanitan/Solgaleo/Boltund.
- Singularity: A protect move that lowers the speed of foes who make contact by one stage. Learned by Gardevoir.
- Serpent Dance: Increases the user's special attack and speed by one stage. Learned by Seviper/Milotic/Serperior/Dunsparce/Ekans/Arbok/Huntail/Gorebyss/Rayquaza/Silicobra/Sandaconda/Giratina/Gyarados.

# Updated Moves

- Simple Beam: Replaces opponents abilities with the Simple ability. If opponent has a banned ability such as Stance Change, then they will still keep that ability but the others will be replaced with Simple.
- Worry Seed: Replaces opponents abilities with just the Worry Seed ability. If opponent has a banned ability such as Stance Change, then they will still keep that ability but the others will be replaced with Worry Seed.
- Entrainment: Replaces opponents abilities with the user’s abilities. If opponent has a banned ability such as Stance Change, then they will still keep that ability but the others will be replaced with the user’s abilities in their respective slot.
- Skill Swap: swaps the user abilities with the target abilities.  If opponent has a banned ability such as Stance Change, then they will still keep that ability but the others will be replaced with the user’s abilities in their respective slot.
- Gastro Acid: Neutralises target abilities unless it is a banned ability like Stance Change.
- Role Play: replaces the user’s abilities with the target’s abilities.
- Core Enforcer: Nullifies opponent’s abilities.

# Credits

- The fine people who worked on pokeemerald and pokeemerald-expansion
- DizzyEggg
- LOuroboros
- BuffelSaft
- Blackforest92
- ExpoSeed
- SBird1337
- aarant
- SonikkuA-DatH
- Xavion3
- GriffinR
- kleeenexfeu
