# Overview:
__each month, make a remake a game from a certain time(increasing in recency), and talk about how it's creators prevent misuse__
### Some points to cover
___
#### At a High Level:
- what counts as "misuse?"
  - threat model depends on game type, consequences of cheats vs cost to fight them, release date*, etc
    - (not the best example, but GDB didn't come out until about 1986 - 8 years after Magnavox Odyssey 2)
- effects beyond irritating cheaters
  - reduces "moddability"
    - the glory that is [Hannah Montana Linux](http://hannahmontana.sourceforge.net/) would not be possible without Linux's open-source-ness
- that's all well and good, but how do I secure my game?(general advice)
  - great video here - https://www.youtube.com/watch?v=hI7V60r7Jco
  - will add more as I learn more, but generally:
    - only send necessary data(can't hack what you don't have)
    - find balance between security and usability - server can't process _everything_, but don't for example, let the client decide how much money it has
    - ...
#### Monthly:
- how did they original creators implement it?
  - gold mine - https://www.youtube.com/c/TechRules
  - older games --> custom hardware
  - newer games --> standardized platforms = standardized security?
    - cracking game might require you beat game platform, making it harder
- how could it be improved technically(remembering limitations of time period)?
  - does it need to be improved?
    - it's not "100% unhackable," but nothing is
  - could it be faster?
- how could the UX be improved?
  - interestingly, bigger hurdle for linux gaming is now anticheat support, not techical capabilities of OSes
    - _X_ _could_ run, but the anticheat won't function 100% and might report usage as "hacking" or simply quit the game
  - intrusiveness
  - Valorant's Vanguard = good example
    - extremely high privleges, runs 24/7(even when game isn't running)
      - obvious privacy issues for black-box with root access
        - "trust me bro"
      - plus, if Vanguard's compromised, attackers have a 24/7 "legit" backdoor into the computer
