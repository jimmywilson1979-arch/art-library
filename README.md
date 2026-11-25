# Art Library

Pictures made for my projects, kept in one place so any app can use them.

**Browse:** https://jimmywilson1979-arch.github.io/art-library/ (search, tap a picture to copy its link or download it)

## What's here
| Folder | What |
|---|---|
| `cards/nature/` | 50 animals and sea creatures |
| `cards/dinosaurs/` | 24 dinosaurs |
| `cards/space/` | the Sun, planets, dwarf planets and moons |
| `cards/christmas/` | 26 festive pictures |
| `mystery/` | 23 pictures from the "Who ate the cake?" mystery game: rooms, suspects, objects, table |
| `roll-on/kingdom/` | 36 fantasy kingdom places and objects (villages, castles, Dragon's Rest, crystal ball, quest scroll, treasure) plus 8 round player tokens (dragon, unicorn, wizard, crown, shield, bow, fairy, horse), made for Roll On |
| `roll-on/northpole/` | 36 North Pole places and objects (Snowdrift Lane to Santa's Grotto, sleigh stops, Christmas Eve, the Naughty Corner, cracker, elf scroll, elf hut, chocolate coins) plus 8 round player pieces (Santa, snowman, reindeer, elf, penguin, present, gingerbread, bell), made for Roll On |
| `roll-on/xmas/` | 18 Save Christmas pictures (Santa's Workshop, igloo, elf store and puzzle box, present sack, deep snow, polar bear, ice cave, avalanche, lighthouse, sleigh tracks, head elf, star gazer, Mrs Claus, reindeer, midnight clock, Santa's sleigh) plus 4 round hero pieces |
| `roll-on/dragon/` | 20 Dragon's Mountain pictures (mountain forest, path, stream, ruins, camp, treasure nook, hermit's hut, riddle and rune stones, giant web, wolf den, goblin cave, rockslide, high peak, scorched rocks, the red dragon waking, knight, wizard, healer, ranger) plus 4 round hero pieces |
| `roll-on/island/` | 24 desert-island pictures for Treasure Island: beach, jungle, lagoon, shipwreck, chests, parrot, map piece, quicksand, snakes, cave, rockfall, lookout tower, the X, the storm, and four heroes (captain, lookout, ship's doctor, explorer with a monkey) |
| `buzz-in/rounds/` | 24 quiz round title cards for Buzz In (pictures round the edges, plain middle for the round name) |
| `buzz-in/frames/` | 8 picture frames with see-through middles (gold, wooden, crayon, Christmas, silver, seaside, jungle, space) as WebP and PNG. Each middle is exactly 3:4; `frames.json` gives where it sits (left/top/right/bottom as a share of the frame's width) |
| `twenty-four-doors/` | 4 tall phone backgrounds (snowy village, birch forest, toy town, town square) and 8 painted advent door fronts with blank plaques, for Twenty-Four Doors |
| `who-is-it/` | 24 friendly head-and-shoulders portraits on a cream background, all different (hair colour and style, glasses, hats, beards, earrings), made for Who Is It? in Head to Head |
| `robot/` | concept pictures of the Claude home robot (phone head on a charcoal-and-gold body), photo-style, made to show what the finished product could look like |
| `pip/` | Pip, the red robot hero of the platformer game (bold outlined cartoon style): a hero picture, 12 separate poses with see-through backgrounds in `pip/poses/` (idle, blink, land, happy, run 1–6, jump, spin, hurt, tumble), and the game-ready sprite sheet `pip-game-sheet.png` with its `.json` |
| `pip/v2/` | Upgraded glossy Pip made with ChatGPT (Nov 2026) for Bounce Brawl: the official front-facing reference `pip-v2-reference-front.webp`, plus 16 action poses from 4 sheets, see-through backgrounds. Sheet 1 (`pip-v2-s1-*`: punch, slam landing, dash, flying kick) is the chosen look, with the ring on his antenna; sheet 2's fist pump is the win pose. Full sheets are in `originals/pip-v2-chatgpt-sheet1–4.webp` |
| `bounce-brawl/fighters/` | Bounce Brawl V1 fighters made with ChatGPT (Nov 2026): the 6-fighter line-up at true sizes, and front references for Boulder, Bonk, Zippa, Gloop and Frostbite (Pip's is in `pip/v2/`), and each fighter's 8 game poses (idle, run, jump, punch, dash, slam, hurt, win, all facing right) in a sub-folder per fighter (`pip/`, `boulder/`, `bonk/`, `zippa/`, `gloop/`, `frostbite/`); Gloop also has a puddle pose and a separate fist, and Zippa's jump is a wall-cling (wall erased; the original with the wall is kept) |
| `pip/enemies/` | Pip's enemies in the same style: Gloop (purple slime, now a legless oozing blob – the old legged poses are kept too), Buzzbot (flying robot bug), Clanker (wind-up tin crab), 4 poses each with see-through backgrounds, plus game-ready sheets; Captain Clank, the pirate crab boss of World 2 (stand, claws up, throw, dizzy) |
| `pip/world/` | Pip's world: batteries, golden battery, shield orb, heart, blocks, spring, checkpoint flags, finish star, moving platform (see-through), the sunny sky, a seamless hills strip, and 48px game tiles (`game-*.png` are the in-game sizes) |
| `pip/world2/` | Pip World 2 Sandy Shores: barrel, sand strip, pier plank, palm tree, seagull (2 flaps), sea urchin, jellyfish, power-ups (rocket boots, battery magnet, speed boost), diving helmet – all see-through – and the seaside background |
| `pip/world3/` | Pip World 3 Frosty Peaks, made with Sprixen: penguin-bot (waddle + belly slide), snowman-bot (throw), ice bat-bot (fly) and the Yeti-Bot boss (walk, ground pound, dizzy), each as a single picture plus animation sheets, and the game-ready sheets |
| `pip/world4/` | Pip World 4 Junkyard Factory, made with Sprixen: rust-rat (run), spring hopper (hop), spark drone (hover), the Scrap King boss (walk, magnet, slam, overheat) and the sunset factory background, plus game-ready sheets |
| `pip/world5/` | Pip World 5 Cloud Kingdom, made with Sprixen: storm-cloud bot, propeller bird, balloon bot, Queen Buzz boss (fly, dive, dizzy) and the cloud castle background, plus game-ready sheets |
| `pip/bosses-hurt/` | Hurt (stomped) animations for all five Pip bosses – King Gloop, Captain Clank, Yeti-Bot, Scrap King, Queen Buzz – made with Sprixen, plus game-ready sheets. New Sprixen skies are in `pip/world/` (sunny) and `pip/world3/` (snowy) |
| `flags/` | every country's flag (271, incl. Wales, England, Scotland, EU, UN), square versions in `flags/square/`, names and capitals in `flags/flags.json` (flag-icons, MIT licence) |
| `originals/` | the full-size Gemini sheets, exactly as made |
| `library.json` | a list of every picture with its name and file, for apps to read |

## Using a picture in a project
`https://jimmywilson1979-arch.github.io/art-library/cards/nature/lion.webp`

Pictures are 640px wide WebP, named after what they show.

## Making more in the same style
Made in the free Gemini app. Ask for a **4 × 3 grid of 12 tiles** with thin white gaps, and keep using the same Gemini chat so the style matches:

> Storybook illustration for a children's picture book: warm hand-painted gouache and watercolour look, soft lighting, rich but gentle colours, the subject shown whole and centred with a simple painted background. Same style in every tile. No text, no letters, no numbers, no labels.

Then send the sheet to Claude to cut up and add here. If Gemini writes names on the tiles anyway, Claude crops them off. Landscape scenes are cropped to about 3:2 (640 × 465).
