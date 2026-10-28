# WoW-Forever-Guide
## 1. Facțiuni

### 1.1. Alliance

| Race | ![Druid](https://img.shields.io/badge/Druid-FF7D0A?style=flat-square) | ![Hunter](https://img.shields.io/badge/Hunter-ABD473?style=flat-square) | ![Mage](https://img.shields.io/badge/Mage-69CCF0?style=flat-square) | ![Paladin](https://img.shields.io/badge/Paladin-F58CBA?style=flat-square) | ![Priest](https://img.shields.io/badge/Priest-FFFFFF?style=flat-square) | ![Rogue](https://img.shields.io/badge/Rogue-FFF569?style=flat-square) | ![Shaman](https://img.shields.io/badge/Shaman-0070DE?style=flat-square) | ![Warlock](https://img.shields.io/badge/Warlock-9482C9?style=flat-square) | ![Warrior](https://img.shields.io/badge/Warrior-C79C6E?style=flat-square) |
|------|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Dwarf |  | X |  | X | X | X | X |  | X |
| Gnome |  |  | X |  | X | X |  | X | X |
| Human |  | X | X | X | X | X |  | X | X |
| Night Elf | X | X |  |  | X | X |  |  | X |

### 1.2. Horde

| Race | ![Druid](https://img.shields.io/badge/Druid-FF7D0A?style=flat-square) | ![Hunter](https://img.shields.io/badge/Hunter-ABD473?style=flat-square) | ![Mage](https://img.shields.io/badge/Mage-69CCF0?style=flat-square) | ![Paladin](https://img.shields.io/badge/Paladin-F58CBA?style=flat-square) | ![Priest](https://img.shields.io/badge/Priest-FFFFFF?style=flat-square) | ![Rogue](https://img.shields.io/badge/Rogue-FFF569?style=flat-square) | ![Shaman](https://img.shields.io/badge/Shaman-0070DE?style=flat-square) | ![Warlock](https://img.shields.io/badge/Warlock-9482C9?style=flat-square) | ![Warrior](https://img.shields.io/badge/Warrior-C79C6E?style=flat-square) |
|------|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| Orc |  | X | X |  |  | X | X | X | X |
| Tauren | X | X |  |  |  |  | X |  | X |
| Troll |  | X | X |  | X | X | X | X | X |
| Undead |  |  | X | X | X | X |  | X | X |

## 2. Stats — Ce inseamna fiecare

In WoW exista **5 stats primare**. Ele nu fac nimic direct — ele se **transforma** in altceva (HP, mana, damage, armor, crit). De aia acelasi item poate fi BIS pentru unul si gunoi pentru altul.

> ⚠️ **Important:** Formulele de mai jos sunt cele din **Classic (1.12)**, pe care **WoW Forever** le foloseste ca baza. Serverul poate avea ajustari proprii — verifica mereu pe **Character Sheet** (tasta `C`) si da **hover** pe stat ca sa vezi exact ce iti da TIE, pe clasa TA, la level-ul TAU.

### 2.1. Tabel rapid

| Stat | Ce face, pe scurt | Cine beneficiaza cel mai mult |
|---|---|---|
| 🔴 **Stamina** | Iti da **HP** | 🛡️ **Flav** (tank) — dar e bun pentru **TOTI** la leveling |
| 💪 **Strength** | Iti da **Attack Power** (damage melee) | 🗡️ **Sebi** (Paladin Ret), 🛡️ **Flav** |
| 🏃 **Agility** | **Attack Power** (doar Rogue & Hunter), **Crit**, **Dodge**, **Armor** | 🗡️ **Adi** (Rogue), 🏹 **Necu** & **Octi** (Hunter) |
| 🔵 **Intellect** | Iti da **Mana** + **Spell Crit** | 💚 **Vladi** (Priest), 🏹 **Ali** (Warlock) |
| ✨ **Spirit** | **Regen** de mana si HP **in afara luptei** | 💚 **Vladi** (Priest) |

---

### 2.2. 🔴 Stamina — Cat traiesti

**Ce face:** Iti creste **Health Points (HP)**. Atat. Dar e cel mai simplu si cel mai universal stat din joc.

**Cum se calculeaza:**
```
Primele 20 de Stamina  →   1 HP / punct
Fiecare punct PESTE 20 →  10 HP / punct
```
Formula pentru bonusul de HP este:
```
Bonus HP = MIN(Stamina, 20) × 1 + MAX(Stamina - 20, 0) × 10
HP total = HP de baza + Bonus HP
```

`MIN` inseamna „alegem valoarea mai mica”, iar `MAX` nu lasa partea de dupa 20 sa devina negativa.

**Exemplu cu 100 Stamina:**
```
Primele 20 puncte: 20 × 1  = 20 HP
Urmatoarele 80 puncte: 80 × 10 = 800 HP
Bonus total: 20 + 800 = 820 HP
```

Asadar, 100 Stamina inseamna **+820 HP**, peste HP-ul de baza dat de clasa si level.

**La fel pentru toate clasele** — nu exista clasa care sa ia mai mult HP per punct de Stamina.

| Cine | Cat conteaza | De ce |
|---|---|---|
| 🛡️ **Flav** (Warrior Prot) | ⭐⭐⭐⭐⭐ | **Stat-ul #1 al tankului.** Mai mult HP = Vladi are timp sa te prinda cu heal. Fara HP, mori intre doua heal-uri. |
| 🏹 **Ali** (Warlock) | ⭐⭐⭐⭐ | Isi transforma HP-ul in mana (**Life Tap**) si in Healthstone. Pentru el Stamina e **indirect si mana**. |
| 🗡️ **Adi**, **Sebi**, **Tipu** (melee) | ⭐⭐⭐ | Stau in fata, iau AoE si mobii care scapa de pe tank. |
| 💚 **Vladi** (Priest) | ⭐⭐⭐ | Nu pentru damage — ca sa **supravietuiasca** unui hit pana il scoate cineva. |
| 🏹 **Necu** / **Octi** (Hunter) | ⭐⭐ | Stau departe, dar la leveling solo conteaza. |

> 💡 **Regula de leveling:** Pana pe la level 40, **Stamina e bun pentru oricine**. Daca mori mai rar, levelezi mai repede. Nu refuza un item doar pentru ca are "doar" Stamina.

---

### 2.3. 💪 Strength — Damage de melee

**Ce face:** Iti da **Attack Power (AP)**, care se traduce in damage cu arma. Si **Block Value**, daca porti scut.

**Cum se calculeaza:**
```
Warrior, Paladin, Shaman, Druid    →  2 Attack Power / Strength
Rogue, Hunter, Mage, Priest, Lock  →  1 Attack Power / Strength

Bonus AP = Strength × AP primit pentru 1 Strength
Block Value = Strength / 20
**NU CRESTE BLOCK CHANCE(%) !**

14 Attack Power = +1 DPS cu arma
```

**Exemplu cu 30 Strength:**
```
Sebi (Paladin): 30 × 2 = 60 Attack Power
Adi (Rogue):    30 × 1 = 30 Attack Power
Block Value:    30 / 20 = 1,5 (valoarea afisata poate fi rotunjita)
```

Pentru damage-ul mediu al armei, conversia aproximativa este:
```
Bonus DPS = Attack Power / 14
```

Deci 28 AP inseamna aproximativ `28 / 14 = 2 DPS` in plus. **Sebi (Paladin)** ia dublu AP din Strength fata de **Adi (Rogue)**; acelasi item poate avea efect diferit.

| Cine | Cat conteaza | De ce |
|---|---|---|
| 🗡️ **Sebi** (Paladin Ret) | ⭐⭐⭐⭐⭐ | **Stat-ul lui #1.** 2 AP / punct, iar Ret loveste rar si tare — vrea numere mari pe hit. |
| 🛡️ **Flav** (Warrior Prot) | ⭐⭐⭐⭐ | 2 AP / punct + **Block Value** + mai mult damage = **mai mult threat**. Tankul fara threat nu e tank. |
| 🗡️ **Tipu** (Enh Shaman) | ⭐⭐⭐⭐⭐ | **Stat-ul lui #1.** 2 AP / punct, in timp ce Agility ii da **0 AP**. Enhancement traieste din Attack Power. |
| 🗡️ **Adi** (Rogue) | ⭐⭐ | Doar **1 AP** / punct. Nu e rau, dar Agility e net superior pentru el. |
| 🏹 **Necu** / **Octi** (Hunter) | ⭐ | **NU** creste damage-ul **ranged**. Aproape inutil. |
| 💚 **Vladi** / 🏹 **Ali** | ❌ | Tehnic iau 1 AP / punct, dar **nu lovesc niciodata cu arma**. Strength **NU** da spell damage. |

> ❌ **Greseala clasica:** "Am gasit item cu +Strength si sunt Priest, il iau ca e numarul mare." **Nu.** Strength nu face absolut nimic pentru un caster.

---

### 2.4. 🏃 Agility — Cel mai complex stat

**Ce face:** **4 lucruri deodata** — de aia e atat de puternic pentru clasele potrivite.

**Cum se calculeaza:**
```
1. ARMOR
      Bonus Armor = Agility × 2   (la TOATE clasele)

2. ATTACK POWER
   a. Ranged Attack Power
      Hunter                            →  2 ranged AP / Agility

   b. Melee Attack Power
      Rogue, Druid (cat form)           →  1 melee AP / Agility
      Warrior, Paladin, Shaman, casteri →  0 melee AP / Agility

3. CRIT  (aproximativ, la level 60)
      Warrior / Paladin / Shaman / Druid  →  ~20 Agility = 1% crit
      Rogue                               →  ~29 Agility = 1% crit
      Hunter                              →  ~53 Agility = 1% crit (ranged)

4. DODGE
      Dodge% = bonusul de dodge oferit de Agility la level-ul tau
```

**Exemplu cu 40 Agility:**
```
Armor pentru oricine: 40 × 2 = 80 armor
Hunter AP:            40 × 2 = 80 ranged AP
Rogue AP:             40 × 1 = 40 melee AP
Warrior/Paladin AP:   40 × 0 = 0 AP din Agility
```

Crit-ul si dodge-ul nu se calculeaza doar impartind la un numar fix pentru toate level-urile. De aceea valorile `~20`, `~29` si `~53` sunt aproximari pentru level 60.

> ⚠️ Valorile de **crit** se schimba cu level-ul si difera pe clasa. **Verifica pe Character Sheet**, nu te lua strict dupa numerele astea.

| Cine | Cat conteaza | De ce |
|---|---|---|
| 🗡️ **Adi** (Rogue Combat) | ⭐⭐⭐⭐⭐ | **Stat-ul lui #1, fara discutie.** Ii da AP **si** crit **si** dodge **si** armor. Combat traieste din crit-uri. |
| 🏹 **Necu** / **Octi** (Hunter) | ⭐⭐⭐⭐⭐ | **Stat-ul lor #1.** Ii da ranged attack power **si** crit. Hunterul e clasa cea mai dependenta de Agility din joc. |
| 🛡️ **Flav** (Warrior Prot) | ⭐⭐⭐⭐ | **Nu** pentru damage (0 AP!), ci pentru **Armor + Dodge** — tankul vrea sa fie lovit mai rar si mai slab. |
| 🗡️ **Tipu** (Enh Shaman) | ⭐⭐⭐ | **0 AP din Agility!** Doar crit (~20 Agi = 1%), armor si dodge. Bun, dar **Strength e mai bun**. |
| 🗡️ **Sebi** (Paladin Ret) | ⭐⭐ | 0 AP din Agility, dar primeste crit si armor. Clar secundar fata de Strength. |
| 💚 **Vladi** / 🏹 **Ali** | ❌ | Doar putin armor. Practic inutil. |

> 💡 **De retinut:** Agility **nu** da Attack Power la **Warrior, Paladin si Shaman**. Flav, Sebi si Tipu iau din el **doar** armor, crit si dodge — nu damage direct.

---

### 2.5. 🔵 Intellect — Cat de mult poti casta

**Ce face:** Iti da **Mana** si **Spell Crit**.

**Cum se calculeaza:**
```
Bonus Mana = Intellect × 15

Spell Crit  →  ~59,5 Intellect = 1%  (la level 60)

Bonus ascuns: creste viteza cu care urci WEAPON SKILL
```

**Exemplu cu 60 Intellect:**
```
Bonus Mana = 60 × 15 = 900 mana
Spell crit aproximativ = 60 / 59,5 = 1,01%
```

Mana de pe Character Sheet este:
```
Mana total = Mana de baza a clasei si level-ului + Bonus Mana
```

Intellect nu inseamna spell damage. El iti da o rezerva mai mare de mana si, indirect, iti permite sa casti mai multe spell-uri inainte sa ramai fara mana.

| Cine | Cat conteaza | De ce |
|---|---|---|
| 💚 **Vladi** (Priest Disc) | ⭐⭐⭐⭐⭐ | Mana = **cate heal-uri poate da**. Ramane fara mana → moare grupul. |
| 🏹 **Ali** (Warlock) | ⭐⭐⭐⭐ | Mana pool mare = mai multe spell-uri intre Life Tap-uri. |
| 🏹 **Necu** / **Octi** (Hunter) | ⭐⭐⭐ | **Da, Hunterul foloseste mana in Classic!** La leveling conteaza mult mai mult decat crezi. |
| 🗡️ **Sebi** (Paladin Ret) | ⭐⭐ | Mana pentru Seal-uri, Judgement si un heal de urgenta. |
| 🗡️ **Tipu** (Enh Shaman) | ⭐⭐ | Totems, Lightning Shield si heal-uri costa mana. |
| 🛡️ **Flav** / 🗡️ **Adi** | ❌ | Warrior foloseste **Rage**, Rogue foloseste **Energy**. **Nu au mana deloc.** Intellect = 0 pentru ei. |

> ❌❌ **CEA MAI MARE GRESEALA DE INCEPATOR**
>
> In **Classic**, Intellect **NU** iti creste damage-ul la spell-uri! Nu exista "spell power din Intellect" ca in expansion-urile noi.
>
> Damage-ul si healing-ul de spell vin **DOAR** din iteme pe care scrie explicit:
> - `+X Spell Damage and Healing`
> - `+X Healing`
> - `+X Damage` de scoala (Fire, Shadow, Frost...)
>
> Deci **Vladi** trebuie sa caute **+Healing**, iar **Ali** sa caute **+Shadow Damage** — nu doar Intellect.

---

### 2.6. ✨ Spirit — Regen intre lupte

**Ce face:** Iti regenereaza **mana** si **HP** — dar **doar cand NU castezi**.

**Cum se calculeaza (mana per tick de 2 secunde):**
```
Priest, Mage                             →  (Spirit / 4) + 12,5
Druid, Hunter, Paladin, Shaman, Warlock  →  (Spirit / 5) + 15
```

Formula se aplica la fiecare tick de 2 secunde, nu la fiecare lovitura sau spell:
```
Mana regen pe secunda = Mana regen pe tick / 2
Mana regen in 10 secunde = Mana regen pe tick × 5
```

**Exemplu pentru Vladi cu 80 Spirit:**
```
Mana pe tick = (80 / 4) + 12,5 = 32,5 mana
Mana pe secunda = 32,5 / 2 = 16,25 mana
In 10 secunde = 32,5 × 5 = 162,5 mana
```

Acest calcul este valabil doar cand regula celor 5 secunde permite regen-ul. Daca ai cheltuit mana recent, valoarea reala poate fi `0` pana iesi din acea fereastra.

> 🕒 **REGULA CELOR 5 SECUNDE (5-Second Rule)** — cel mai important mecanism legat de Spirit:
>
> **Din momentul in care cheltui mana, Spirit-ul tau NU regenereaza nimic timp de 5 secunde.**
>
> Daca Vladi da heal la fiecare 3 secunde, **Spirit-ul lui nu face absolut nimic**. De aia healerii buni invata sa lase pauze scurte intre heal-uri — ca sa intre in regen.

| Cine | Cat conteaza | De ce |
|---|---|---|
| 💚 **Vladi** (Priest Disc) | ⭐⭐⭐⭐⭐ | **Singurul care chiar traieste din Spirit.** Il tine in mana intre pull-uri si scurteaza pauzele de baut. Discipline are **Meditation** — talent care lasa o parte din regen sa mearga **si in timp ce castezi** (ocoleste partial regula celor 5 secunde). |
| 🏹 **Ali** (Warlock) | ⭐⭐ | Are **Life Tap** — isi face mana din HP. Spirit e mult mai slab pentru el decat pentru Vladi. |
| 🏹 **Necu** / **Octi** (Hunter) | ⭐⭐ | Ajuta intre pull-uri la leveling. |
| 🗡️ **Sebi** / 🗡️ **Tipu** | ⭐ | Marginal in dungeon. **La leveling solo conteaza mai mult** decat crezi — mai putine pauze de baut. |
| 🛡️ **Flav** / 🗡️ **Adi** | ❌ | Nu au mana. Spirit le da doar putin HP regen **in afara luptei** — aproape inutil. |

---

### 2.7. Ce stat vrea fiecare dintre noi

Ordinea in care sa va uitati la iteme. **Stanga = cel mai important.**

| Nume | Clasa / Spec | 🥇 Principal | 🥈 Secundar | ❌ Ignora complet |
|---|---|---|---|---|
| 🛡️ **Flav** | Warrior Protection | 🔴 **Stamina** | 💪 Strength → 🏃 Agility → *Defense* | 🔵 Intellect, ✨ Spirit |
| 💚 **Vladi** | Priest Discipline | *+Healing* → 🔵 **Intellect** | ✨ Spirit → 🔴 Stamina | 💪 Strength, 🏃 Agility |
| 🏹 **Ali** | Warlock Affliction | *+Shadow Damage* → 🔵 **Intellect** | 🔴 Stamina → ✨ Spirit | 💪 Strength, 🏃 Agility |
| 🏹 **Necu** | Hunter Beast Mastery | 🏃 **Agility** | 🔴 Stamina → 🔵 Intellect | 💪 Strength, ✨ Spirit |
| 🏹 **Octi** | Hunter | 🏃 **Agility** | 🔴 Stamina → 🔵 Intellect | 💪 Strength, ✨ Spirit |
| 🗡️ **Sebi** | Paladin Retribution | 💪 **Strength** | 🔴 Stamina → 🏃 Agility → 🔵 Intellect | ✨ Spirit |
| 🗡️ **Adi** | Rogue Combat | 🏃 **Agility** | 💪 Strength → 🔴 Stamina | 🔵 Intellect, ✨ Spirit |
| 🗡️ **Tipu** | Shaman Enhancement | 💪 **Strength** | 🏃 Agility → 🔴 Stamina → 🔵 Intellect | — |

> 💡 **La leveling (1–60), pentru TOATA lumea:** **arma** conteaza mai mult decat orice stat de pe armura. Un weapon upgrade bate 10 puncte de stat. Nu sta cu arma de level 12 cand esti level 30.

---

### 2.8. Stats derivate — ce vedeti pe Character Sheet

Astea nu se gasesc (de obicei) direct pe iteme — ele **rezulta** din stats-urile primare:

| Stat derivat | De unde vine | Ce face |
|---|---|---|
| **Attack Power** | Strength, Agility | `14 AP = +1 DPS` cu arma |
| **Armor** | Agility × 2 + armura purtata | Reduce damage-ul **fizic** |
| **Crit %** | Agility (melee), Intellect (spell) | Sansa de damage dublu |
| **Dodge %** | Agility | Eviti complet atacul |
| **Block %** | Scut + Strength | Blochezi o parte din damage |
| **Health** | Stamina | Cat traiesti |
| **Mana** | Intellect | Cate spell-uri poti da |

**Cum functioneaza Armor:**
```
Reducere damage % = Armor / (Armor + 400 + 85 × Level_Atacator)

CAP: maxim 75% reducere — mai mult armor peste cap nu face nimic
```

**Exemplu:** la 2.000 armor si un atacator level 60:
```
Reducere = 2000 / (2000 + 400 + 85 × 60)
         = 2000 / 7500
         = 26,67%
```

Cu alte cuvinte, un atac fizic de 1.000 damage devine aproximativ:
```
Damage primit = 1000 × (1 - 0,2667) = 733 damage
```

Formula foloseste level-ul **atacatorului**, nu level-ul tau. Armor-ul nu reduce damage magic.

> ⚠️ Armor-ul reduce **DOAR damage fizic**. **Nu** te apara deloc de magie — pentru aia ai nevoie de **Resistances** (Fire, Frost, Shadow, Nature, Arcane).

---

### 2.9. ✅ Checklist — Stats

- [ ] Toata lumea stie care e stat-ul ei **principal**.
- [ ] Toata lumea stie ce stat sa **ignore** complet.
- [ ] Toata lumea da **hover pe Character Sheet (`C`)** ca sa verifice valorile pe server.
- [ ] Nu dam roll pe iteme care nu ne folosesc (vezi tabelul 2.7).

---

## 3. Clase

## 3.1. Hunter 🏹

### 3.1.1. PvE — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **High Sustained DPS:** Damage constant si bun pe boss fights.<br>- **BUN RAU** pe solo leveling<br>- **Pull & Utilitate:** Feign Death si Freezing Trap ajuta la controlul pull-urilor. ! ATENTIE ! poti/puteti sa ne dati wipe usor | - **Ammo Dependency:** Are nevoie constant de arrows/bullets ( NU SUNT SIGUR DACA PE **FOREVER** EXISTA AMMO) <br>- **Pet Management:** Pet-ul poate da pull la add-uri daca nu il controlati bine<br>- **Threat Management:** Damage-ul mare poate face tank-ul sa piarda aggro.  **GRIJA** | 

### 3.1.2. PvP — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **Burst Bun** Aimed Shot si Multi-Shot dau tare intr-un window scurt.<br>- **Mana Pressure:** Viper Sting poate reduce mana casterilor si healerilor.<br>- **Pet Pressure:** Pet-ul adauga damage constant si forteaza adversarul sa reactioneze. | - **SLAB in Melee Range:** Daca te prinde o clasa Melee, iti pica maselele<br>- **Limited Defensive Options:** Are mai putine CD defensive directe fata de alte clase.<br>- **Pet Dependency:** O parte din pressure scade daca moare petul |

---

## 3.2. Priest ✨

### 3.2.1. PvE — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **Strong Heal**<br>- **Damage Prevention:** Power Word: Shield da absorb damage si castiga timp pentru window-uri de heal.<br>- **Group Utility:** Dispel Magic, Cure Disease si Power Word: Fortitude ajuta la cleanse la debuff-uri | - **Mana Management:** Healing-ul continuu mananca mana blana in dungeon-uri lungi.<br>- **Threat from Healing:** Heal-urile pot atrage aggro de la mobi daca tank-ul nu controleaza bine grupul. **!GRIJA FLAV!**<br>- **Low Armor:** Fiind Cloth, este vulnerabil daca este atacat direct. P.S.: O beleste grav |

### 3.2.2. PvP — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **Strong Defensive Healing:** Ne da heal drq :)) <br>- **Dispel Utility:** Anuleaza debuff-uri <br>- **Powerful Defensive Tools:** Power Word: Shield si Psychic Scream face space pentru healing sau backing | - **Focus Target:** Primu target de la inamici, trebuie protejat primul. Are prioritate! <br>- **Cast Interruptions:** Damage-ul primit si interrupt-urile pot impiedica healing-ul eficient.<br>- **Mana Pressure:** Daca adversarii prelungesc lupta, poate ramane fara resurse pentru heal-uri. |

---

## 3.3. Warlock 🔥

### 3.3.1. PvE — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **Strong DoT:** Corruption, Curse of Agony si alte DoT-uri tin damage constant <br>- **Healthstone & Soulstone:** Healthstone ofera o optiune de supravietuire, iar Soulstone poate permite o revenire dupa moarte daca ii da prepare.<br>- **Crowd Control & Utility:** Fear, Banish si curses ajuta la gestionarea mobilor | - **Soul Shard Management:** Trebuie sa gestioneze shards pentru anumite spells si utilitati.<br>- **Threat from DoTs:** Damage-ul aplicat pe mai multe tinte complica aggro-ul in pull-uri mari.<br>- **Limited Mobility:** Multe spells necesita cast time, iar Warlock-ul nu se misca ca un Rogue sau Mage. |

### 3.3.2. PvP — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **Sustained Pressure:**<br>- **Fear Control:** Fear poate scoate adversari din lupta <br>- **Strong Attrition:** Drain Life, Healthstone si pet-ul pot sustine supravietuirea in lupte prelungite. | - **Fear Limitations:** Fear poate fi eliminat, intrerupt sau poate avea eficienta redusa impotriva anumitor adversari.<br>- **Cast-Time Vulnerability:** Este vulnerabil la interrupt-uri si la presiune melee.<br>- **Resource Management:** Soul Shards si mana pot deveni o problema in lupte repetate. |

---

## 3.4. Paladin 🛡️

### 3.4.1. PvE — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **Powerful Blessings:** Blessing of Might, Blessing of Kings si Blessing of Salvation pot imbunatati DMG, Stats sau Threat Control<br>- **Emergency Support:** Lay on Hands poate salva un aliat in situatii critice.<br>- **Strong Utility:** Auras, Cleanse si Blessing of Protection ofera suport defensiv si ajuta grupul sa gestioneze anumite mecanici. | - **Mana Dependency:** Healing-ul si abilitatile consumatoare de mana pot limita eficienta in lupte lungi.<br>- **Lower Mobility:** Are putine optiuni de mobilitate pentru a urmari rapid tinte sau a evita mecanici.<br>- **Damage Limitations:** Retribution poate avea damage mai putin constant decat alte spec-uri DPS

### 3.4.2. PvP — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **Strong Defensive Cooldowns:** Divine Shield da o fereastra importanta de supravietuire.<br>- **Emergency Healing:** Flash of Light si Holy Light pot salva aliati in momente critice.<br>- **Team Support** | - **Limited Mobility:** Slab daca i se face kite <br>- **Mana Pressure:** Healing-ul repetat poate epuiza rapid mana.<br>- **Predictable Offense:** O parte din presiunea ofensiva depinde de apropierea de tinta si de cooldown-urile disponibile. |

---

## 3.5. Rogue 🗡️

### 3.5.1. PvE — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **High Single-Target DPS** <br>- **Strong Crowd Control:**<br>- **Threat Control:** Feint si Vanish pot ajuta la gestionarea threat-ului si la evitarea unor situatii periculoase. | - **Limited Group Utility:** Nu are aproape deloc buffs pentru grupa<br>- **Melee Dependency:** <br>- **Energy & Combo Point Management** Rotatia e cea mai importanta: Gresesti ceva, ai cam supt-o|

### 3.5.2. PvP — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **High Burst Damage:** Opener puternic <br>- **Excellent Control:** Kidney Shot, Cheap Shot, Blind si Sap da slowdown la ramp inamic<br>- **Stealth & Reset Potential:** Hit & Run | - **Cooldown Dependency:** O parte importanta din burst si control depinde de cooldown-uri.<br>- **Vulnerable When Controlled:** Stun-urile si alte forme de crowd control pot opri Rogue-ul inainte sa-si execute combo-ul.<br>- **Limited Ranged Pressure:** Are putine optiuni de damage sustinut la distanta. |

---

## 3.6. Shaman ⚡

### 3.6.1. PvE — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **Powerful Totem Support:** Strong rau daca sta langa toteme <br>- **Flexible Role:** Poate contribui cu damage melee, spell damage sau healing, in functie de spec.<br>- **Useful Utility:** E bun ofensiv si defensiv, e ce trb | - **Totem Positioning:** Totemele trebuie plasate corect si pot necesita inlocuire cand grupul se deplaseaza.<br>- **Mana Management:** Healing-ul si spell-urile pot consuma rapid mana.<br>- **Gear Competition:** Enhancement poate concura pentru anumite arme melee cu alte clase din grup. |

### 3.6.2. PvP — Strengths & Weaknesses

| 🟢 STRENGTHS | 🔴 WEAKNESSES |
|---|---|
| - **Strong Burst Potential**<br>- **Purge & Utility:** Purge elimina buff-uri , iar totemele pot da counter la unele efecte<br>- **Hybrid Support:** Poate alterna intre damage, healing si space control | - **Totem Vulnerability:** Adversarii pot distruge totemele = reduce eficienta suportului.<br>- **Mana Dependency:** Spell-urile mananca mana destul de tare<br>- **Limited Escape Tools:** Nu are asa multe resurse sa scape |

---

## 4. Cine ce joaca

| Nume | Rasa | Clasa | Spec | Rol |
|------|------|-------|------|-----|
| Flav | Orc | ![Warrior](https://img.shields.io/badge/Warrior-C79C6E?style=flat-square) | Protection | 🛡️ Tank |
| Vladi | Troll | ![Priest](https://img.shields.io/badge/Priest-FFFFFF?style=flat-square) | Discipline | 💚 Heal |
| Ali | Undead | ![Warlock](https://img.shields.io/badge/Warlock-9482C9?style=flat-square) | Affliction | 🏹 Ranged DPS |
| Necu | Troll | ![Hunter](https://img.shields.io/badge/Hunter-ABD473?style=flat-square) | Beast Mastery | 🏹 Ranged DPS |
| Octi | Orc/Troll | ![Hunter](https://img.shields.io/badge/Hunter-ABD473?style=flat-square) | ? | 🏹 Ranged DPS | 
| Sebi | Undead | ![Paladin](https://img.shields.io/badge/Paladin-F58CBA?style=flat-square) | Retribution | 🗡️ Melee DPS |
| Adi | Orc | ![Rogue](https://img.shields.io/badge/Rogue-FFF569?style=flat-square) | Combat | 🗡️ Melee DPS |
| Tipu | Orc | ![Shaman](https://img.shields.io/badge/Shaman-0070DE?style=flat-square) | Enhancement | 🗡️ Melee DPS |

## 5. Gear — Cine ce poarta

Tipul de armura depinde de clasa. Unele clase fac **upgrade** la level 40.
Ordinea este de la cel mai **slab** (🧵 Cloth) la cel mai **tare** (🪖 Plate).

| Nume | Clasa | Armor Progression |
|---|---|---|
| Vladi | Priest | 🧵 **Cloth** — tot timpul |
| Ali | Warlock | 🧵 **Cloth** — tot timpul |
| Adi | Rogue | 🧥 **Leather** — tot timpul |
| Necu | Hunter | 🧥 **Leather** pana la 39<br>⛓️ **Mail** de la 40 in sus |
| Octi | Hunter | 🧥 **Leather** pana la 39<br>⛓️ **Mail** de la 40 in sus |
| Tipu | Shaman | 🧥 **Leather** pana la 39<br>⛓️ **Mail** de la 40 in sus |
| Sebi | Paladin | ⛓️ **Mail** pana la 39<br>🪖 **Plate** de la 40 in sus |
| Flav | Warrior | ⛓️ **Mail** pana la 39<br>🪖 **Plate** de la 40 in sus |

> **Important:** Upgrade-ul de la level 40 (Mail pentru Necu/Octi/Tipu, Plate pentru Flav/Sebi) se invata de la **class trainer** in capitala. Mergem impreuna sa vedem cat costa.

## 6. Profesii & Crafting

Scopul nostru este să ne ajutăm reciproc cu materiale, echipament, consumabile și obiecte utile pentru dungeon-uri și PvP.

Fiecare personaj poate avea **2 profesii principale** și poate învăța separat **Cooking, First Aid și Fishing**.

### 6.1. Cine ce profesii alege

Fiecare profesie este ori **Gathering** (aduni materiale din lume), ori **Crafting** (transformi materialele in obiecte).

Am ales profesiile dupa **3 reguli**:
1. **Crafting-ul tau trebuie alimentat de Gathering-ul tau** — altfel ramai fara materiale.
2. **Crafting-ul trebuie sa se potriveasca cu armor type-ul si rolul clasei.**
3. **Nu duplicam o profesie decat daca duplicarea aduce ceva real.**

| Nume | Clasa | Rol | ⛏️ Gathering | 🔨 Crafting | De ce se potriveste cu clasa |
|---|---|---|---|---|---|
| Flav | Warrior | 🛡️ Tank | ⛏️ Mining | ⚙️ Engineering | Mining da **Toughness** (+stamina) — exact ce vrea un tank. Sapper Charges fac AoE damage = **threat** pe pack-uri, iar grenades dau **stun** = CD extra de control. |
| Vladi | Priest | 💚 Heal | — *(Cloth de la mobi)* | 🪡 Tailoring + 🪄 Enchanting | Tailoring crafteaza **exact armor type-ul lui (Cloth)** + bags pentru tot grupul. Ce nu foloseste **dezenchanteaza** — de aia cele doua merg mereu impreuna. |
| Ali | Warlock | 🏹 Ranged DPS | 🌿 Herbalism | 🧪 Alchemy | Warlock-ul isi face Healthstone singur, dar **arde mana** — are nevoie de mana pots. Herbalism il alimenteaza direct. |
| Necu | Hunter | 🏹 Ranged DPS | ✂️ Skinning | 🐮 Leatherworking | Hunter-ul **omoara bestii non-stop** — cel mai bun skinner din joc. Leatherworking ii face **Leather 1-39 → Mail 40+** (fix progresia lui) si, cel mai important, **Quiver / Ammo Pouch** (+ranged attack speed). |
| Octi | Hunter | 🏹 Ranged DPS | ⛏️ Mining | ⚙️ Engineering | Mining ii asigura materialele pentru Engineering. Bombele, grenades si scopes ii dau damage si control, utile atat solo, cat si in dungeons. |
| Sebi | Paladin | 🗡️ Melee DPS | ⛏️ Mining | 🔨 Blacksmithing | Mining da **Toughness** (+stamina) pentru melee. Blacksmithing ii face **Mail 1-39 → Plate 40+** (fix progresia lui) + arme, si pentru el si pentru Flav. |
| Adi | Rogue | 🗡️ Melee DPS | ⛏️ Mining | ⚙️ Engineering | Rogue + Engineering e combinatia clasica: **Sapper Charges, Rocket Boots, grenades**. Mining ii da ore-ul (+Toughness stamina). Nu ia Leatherworking pentru ca **Necu ii crafteaza deja gear-ul**. |
| Tipu | Shaman | 🗡️ Melee DPS | 🌿 Herbalism + ✂️ Skinning | — *(gatherer dedicat)* | Enhancement e **melee**, deci skinuieste usor ce omoara. Alimenteaza **exact cele doua crafturi care consuma cel mai mult**: Alchemy (herbs) si Leatherworking (leather) — iar Necu ii face gear-ul lui. |

#### 5.1.1. Distributia finala

| Gathering | Cati | Cine |
|---|---|---|
| ⛏️ Mining | **4** | Flav, Sebi, Adi, Octi |
| 🌿 Herbalism | **2** | Ali, Tipu |
| ✂️ Skinning | **2** | Necu, Tipu |

| Crafting | Cati | Cine |
|---|---|---|
| ⚙️ Engineering | **3** | Flav, Adi, Octi |
| 🔨 Blacksmithing | 1 | Sebi |
| 🧪 Alchemy | 1 | Ali |
| 🐮 Leatherworking | 1 | Necu |
| 🪡 Tailoring | 1 | Vladi |
| 🪄 Enchanting | 1 | Vladi |

> **Toate cele 6 profesii de crafting sunt acoperite.** Fiecare consumator de ore (Flav, Sebi, Adi, Octi) isi mineste singur ore-ul — nu depinde de nimeni.

> **De ce 4 Mining?** Avem **4 crafturi care consuma ore** (3x Engineering + 1x Blacksmithing). Fiecare isi strange materialele pentru propriul crafting.

> **De ce 3 Engineeri (Flav, Adi + Octi)?** Bombele, sapperele si Rocket Boots **pot fi folosite DOAR de cel care are profesia**. Nu poti face un sapper pentru altcineva. La celelalte crafturi (BS, LW, Tailoring, Alchemy) obiectul il poate folosi oricine — deci acolo duplicarea ar fi pierdere. Aici e castig curat.

> **De ce Tipu nu are crafting?** Toate cele 6 crafturi sunt deja luate. Alchemy si Leatherworking sunt cele mai **hamesite** de materiale cand le ridici la 300 — Tipu le acopera pe amandoua. Daca mai tarziu vrem mai multe pots, poate schimba Skinning → 🧪 Alchemy.

> **Atentie la Vladi:** Tailoring + Enchanting nu are nicio profesie de gathering. Cloth-ul vine de la **humanoid mobs**, deci tot grupul ii pastreaza cloth-ul. In schimb, el face **bags pentru toata lumea**.

### 6.2. Ce face fiecare profesie?

#### 5.2.1. Profesii care adună materiale

| Profesie | Ce faci? | La ce ne ajută? | Link |
|---|---|---|---|
| ⛏️**Mining** | Cauti veins → ores, stone și gems | Materiale pentru Engineering și Blacksmithing. Da si **Toughness** (+stamina). Flav, Sebi și Adi o au. | https://www.wow-professions.com/forever/mining-leveling-guide |
| 🌿**Herbalism** | Culegi plante si ierburi | Ali le foloseste pentru potiuni si alte consumabile. Tipu il aprovizioneaza. | ! SOON TO COME ! |
| ✂️**Skinning** | Obtii leather & piei de la mob (bestii) **(DIFERIT DE TAILORING)** | Necu crafteaza gear si quivers. Tipu aduce pielea in plus. | ! SOON TO COME ! |

#### 5.2.2. Profesii care creează obiecte

| Profesie | Ce faci? | La ce ne ajută? | Link |
|---|---|---|---|
| 🧪**Alchemy** | Folosesti herbs + alte materiale pentru pots si elixire | 🔴Healing🔴<br>🔵Mana🔵 | https://www.wow-professions.com/forever/alchemy-leveling-guide |
| 🔨**Blacksmithing** | Materiale pentru arme & armura | ⛓️ Mail + 🪖 Plate pentru **Flav** si **Sebi**, plus arme si sharpening stones pentru toata lumea | https://www.wow-professions.com/forever/blacksmithing-leveling-guide |
| 🪄**Enchanting** | Craftezi enchants care se pot pune pe APROAPE orice parte de armura | ⬆️⬆️⬆️ BUFF ⬆️⬆️⬆️ la arme si armuri, pentru tot grupul | https://www.wow-professions.com/forever/enchanting-leveling-guide |
| ⚙️**Engineering** | Materiale pentru explosives, bombs, guns, scopes si gadgets | ⬆️🟢DMG AMP🟢⬆️, control si utilitate in PvE si PvP. **Bombele se folosesc doar de engineer**, dar **scopurile** se pot da altora (ex: lui Necu). | https://www.wow-professions.com/forever/engineering-leveling-guide |
| 🐮**Leatherworking** | Folosesti leather și hides pentru armura si alte obiecte din piele | 🧥 Leather pentru **Adi**, 🧥→⛓️ Leather/Mail pentru **Necu** si **Tipu**, **armor kits** pentru toti si **Quiver** pentru Necu | https://www.wow-professions.com/forever/leatherworking-leveling-guide |
| 🪡**Tailoring** | Folosesti cloth obtinut in principal de la humanoid mobs **(DIFERIT DE SKINNING!)** | 🧵 Cloth gear pentru **Vladi** si **Ali**, plus **bags pentru tot grupul** | https://www.wow-professions.com/forever/tailoring-leveling-guide |

>**Nota**: 💎 **Jewelcrafting** nu apare in lista. Trebuie sa verificam daca exista pe **WoW Forever** — daca da, cel mai usor ar fi sa o ia unul dintre mineri (Sebi sau Adi), pentru ca se alimenteaza din Mining. Discutam.

## 6.3. Ce inseamna profesiile pentru noi?

#### 5.3.1. Flav — ⛏️ Mining + ⚙️ Engineering *(Warrior, Tank)*
- **Pentru clasa lui:** Mining da **Toughness** (+stamina), iar tank-ul vrea stamina.
- **Pentru grup:** Sapper Charges = AoE damage = **threat instant** pe pull-uri mari. Grenades = **stun** pe pack-uri.

#### 5.3.2. Vladi — 🪡 Tailoring + 🪄 Enchanting *(Priest, Heal)*
- **Pentru clasa lui:** Tailoring crafteaza **Cloth**, fix armor type-ul lui.
- **Pentru grup:** **Bags pentru toata lumea** (cel mai mare quality-of-life la leveling) + enchants pe gear-ul tuturor.
- **Atentie:** nu are gathering — **ii pastram cloth-ul**.

#### 5.3.3. Ali — 🌿 Herbalism + 🧪 Alchemy *(Warlock, Ranged DPS)*
- **Pentru clasa lui:** Warlock-ul arde mana; isi face singur mana pots.
- **Pentru grup:** 🔴 Healing si 🔵 Mana pots + elixire pentru dungeons si OW.

#### 5.3.4. Necu — ✂️ Skinning + 🐮 Leatherworking *(Hunter, Ranged DPS)*
- **Pentru clasa lui:** Hunter-ul omoara bestii non-stop = **cel mai bun skinner**. LW ii face **Quiver** (+ranged attack speed) — item de clasa.
- **Pentru grup:** Leather pentru Adi, Leather→Mail pentru el si Tipu, **armor kits** pentru toti.

#### 5.3.5. Octi — ⛏️ Mining + ⚙️ Engineering *(Hunter, Ranged DPS)*
- **Pentru clasa lui:** Isi strange singur ore-ul in timpul questing-ului si il transforma in bombe, grenades si scopes pentru arma ranged.
- **Pentru grup:** al **treilea** Engineer care poate folosi sappere, grenades si Rocket Boots in dungeons.

#### 5.3.6. Sebi — ⛏️ Mining + 🔨 Blacksmithing *(Paladin, Melee DPS)*
- **Pentru clasa lui:** BS crafteaza **Mail 1-39 → Plate 40+**, exact progresia lui.
- **Pentru grup:** arme si armura pentru el si Flav + sharpening stones pentru toti melee.

#### 5.3.7. Adi — ⛏️ Mining + ⚙️ Engineering *(Rogue, Melee DPS)*
- **Pentru clasa lui:** Rogue + Engineering e combinatia clasica (Sapper, Rocket Boots, grenades). Mining ii da ore + stamina.
- **Pentru grup:** al **doilea** om care poate arunca sappere — bombele nu se pot da altcuiva, deci asta chiar dubleaza burst-ul.
- **De ce nu Leatherworking?** Pentru ca **Necu ii crafteaza deja gear-ul de Leather**.

#### 5.3.8. Tipu — 🌿 Herbalism + ✂️ Skinning *(Shaman Enhancement, Melee DPS)*
- **Pentru clasa lui:** Enhancement e **melee**, deci skinuieste usor ce omoara. Gear-ul lui (Leather→Mail) vine de la Necu.
- **Pentru grup:** alimenteaza **exact cele 2 crafturi care consuma cel mai mult**: Alchemy (herbs → Ali) si Leatherworking (leather → Necu).

#### 5.3.9. 📌 Pe scurt

| Jucator | Cu ce ajuta grupul? |
|---|---|
| Flav | Sappere si grenades pentru pull-uri + ore |
| Vladi | **Bags** + enchants pentru tot grupul |
| Ali | Pots + elixire |
| Necu | Leather/Mail gear, armor kits + Quiver |
| Octi | Al treilea Engineer: sappere, grenades, scopes + ore |
| Sebi | Arme + Mail/Plate armor + sharpening stones |
| Adi | Engineer: sappere pentru burst + ore |
| Tipu | Herbs pentru Ali + leather pentru Necu |

> **Obiectiv:** Strangem materiale in timp ce facem leveling si le folosim pentru crafting, consumabile si upgrade-uri pentru tot grupul.

### 6.4. Checklist — Profesii

#### 5.4.1. Profesii principale

- [ ] Flav: ⛏️ Mining + ⚙️ Engineering
- [ ] Vladi: 🪡 Tailoring + 🪄 Enchanting
- [ ] Ali: 🌿 Herbalism + 🧪 Alchemy
- [ ] Necu: ✂️ Skinning + 🐮 Leatherworking
- [ ] Octi: ⛏️ Mining + ⚙️ Engineering
- [ ] Sebi: ⛏️ Mining + 🔨 Blacksmithing
- [ ] Adi: ⛏️ Mining + ⚙️ Engineering
- [ ] Tipu: 🌿 Herbalism + ✂️ Skinning

#### 5.4.2. Profesii secundare — Toți cei 8

- [ ] Flav: First Aid + Cooking + Fishing
- [ ] Vladi: First Aid + Cooking + Fishing
- [ ] Ali: First Aid + Cooking + Fishing
- [ ] Necu: First Aid + Cooking + Fishing
- [ ] Octi: First Aid + Cooking + Fishing
- [ ] Sebi: First Aid + Cooking + Fishing
- [ ] Adi: First Aid + Cooking + Fishing
- [ ] Tipu: First Aid + Cooking + Fishing

#### 5.4.3. Obiective de grup

- [ ] Suntem TOTI de acord cu profesiile.
- [ ] Toti au invatat profesiile alese.
- [ ] Am stabilit cine/ce aduna (ores, herbs, leather și cloth)
- [ ] Toata lumea pastreaza **cloth-ul** pentru Vladi.
- [ ] Toata lumea pastreaza **leather-ul** pentru Necu.
- [ ] Am verificat daca 💎 Jewelcrafting exista pe WoW Forever.
- [ ] Avem consumabile pentru dungeons
- [ ] Am stabilit unde depozitam materialele pentru crafting.
