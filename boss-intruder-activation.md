# Boss Intruder Activation

Instead of AI Protocols, Boss Intruders have a whole
deck of AI cards. When a Boss Intruder activates,
you simply **draw the top AI card** from the deck and
resolve it. Note that some Boss Intruders, like the
Mothman, may have additional actions to resolve,
before or after the main AI card action. However,
the main part of a Boss Intruder’s activation will
always be an AI card draw.

To resolve the Boss Intruder’s activation, follow
these steps in order:

1. **Draw AI:** Draw the top card from the AI deck.
2. **Targeting:** Decide who or what becomes the Target of the Attack.
3. **Movement Commands:** Resolve Intruder Movement commands.
4. **Attack/Action:** Resolve Intruder Attack/Action commands.  
  **4.1. Attack Roll:** Perform an Attack Roll.  
  **4.2. Attack Consequences:** Resolve all Attack/Action effects.
5. **After Attack/Action:** Resolve all After Attack/Action effects.


## 1. Draw AI

To determine the Intruder’s behavior, draw an AI
card from the top of the AI deck. Notice the **roman
numeral** in the center of the card back. This number indicates the level of the AI card. So, although
the AI cards are facedown, you get some sense of
how dangerous the next Intruder Attack will be.

## 2. Targeting

After you reveal the AI card, check the targeting to
see who or what is being attacked. Targeting is a
series of increasingly general separate instructions
called **lines**. Each line consists of the word Target:”
followed by targeting instructions. Note that a single targeting line can in fact take up more space
than a text line.

To check who is the Target of the Intruder Attack,
read the lines in the “targeting” area of the AI card,
one by one from top to bottom until you find the
first one that you can resolve. Do not check further
targeting lines.

To become the Target, a Spacer must fulfill all requirements of a single targeting line. If there is no
valid Target for any of the targeting instructions,
the AI card is discarded and the Intruder performs
its Routine instead. Note that some Zone Attacks
target spaces, not specific Spacers and they are
considered performed even if there are no Spacers
in the designated Zone (therefore they do not result
in a Routine).

**Note:** Some targeting instructions will require you
to measure distance (e.g. Closest or Furthest). Distance in **Enormity** is always measured in spaces
and orthogonally (in cardinal directions), never diagonally.

### Specific Targets

Some game effects will instruct you to resolve an
Attack against a specific Target (e.g. “Perform Signature against the Attacker”). When it happens,
this instruction overrules any targeting instructions
on the card itself. Note that if a Spacer becomes a
Target in the Targeting step, it remains the Target
until the end of this AI card unless an effect specifically states otherwise.

### Typical Targeting Instructions

**Closest:** The Target is the shortest distance (in
spaces) from the Intruder (counted through Obstacles and red lines) among all possible Targets.

**Furthest:** The Target is the furthest distance (in
spaces) from the Intruder (counted through Obstacles and red lines) among all possible Targets.

**In front:** The Target is on any space in front (see
Facing p. 27) and within Line of Sight (see p. 21) of
the Intruder.

**In sight:** The Target is within Line of Sight (see p. 21)
of the Intruder.

**Highest/Lowest X:** Least/most value/amount of a
specified statistic/resource. For example, Lowest
Stress ![Stress Icon](svg/icon-stress.svg).

**No Target:** Always resolve this instruction if no other targeting instruction is applicable.

**Last to Noise/Priority Target:** The Target with the
**Priority Target/Last to Noise ![Priority Target Symbol](svg/icon-target.svg)** token.

**Zone X:** All spaces in an indicated area. Zones are
measured in spaces from the source, **orthogonally
and diagonally**. This means a Zone always creates
a ‘box’ around the source. This targeting line triggers even if there are no Spacers within the indicated area, unless the targeting specifically states
‘Spacers in Zone X’.

## 3. Movement Commands

Perform Boss Intruder Movement commands, like
‘Move’ and ‘Shift’ (see Action Commands below for
specifics). Boss Intruders move according to baseline Intruder movement rules (see p. 28), with a few
exceptions (see box Bosses, Terrain and Crash on p.
33).

## 4. Attack/Action Commands

Perform Boss Intruder Attack commands, like
‘Attack’ or ‘Shoot’, or other non-Attack, non-Movement Action commands (see Action Commands
above for specifics).

### 4.1 Attack Roll
Boss Intruder’s attack rolls are resolved according
to baseline Intruder rules (see p. 26).

### 4.2. Attack Consequences
Boss Intruder’s attacks are resolved according to
baseline Intruder rules (see p. 26).

## 5. After Attack/Action

Boss Intruders After Attack/Action effects are resolved according to baseline Intruder rules (see p.
26), with the following addition.

When an Intruder Attack/Action targets more than
one Spacer, it is important to know if the After Attack/Action effect applies to every targeted Spacer
or just the last one. To avoid confusion, in the latter
case, the game uses the term After Final:. This indicates that the effect resolves only after the last
Attack/Action from the AI card.

## Action Commands

If the command uses an ampersand ‘&’, it is considered a composite command made of two or more
other commands. Below, you will find a list of Attack commands found in the Demo:

**Attack (Melee):** An Attack without a specific command (i.e. ‘Shoot:’) is considered **Melee** and requires **adjacency**.

**Blast:** Performed against all Spacers in a designated zone. Each Spacer performs a separate Attack
Roll, but they are considered to **happen simultaneously**. The following rules apply:

- A Chain Break during one of these Attacks
  does not invalidate unresolved Attacks
  against other Spacers.
- If a Spacer moves outside of the Attack
  Zone after you have already begun to resolve this Attack against other Spacers in
  the Zone (i.e. performed an Evasion Roll and
  applied Attack effects), it does not invalidate an Attack against them.
- Blast attacks all Spacers within X spaces
  horizontally, vertically **and diagonally** from
  the source of Zone X.
- The Intruder is **not** considered to be inside
  the Zone originating from it and neither are
  Spacers in Other Places (see Other Places, p. 42).

**Move:** Perform a movement using standard Intruder rules for Movement. Move is usually part of a
composite command, i.e. ‘Move&Attack:’.

**Shift:** Perform movement **in a straight line** (either
horizontal or vertical), along the shortest possible
path, to a space from which the following action
(usually ‘Shoot’, ‘Ranged’ or ‘Blast’) can be performed against the Target. If an Attack is preceded
by Shift, check valid Targets and measure Range
using these rules too. **Note:** Shift can be compared
to that of a Rook from Chess.

**Shoot:** Shoot can be performed against a Spacer
within X spaces of the Intruder, **in a straight line**,
where X is the Intruder’s Range. Most Boss Intruders have **Unlimited Range**. Note that if Shoot is part
of a composite command, i.e. ‘Shift&Shoot’, the
Intruder will stop the movement as soon as moves
within range of the Attack.

**Terrorize:** These are mental assaults that force the
Target to gain Stress ![Stress Icon](svg/icon-stress.svg) instead of losing Vitals ![Vitals Icon](svg/icon-vitals.svg).
Terrorize usually has unlimited range. Terrorize **cannot** be mitigated with armor, be re-rolled using **armor re-rolls** or avoided with the Dodge X keyword,
unless stated otherwise. Terrorize can target a specific Spacer, or a designated Zone.