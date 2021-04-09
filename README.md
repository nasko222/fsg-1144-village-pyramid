Filtred Seed Glitchless generator for 1.14.4

Generates village and desert temple next to spawn (0, 0?)

NOT OFFICIAL FOR SPEEDRUN.COM (yet?)


COMPILE: gcc csprng.c -I./include -L./libs -lgcrypt -lgpg-error -L. -lcubiomes -lm -lpthread -Wl,-rpath=./libs/ -lminecraft_nether_gen_rs -o seed