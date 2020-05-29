# Changelog
작업하면서 변경점은 모두 이 기록에 저장합니다.
할수있으면 영어로도 추가내용을 적기

이 체인지 로그 포맷은 [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)를 기반으로 작성됨,

## [Unreleased]
### Added
- 새로운 종족 쌍두 오우거 추가. 2개의 무기와 2개의 목걸이를 낄 수 있음. 그러나 방패를 낄 수 없음
  - Added two-headed ogre(playable). Can wear 2 weapons and 2 amulets. But you can't wear a shield
  
- 새로운 종족 천사 추가. 세 선신 중 하나를 믿고 시작함. 악신들의 미움을 사서 끊임없는 징벌과 싸운다.
  - Added angel(playable). A holy species who starts by believing in one of the three good gods.
    To be hated by evil gods and to fight infinity wrath
  
- 새로운 종족 멘티스 추가. 적에게 접근할때 자동으로 점프 공격을 함
  - Added mantis(playable). leap attack automatically when approaching an enemy
  
- 새로운 종족 레서리치 추가. 높은 강령 적성, 빠른 마나회복, 27렙때 와일드매직을 얻음
  - Added Lesser-Lich. high necromancy skill, high mana regen, wild magic when 27 level
  
- 파켈라스 추가 및 리워크. 이제 마나를 제약하지않으나 마음대로 업그레이드할 수 있는 프로토타입 로드를 선물함. 상세 설명은 [이 곳](https://github.com/kimjoy2002/crawl/issues/60)을 확인
  - Added pakellas and rework.  No longer constrained mana, but presents a prototype rod that can be upgraded at will. Click [here](https://github.com/kimjoy2002/crawl/issues/60) for details
  
- 독물의 추출, 증산 추가
  - Added Fulsome Distillation, Evaporate spell
  
- 독물의 추출을 위한 나쁜 포션(독, 맹독, 맹물, 불안정 변이)추가. 추출에서만 나오는 포션이며 자연 드랍되면 버그임
  - Added bad potions (poison, strong poison, water, unstable mutation) for Evaporate. only create by Fulsome Distillation

- 5레벨 독/파괴 마법, 에링야의 뿌리송곳 추가. 2~5의 거리를 지니는 스마이트형 물리복합 마법
  - Added Eringya's Rootspike, level 5 posion/conjuraion spell. 2~5 range smite-targeting spell. partially ignores poison resistance
  
- 7레벨 독 마법, 올그레브의 마지막 자비 추가. 시야안의 적을 선택하여 독중첩만큼 데미지를 주고 사망시 3X3범위의 무속성 폭발이 발생 
  - Added Olgreb's Last Mercy, level 7 posion spell. Choosing an enemy in the LOS, dealing damage equal to the amount of poison, and causes a 3X3 irresistible explosion upon death
  
- 5레벨 독/참 마법, 독선 추가. 지속시간동안 적을 근접공격시 맞은 적의 독저항을 중첩하여 깎을 수 있음
  - Added Poison Gland, level 5 posion/charm spell. For the duration, melee attack makes a attacked creature more vulnerable to poison

- 5레벨 변이/대지 마법. 벽 위장. 벽으로 파고들어서 잠자는 적을 깨우지않고 이동, 암살 하는게 가능해진다.  
   - Added Wall Camoflage, level 5 earth/transmutation spell. Melting into the wall makes it possible to move and stab without waking the sleeping enemy.

- 베오그의 새로운 권능 오크 추종자 되돌리기 추가. 선택한 오크 추종자를 오크 광산으로 즉시 전송한다. 
   - Added Beogh ability "return Orcish Followers". Immediately send the selected orcish follower to orcrish mines.
   
- 다음 신들이 6성때 무기에 브랜드를 부여해줌: 이레델렘눌(흡혈), 마크레브(혼돈), 트로그(안티매직), 지바(slimifying), 엘리빌론(pacifing), 체브리아도스(sluggish), 진(실버)
   - The following gods give the weapon a brand at 6 stars: Yredelemnul(vampiric), Makhleb(chaos), Trog(antimagic), Jiyva(slimifying), Elyvilon(pacifing), Cheibriados(sluggish), zin(silver)

- 독마법 최종티어 책인 거장의 회고록 추가
  - Added The Memoirs of the Virtuoso, the highest level Poison book
  
- 가방 아이템 추가. 아이템을 자유롭게 넣고 뺄 수 있는 유틸리티 아이템임
  - Added bag. Miscellany that provide additional storage space

- 마법 복구 : 가속, 특이점, 정령소환, 컨트롤 언데드
  - rollback Haste, Singularity, Summon Elemenatal, Control Undead
  
- 로드 복구 (iron, clouds, ignition, inaccuracy, shadows)
  - rollback rod (iron, clouds, ignition, inaccuracy, shadows)
  
- 전기디스크 복구
  - rollback disc of storms
  
- 아카식 레코드 마법책 복구
  - rollback akashic record
  
- 스토커 복구. 벽과 융합하는 새로운 마법과 함께
  - rollback stalker. with magic of transforming into a wall

- 라바 오크, 지니, 하이엘프, 마운틴드워프 복구
  - rollback Lava orc, Djinni, HighElf, MountainDwarf
  
- 레펠 미사일 복구. 이제 경갑을 입어야 사용할 수 있음
  - Added and rework repel missle. now, need to wear light armor to cast RMsl
  
- 둔기 특성화. 이제 둔기로 적을 죽일때마다 시체를 넉백시킬 수 있고 넉백된 시체는 적에게 데미지를 줌
  - add mace&flail ability. Now every time you kill an enemy with a mace&flail weapon, you can knock back the corpse, and the knocked back corpse deals damage to the enemy
  
- 변이 시체, 고기를 되돌림
  - rollback mutagenic corpse
  
- 분수를 다시 마실 수 있게 됨
  - Become able to drink fountain again
  
- auto_bag_items rc 옵션 추가. 주운 아이템을 자동으로 가방에 아이템을 넣는 옵션 ( example auto_bag_items = !? )
  - Added auto_bag_items rc option. Option to automatically put picked items in a bag

- 새로운 메인 타이틀 이미지 추가 (logal-image)
  - Add new title artwork (logal-image)

### Changed
- 오우거 둔기적성 +3으로 변경 (기존 -1)
  - Ogre Maces & Flails aptitude changed to +3 (prev -1)

- 메뉴 컬러링을 위한 태그(fixed_artefact, random_artefact) 추가. 픽다트의 기본 색깔을 노란색으로 변경
  - Added Menu/colouring Prefixes(fixed_artefact, random_artefact). Changed the default color of the fixed artefact to yellow
  
- 아쉔자리의 "아이템 저주"는 이제 여러 아이템을 저주시킬 수 있다.
  - Ashenzari's 'curse item' curse multiple equipment.
  
- 오조크브의 갑옷은 이제 움직여도 풀리지않음
  - Ozocubu's armor no longer looses when moved
  
- 링 오브 파이어는 이제 맞은 적에게 이너파이어를 검
  - Ring of Fire now casts Inner Fire on enemies it hits.
  
- 고통의 상처의 소음이 줄어듬
  - excruciating wounds's noise reduction
  
- 네멜렉스의 원더덱이 돌아옴. 이제 네멜렉스는 다시 발동술을 사용함
  - Nemelex's deck of wonder is comeback. Now Nemelex uses the evocation again.
  - 돌아온 카드들 (xom, mercenary, alchemist, bargain, sage, portal, trowel, experience, helm, shuffle)

- 드라코들은 이제 아래 종류의 갑옷을 입을 수 있음. All dracos can wear armour listed below
  - 로브 Robe
  - 가죽 갑옷 Leather armour
  - 트롤 가죽 갑옷 Troll leather armour
  - 모든 종류의 용 비늘 갑옷 all kinds of dragon scale

- 드라코들은 갑옷술을 수련 할 수 있음. All draco can train armour skill.
  - 적성은 -3. Aptitude is -3.

- 드라코들은 시작할 때 뒤틀린 몸 변이를 가짐. All draco have deform mutation at start.

- 드라코 전원 14레벨에 영구 비행 변이를 얻도록 변경
  - All dracos will gain big wing mutation at xl 14
  
- 펠리드와 옥토포드는 스카프를 낄 수 있게 됨
  - Allow octopode, felid wields a scarf

- Inhibited Regeneration 변이 변경, 시험적으로 딥 드워프는 자연 회복이 이루어짐
  - Change Inhibited Regeneration. and deep dwarf allow regen naturally (experimental)
  
- 강령술사는 스타팅책에 컨트롤 언데드와 고통의 상처를 들고 시작함
  - necromancer starting book now contains 'control undead' and 'excruciating wounds'

- 아군 소환물이 다시 LOS밖의 적과 싸울 수 있음
  - Allow friendly summons from attacking out of LOS

- 다시 시야 밖에서 구름이 사라지지않음
  - Don't erase clouds outside of LOS

- 이제 던전 5층이 되기전까진 구덩이 함정이 등장하지않음
  - Shaft traps will not spawn before D:5
  
- 트로그의 분노는 이제 처형도끼 베이스에 +rage임. 또한 안티매직 오라를 가짐
  - Wrath of Trog is now executioner axe with +rage. also has antimagic aura

- 저주받은 해골 타일 변경 (kormed)
  - A new curse skull tile (kormed)

### Removed

- Nothing


### 0.25 Featrue
- 갑옷 장착시 AC를 보여주는 인터페이스 추가
  - Improve armour AC change descriptions
  
- 독 중첩단계에 따른 타일 이펙트 추가
  - can see poison level mons and player
  
- 에어스트라이크는 주변의 빈공간의 수만큼 데미지가 증가됨
  - Airstrike damage now scales so it's greater the more unoccupied squares there are surrounding the target.

- 오조크브의 냉장고의 데미지 33%증가되고 시전자에게 데미지를 주지않음
  - Ozocubu's Refrigeration does 33% more damage on-average and no longer harms the caster
  
- 베놈 메이지의 기본책인 The Young Poisoner's Handbook은 이제 이그나이트 포이즌을 들고 시작함
  - The Young Poisoner's Handbook now contains Ignite Poison.
  
  
  
[Unreleased]: https://github.com/kimjoy2002/crawl/compare/0.24.1...HEAD