### A script to encrypt/decrypt and modify Diablo III saves

This script is a WIP for modifying Xbox One, PS4, and Switch saves for Diablo III


An example of how to mod gold would work like this (this is the only thing implemented ATM):

`python D3Edit.py -i account.dat -o account_mod.dat -s 0 --gold 999999999`

```
usage: D3Edit.py [-h] -i IN_FILE [-o OUT_FILE] [-s SLOT]
                 [--gold GOLD]
                 [--blood-shards BLOOD_SHARDS]
                 [--reusable-parts REUSABLE_PARTS] [--arcane-dust ARCANE_DUST]
                 [--veiled-crystals VEILED_CRYSTALS]
                 [--deaths-breath DEATHS_BREATH]
                 [--forgotten-souls FORGOTTEN_SOULS]
                 [--khanduran-runes KHANDURAN_RUNES]
                 [--caldeum-nightshade CALDEUM_NIGHTSHADE]
                 [--arreat-war-tapestries ARREAT_WAR_TAPESTRIES]
                 [--corrupted-angel-flesh CORRUPTED_ANGEL_FLESH]
                 [--westmarch-holy-water WESTMARCH_HOLY_WATER]
                 [--hearts-of-fright HEARTS_OF_FRIGHT]
                 [--vials-of-putridness VIALS_OF_PUTRIDNESS]
                 [--idols-of-terror IDOLS_OF_TERROR]
                 [--leorics-regrets LEORICS_REGRETS]
                 [--vengeful-eyes VENGEFUL_EYES]
                 [--writhing-spines WRITHING_SPINES]
                 [--devils-fangs DEVILS_FANGS]
                 [--all-currencies ALL_CURRENCIES]

A script to encrypt/decrypt and modify Diablo III saves

optional arguments:
  -h, --help
                        show this help message and exit
  -i IN_FILE, --in-file IN_FILE
                        The account file you want to work with
  -o OUT_FILE, --out-file OUT_FILE
                        The account file you want to output to

selection:
  -s SLOT, --slot SLOT
                        The slot ID you want to work with

modifications:
  --gold GOLD
                        Set the amount of gold
  --blood-shards BLOOD_SHARDS
                        Set the amount of blood shards
  --reusable-parts REUSABLE_PARTS
                        Set the amount of reusable parts
  --arcane-dust ARCANE_DUST
                        Set the amount of arcane dust
  --veiled-crystals VEILED_CRYSTALS
                        Set the amount of veiled crystals
  --deaths-breath DEATHS_BREATH
                        Set the amount of death's breath
  --forgotten-souls FORGOTTEN_SOULS
                        Set the amount of forgotten souls
  --khanduran-runes KHANDURAN_RUNES
                        Set the amount of khanduran runes
  --caldeum-nightshade CALDEUM_NIGHTSHADE
                        Set the amount of caldeum nightshade
  --arreat-war-tapestries ARREAT_WAR_TAPESTRIES
                        Set the amount of arreat war tapestries
  --corrupted-angel-flesh CORRUPTED_ANGEL_FLESH
                        Set the amount of corrupted angel flesh
  --westmarch-holy-water WESTMARCH_HOLY_WATER
                        Set the amount of westmarch holy water
  --hearts-of-fright HEARTS_OF_FRIGHT
                        Set the amount of hearts of fright
  --vials-of-putridness VIALS_OF_PUTRIDNESS
                        Set the amount of vials of putridness
  --idols-of-terror IDOLS_OF_TERROR
                        Set the amount of idols of terror
  --leorics-regrets LEORICS_REGRETS
                        Set the amount of leoric's regrets
  --vengeful-eyes VENGEFUL_EYES
                        Set the amount of vengeful eyes
  --writhing-spines WRITHING_SPINES
                        Set the amount of writhing spines
  --devils-fangs DEVILS_FANGS
                        Set the amount of devil's fangs
  --all-currencies ALL_CURRENCIES
                        Set all currencies to the given value
```

Credits:
> https://github.com/fry -> Diablo III Protobin Decompiler