# Chatteroids
We built this Twitch-integrated Self-Avoiding A.I. live on Twitch!

## Instafluff ##
> *Come and hang out with us at the Comfiest Corner on Twitch!*

> https://twitch.tv/instafluff

> https://twitter.com/instafluffTV

## Credits ##
Thank you too all the participants of this project!

**Instafluff, Amarogine, DEAD_P1XL, SirBillPaxton, sparky_pugwash, Zealouszam, RokvirStormshield, PinataHero, LerajeRandom, TheHungerService, MacabreMan2, mr_grey, vic_likadabooty, Instafriend, SourBeers, jellydance, FuriousFur, neniltheelf, GSOcreative, KitAnnLIVE, funkysquid, OhMyGoogles, AntiViGames, ElysiaGriffin, Pixelgourmet, celtsy, deFunc, Kyoslilmonster, rdmusser, DutchGamer46, madridr4, GeoRevilo, muppen1976, Mikeystea, ItsNaomiArt, CuriousJess, H1lbert, Shaosan, Deitypotato, nightsilas, JustinZedly, oopserv_, Reflect1dentity, kaisuke, 0xCOUCH, PokemoHero, LuckyPheathers, nallaj, tuoppio, BlueJellyCam, DrJavaSaurus, mallesbixie, RebelRoxie, MerlinLeWizard, vPositive, gursimar98, BungalowGlow, Yonlionz, MrRayKoma, malfunct, Bustopher, recursivechat, artkison, The_Modern_Alchemist, cottonsmiles, MisterHex, wietlol, SoundBoy264, WorkingChef, kingswerv, dragonhyperking, coolguyinthehouse123, BassCornbread, MiJennaTailya, SomaPills, InSanityParty, losthewar, Kara_Kim, AgroKragle**

And to everyone that helped improve Pikachu to v2!

**sparky_pugwash, Instafluff, sethorizer, Instafriend, AntiViGames, Neenkatttt, Mikeystea, That_MS_Gamer, Kara_Kim, BungalowGlow, KitAnnLIVE, JokO__, Kisa__d1_1b, LuckyPheathers, videorob25, nightsilas, carbon_add, Royoushi_, Stay_Hydrated_Bot, Neo_TA, neniltheelf, RIKACHET, MrRayKoma, Infanate_Reapage, RokvirStormshield, wietlol, MacabreMan2, mintyLyra, TheHungerService, ItsNaomiArt, zAtaraxia, GeoRevilo, rdmusser, Cats4Hire, nallaj, DvDty, DegenerateDD, SgtStateside, pryce_of, HonestDanGames, sciondragons, donaldwm, Xynal, FablesGames, o0Corps0o, JoelB83, nineam, InSanityParty, Gwozilla, ElysiaGriffin, Kyoslilmonster, Thedudeskee, blackdawn1980, MalForTheWin, Deitypotato, Amarogine, deFunc, 0xCOUCH, PokemoHero, mint_spider, HollaAtYaBoys, DorkzillaI, SumBoi_, Yonlionz, CriticalKnit, rawbeanstalk, thechoconut_, WorkingChef, Flippo13, joaquimley, LambenceeAaron, ravavyr, losthewar, tuoppio, vPositive, KevinTheUnicorn8, FranC312, Liayda, funkysquid, kingswerv, Tornadogenesis**

And to the wonderful friends that helped train Pikachu with our own Neural Network!

**shadowcraft5, TheodoraStyles, Sezzadactyl, racynop, lukys4w, LifeEdge, MarcusMabus, TheShadowSoldiers, fikapaus, LudgoniousLego, sparky_pugwash, Stefizhere, Terunkaa, BungalowGlow, SourBeers, Xalent, That_MS_Gamer, blackdawn1980, Pearcington, antitran, AntiViGames, Rappaport0, Deitypotato, matuzalem_svk, alphanoob_barbarian, lordarion76, LuckyPheathers, ChatTranslator, Fr3aksenpai, uninsulted, Guardiadelaluna, WudsyWudsyWudsy, Instafriend, jellydance, wietlol, KitAnnLIVE, Amarogine, Videokid, Chlapicek99, koralina_211, SleepyMia, Jayromi, Maayainsane, ShekaGotU, FerynTV, Miraellyn, khristyragerunnernet, allwine, SuperChihuahua, angry_mOOky, pprofl, QeraiX, valeia, madybraps, Nintao, reverandsaul, iAmNotFromHere, Glen_Metthews_, sinnomon, SoraWill, radiocaf, Moopaloo, bilko2006, emplinos, DorkzillaI, DrJavaSaurus, NiecyRed, joaquimley, MacabreMan2, mixmg1, Seeroro, BountyHunterLani, malfunct, Hugginator, Zug74, EmpressBooty, Dr_Heresy, Alphairri, SoG_Cuicui, nightsilas, NinjaFalcon_2, WCLeeArt, Instafluff, tuoppio, TheHungerService, Sockelo, LambenceeAaron, kindogrec, ItMeGlaze, Wormius51, fydo, markopolodev, Dl2agon, newb_saibot, ElysiaGriffin, rurutu, HonestDanGames, MirikitaniKatt, catsanovaa, Infanate_Reapage, InSanityParty, Zorchenhimer, 0xCOUCH, rdmusser, Kyoslilmonster, muppen1976, Jakobgjertsen1, dyng89, TheThirdWalker, Neo_TA, MisterHex, deFunc, brandan_f, T_r_a_e_l, funkysquid, ericbrunet1990, sethorizer, DEAD_P1XL, PokemoHero, lolcathorst, Pixelgourmet, username_grfi, Inventus1, HeyOhKei, hormithenormie, kaisuke, Kara_Kim, mmtaleghani, CaseyGeske, BatskyStarman, FuriousFur**

## Instructions ##

1. Install NodeJS - [https://nodejs.org/en/](https://nodejs.org/en/)
2. Open the directory in a Command Prompt/Terminal
3. Install Dependencies: `npm install`
4. Get a Twitch Chat OAuth Password Token - [http://twitchapps.com/tmi/](http://twitchapps.com/tmi/)
4. Create a file named `.env` that looks like this:
```javascript
PORT=8000
TWITCHUSER=[YOUR-USERNAME-HERE]
OAUTH=[YOUR-OAUTH-PASS HERE] # e.g. OAUTH=oauth:kjh12bn1hsj78445234
```
5. Run Server: `npm start`
6. View the webpage from your web browser! [http://localhost:8000](http://localhost:8000)
