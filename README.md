# ASCII Geese

Uses [TerminalTextEffects](https://chrisbuilds.github.io/terminaltexteffects/) and [Asciinema](https://docs.asciinema.org/) to create cast/GIFs of Kubernetes SIG-Honk geese based on the original by [p4ck3t0](https://github.com/p4ck3t0)


## Commands


Example to create the crypto goose

First run TTE on the base_goose.txt file
```bash
tte -i base_goose.txt decrypt --typing-speed 5 --final-gradient-stops 326CE5
```

Then run `asciinema rec` to create the cast. Then run `agg` to convert to a GIF
