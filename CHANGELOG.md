### A word on designing brand new weapons for GTFO

The goal of weapon additions to Thloatere is to explore meaningful and fresh design space that hasn't been filled yet. So, of course, it becomes increasingly difficult to design new balanced weapons that don't tread old ground, as fun as it is.

GTFO weapons only have so much design space to explore while remaining adjacent to vanilla.

Especially when some gimmicks just end up not working out in practice...

So unless I figure out, I dunno, a new SentryGun to experiment with or something... never say never, but I get the feeling that v2.x will be the final major version of Thloatere...

As a bonus, let me tell you about some of the ideas that didn't make it in.
- **Short Rifle v1**: A testing iteration of the Short Rifle. An attempt to keep the original idea of the Short Rifle alive, but as an autogun instead of some weird hybrid of an autogun and specialist. It was actually really fun to play the precision semi-auto autogun style into Strikers and Shooters, but Chargers proved too big of a roadblock for the gun to remain fun. There's a difference between "suboptimal into Chargers" and "completely unworkable into Chargers"... I guess you could consider the Boltthrower a spiritual successor to this, of all things??? Nowadays, the Short Rifle draws more from the Pistol and is actually workable into Chargers.
- **Ultralight Melee**: Scrapped very quickly because the Knife is basically the limits of how light you can make a melee before it becomes pointless. At least I tried it.
- **High Caliber Shotgun**: A testing iteration of the High Caliber Rifle. The High Caliber Rifle was inspired by Fortnite's Hunting Rifle and Ranger Shotgun and takes from both equally. But at some point while testing it, I wasn't sure of how powerful it would be, so I decided to try turning it into the Ranger Shotgun... one shot, seven pellets... yeah, so this was far too strong... at least it was fun?
- **High Caliber SMG**: Inspired by Helldivers 2's Reprimand, this was a really slow firing SMG that hit really hard with unworkable amounts of random spread and damage dropoff. It felt really good to fire and actually did well, but this just ended up basically being "Machine Pistol (Low RPM)" so I scrapped it.
- **SemiBurst Machinegun**: A testing iteration of the Accelerator Rifle. Did you know GTFO has an unused firemode? "SemiBurst x" firemode is where you can shoot x shots, then incur a long cooldown before you can shoot again. So, a burst-fire weapon but the burst itself is semi-auto. This is actually really impractical for combat and ends up feeling too much like either burst or semi...
- **SemiBurst Rifle**: An attempt to make something less Accelerator Rifle more DMR with the SemiBurst firemode... it still had the same problem of not being able to properly settle down into SemiBurst and feeling too much like either of the above...
- **Anti-Air Cannon**: More Helldivers 2. The Autocannon in that game had selectable firemodes between APHET (works like the GTFO Autocannon) and Flak (low-armour-penetrating explosive), so I decided to try and work in a shrapnel-firing version of the Autocannon. This was, once again, too good... or too bad! And it ended up feeling like a rehash of the Choke Mod Shotgun but just with the Autocannon's mag size and reload... oops...
- **Chain Gun**: This was, more or less, a minigun. It was completely uncontrollable and made the Heavy SMG look tame by comparison... it basically ended up just being an even bigger Heavy SMG, so I decided to leave being the Machinegun to the Machinegun and being the Heavy SMG to the Heavy SMG instead of trying to forcefully marry them...
- **Autocannon Sentry**: A scaled up 3-burst sentry gun that killed one Striker per shot. Ultimately just ended up basically being a weird Sniper Sentry??? Might revisit it... I don't know...

### v2.0.1

i can never get these right </3

Bug fixes:
- Removed even more unused shotgun stats from the High Caliber Rifle to placate the WeaponStatShower gods
- Made the description for the Chain Boltthrower on the website not suck

### v2.0.0

New weapons!
- Boltthrower
  - New Wild West rifle-style Primary weapon that slings armour-piercing stakes, staggering up to two enemies per shot and instantly killing Strikers with a single headshot. Requires careful maintenance, as its reload and rate of fire are slow, and its damage and ammo reserves low.
- Chain Boltthrower
  - Machinegun-type Special weapon with an agonizingly long charge-up. Launches stakes that deal incredibly high damage to one enemy, but can't hold many and takes a while to reload.

Bug fixes:
- Removed space from manufacturer name of High Capacity Pistol
- Correctly beefed up muzzle flash and shell casing of High Caliber Rifle, Autocannon, and HEL Rifle

### v1.1.0

Balance changes:
- High Caliber Rifle
  - Hipfire spread: 1.0 -> 0.5
    - The High Caliber Rifle's quick draw, single shot, and quick reload cancel encourage firing the weapon the moment the prisoner finishes changing to it, which conflicted with the rather heavy hipfire spread by single-shot-reload standards.

Bug fixes:
- Correctly applied the following changes:
  - Bat
    - Light attack damage: 3.0 -> 4.0
    - Attack stamina costs all reduced to 0%
  - Sledgehammer
    - Charge time: 1.8 -> 1.75
    - Charged attack stamina cost: 5%/5% -> 2.5%/2.5%
    - Light attack stamina cost: 0%/0% -> 2.5%/1.25%
    - Push attack stamina cost: 5%/5% -> 2.5%/2.5%
  - Spear
    - Light attack damage: 2.0 -> 2.5
    - Charged attack stamina cost: 5%/5% -> 2.5%/2.5%
    - Light attack stamina cost: 0%/0% -> 2.5%/1.25%
    - Push attack stamina cost: 5%/5% -> 2.5%/2.5%
- Fixed a bug where the Shotgun Sentry had 1/12 the intended ammo reserves
- Removed unused shotgun stats (holdover from testing) in the High Caliber Rifle and Autocannon statblocks to prevent WeaponStatShower from having an existential crisis
- Website now displays the correct Precision Rifle firemode change
- Website no longer displays redundant bursts/second information about the HEL Scattergun
- Credit to CatAssTrophy & co. for finding and helping fix these bugs

### v1.0.2

Fixes a bug where Thunderstore didn't go to v1.0.1???

### v1.0.1

Apparently I'm not immune to the day zero patch curse </3

- Fixes a really cursed looping audio bug with the Autocannon
- Updates the README with audiogroup changes I accidentally forgot

### v1.0.0

Release at last :D