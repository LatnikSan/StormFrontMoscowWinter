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
 4. Planes up to BR 3.3 avaible in the mission.
 5. Spawn scores (points) added.
 6. ETA to front line increased for all teams.
 7. Ground forces which are not mandatory to destroy aren't showin on map.
 8. Some hints are added.

RUS:

 1. ���������� ��������� ��������� ����� ����� ��������� � 5 �� 3.
 2. ������ �� ���� ������ ������ ���� �� ������������ ���������� ����� ���� ���������. 
 3. ����� - �� ������ ����� ������ ��������� �� ����� ���� ��� �������������.
     ���������� �����, ������� ������ ������� �� ����������� ���� ����������,
     ���� ��� ���� ��������� ������������.
     ���� ������������ ����� � ������� ������, ��� �������������� ������� ����� ������ (�����),
     ��� ������������ ����� ����� ������. � ��������� ������� ������� ����������� ���� 5 �����. 
 4. ��������� �������� ���������� �� 3.3.
 5. ��������� ���� �����������.
 6. ��������� ��������� ����� ����������� � ������ ������,
     � ����� ����� ���������� �� ����� ������.
 7. �������� ����, ����������� ������� �� ��������� ��� ������� ������, ������ �� ���������� �� �����.
 8. ��������� ��������� ���������.

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