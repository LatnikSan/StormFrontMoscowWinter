User Mission for SB/RB multiplayer battles at War Thunder game

https://warthunder.com/en

https://warthunder.ru/ru/

History and detailed description (in Russian):
https://forum.warthunder.ru/index.php?/topic/261243-proekt-storm-front-ili-khochu-takuyu-missiyu-v-protivostoyanii/

v1.3

ENG:

 1. Front line have only 3 positions for now.
 2. NEW - At each front line you can destroy one of the front-line airfields.
 3. NEW - One base for bombing added per front line.
 4. NEW - Airfields remove when unused and can disappears right below you.
 5. Planes up to BR 3.3 avaible in the mission.
 6. Spawn scores (points) added.
 7. ETA to front line increased for all teams.
 8. Ground forces which are not mandatory to destroy aren't showin on map.
 9. Some hints are added.

RUS:

 1. Количество возможных положений линий фрона уменьшено с 5 до 3.
 2. Теперь на всех линиях фронта один из прифронтовых аэродромов может быть уничтожен. 
 3. НОВОЕ - На каждой линии фронта добавлено по одной базе для бомбардировки.
     Количество очков, которые теряет команда за уничтожение базы ограничено,
     база при этом перестает возрождаться.
     База возрождается сразу с началом миссии, при восстановлении участка линии фронта (холда),
     при установлении новой линии фронта. В остальных случаях таймаут возрождения базы 5 минут. 
 4. NEW - Неиспользуемые аэродромы убираются с карты и могут пропасть прямо под вами.
 5. Доступные самолеты ограничены БР 3.3.
 6. Добавлены очки возрождения.
 7. Увеличено растояние между аэродромами и линией фронта,
     а также между сражениями на линии фронта.
 8. Наземные силы, уничтожение которых не требуется для прорыва фронта, больше не отмечаются на карте.
 9. Добавлены некоторые подсказки.

Tech log:

removed p02 and m02 ground battles
added 1 base to bomb per front line
afs_update - independent launch
afs_set, clr - totally reworked
bmb_set, check, init, reset - totally reworked
added constants:
cst_A_front_line_state_max
cst_B_front_line_state_max
cst_A_bmb_bases_per_front_line_plus1_max
cst_B_bmb_bases_per_front_line_plus1_max
cst_tnt_to_hp_multiplier