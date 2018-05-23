-- This text explain what I changed in this mod and why I did it!

-- If you dont like it, mod it!!!

-----------------------------------------------------------------
Where to place the files in Ubuntu:
/home/simoes/.local/share/Paradox Interactive/Hearts of Iron IV/mod

Other helpfull Folders:
/home/simoes/.steam/steam/steamapps/common/Hearts of Iron IV/common/units
/home/simoes/.steam/steam/steamapps/workshop
/home/simoes/.local/share/Paradox Interactive/Hearts of Iron IV/save games

-----------------------------------------------------------------
WINDOWS:
1) Usar o aplicativo pra criar MODs do proprio jogo acessivel na parte de MODS NA INTERFACE INICIAL
Ela cria o diretorio mod (C:\Users\Simoes\Documents\Paradox Interactive\Hearts of Iron IV\mod\) mais uma subpasta com o nome do seu mod (conversion - no meu caso)

2) La dentro tem um arquivo com papo furado e na subpasta tem que respeitar o CAMINHO exato dos arquivos que queremos modificar no jogo (no meu caso era: \common\units\equipment\)

3) DAi' e' so' botar uma copia dos arquivos la dentro que o jogo usa esses ao inves dos do jogo!!

--> Tentei editar diretamente os arquivos do jogo e NAO consegui!!



----------------------------------------------------------------
MOD FILES:        supported_version="1.5.*"     Cornflakes
----------------------------------------------------------------

ADJUSTS:

	NUCLEAR_PRODUCTION_SCALE = 900,			-- *** Changed from 365 +1 nuclear_production gives 1 nuke per year
=> Why I did it: To make much more difficult to produce atomic bombs

	MIN_MANPOWER_RATIO = 0.5,			-- *** Changed from 0.15 Min manpower ratio to show manpower alert
=> Why I did it: To stop that horrible messages abot low manpower with 1M men still available

	BASE_RESEARCH_POINTS_SAVED = 60.0,		-- *** Changed from 30.0 Base amount of research points a country can save per slot.
=> Why I did it: To give us more time to concentrate on micromananging our troops without having to look to everything

	MAX_DIVISION_SUPPORT_WIDTH = 2,			-- *** Changed from 1 Max width of support in division designer.
=> Why I did it: So we can put more suport batalhons to our divisions (It is not prety, but works fine!!)

	MAX_ARMY_EXPERIENCE = 50000,			-- *** Changed from 500 Max army experience a country can store
	MAX_NAVY_EXPERIENCE = 50000,			-- *** Changed from 500 Max navy experience a country can store
	MAX_AIR_EXPERIENCE = 50000,			-- *** Changed from 500 Max air experience a country can store
=> Why I did it: To give us more time to concentrate on micromananging our troops without having to look to everything

	AIR_WING_MAX_SIZE = 50000, 			--- *** Changed from 1000 Max amount of airplanes in wing
=> Why I did it: After 1943 on we usually have 10000 or more airplanes... This way we can make a very big air wing just once and then divide it into many smaller wings

	CAPACITY_PENALTY = 1,				-- *** Changed from 2 scales penalty of having overcrowded bases.
=> Why I did it: To reduce the time we have to pay attention to it! When we are bombarded by ennemies

	CARRIER_STACK_PENALTY = 8,			-- *** Changed from 4 The most efficient is 4 carriers in combat. 5+ brings the penalty to the amount of wings in battle.
=> Why I did it: Cos it doesent make any sense!! Many battles in WWII have more than 4 carriers anyway!

	MAX_SAVED_FOCUS_PROGRESS = 70,			-- *** Changed from 10 This much progress can be saved while not having a focus selected
=> Why I did it: To give us more time to concentrate on micromananging our troops without having to look to everything

---------------------------------------------------------------------
SUPORT COMPANIES:

Also changed Suport Companies abilities:
1) tech_maintenance_company => Got twice as much reliability
=> Why I did it: The loss of equipment during movment was kind of 10 times the loss in combat... 

2) tech_field_hospital => Got twice as much experience_loss_factor
=> Why I did it: The loss experience during combat was insane! The more your troops fight, the smallest their experience gets! Ok, I know it happens becouse the new troops that arrive to replace KIO are fresh... but it was to much!

3) tech_logistics_company => Got twice as much supply_consumption_factor
=> Why I did it: Geting out of supply during battle was bothering me too much!! They are OK one moment and then they step in a new state and start getting 20 times less suply!!! I had to play with it a little!!


--------------------------------------------------------------------
CONVERSION

Added a lot to the list of conversion... Mostly Planes and tanks!!
=> Why I did it: If you dont have the resources such as metal... to build new tanks, why not scrap old ones to recilce their metal!!



--------------------------------------------------------------------
WOUNDED

Canceled effects of skill_bonus_factor for getting WOUNDED and SICK:
=> Why I did it: They get sick and wounded ALL THE TIME!!! It is too much unrealistic!!!

sick = { ## skill_bonus_factor = -0.5
	 cannot_use_abilities = 1
wounded = { ## skill_bonus_factor = -0.5
	    cannot_use_abilities = 1
		

