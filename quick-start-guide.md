# Guards of Atlantis II — Learn to Play Guide

This guide teaches the game in layers. Start with Part 1 and play a practice round before reading further. Each part builds on what you already know.

---

## Part 1: The 30-Second Pitch

Guards of Atlantis II is a team-based battle game for 4 or 6 players. Each player controls a hero. You're split into two teams — Red and Blue.

There's a lane of zones connecting your base (Throne) to the enemy base. Minions march down the lane automatically. Heroes help their minions, fight enemy heroes, and try to win.

**You win by doing ONE of these:**
1. Push your minions all the way into the enemy Throne.
2. Kill enemy heroes enough times that they run out of Life counters.
3. Be the team that wins the final wave push when time runs out.

That's the big picture. Everything else is just how you do it.

---

## Part 2: The Core Loop (What you actually do each turn)

The game runs in **ROUNDS**. Each round has **4 TURNS**. Here's what happens:

### Step 1 — Pick a Card
Everyone looks at their hand and places one card **FACEDOWN** on the board. You're all doing this at the same time. Don't show anyone.

You're only choosing *which* card to play right now. You'll decide what to do with it in a moment.

### Step 2 — Flip and Check Initiative
Everyone flips their card face-up. Look at the big number in the **top-left corner** of each card. That's the Initiative.

Highest Initiative goes first. Then next highest. And so on.
(Ties? The Tie Breaker coin decides between teams. Same team ties? Agree without discussing why.)

### Step 3 — Take Turns Acting
In Initiative order, each player does **ONE** thing with their card:

- **a) MOVE** — Move your hero up to the number on the boot icon.
- **b) ATTACK** — Attack an enemy hero or minion.
- **c) USE A SKILL** — Apply the card's special text.
- **d) DEFEND** — You don't choose this now. It happens as a reaction (explained in Part 4).
- **e) HOLD** — Do nothing. Always available. No shame in it.

After acting, place your card on your hero dashboard. Done.

### Step 4 — Next Player Goes
The player with the next highest Initiative acts. Repeat until everyone has resolved their card. That's one turn.

**THEN DO IT AGAIN.** After 4 turns, the round ends. Pick up all your cards. Do end-of-round stuff (Part 5). Start a new round.

That's the whole game loop. Everything else is details.

---

## Part 3: Your Cards (The most important thing to understand)

Each card has multiple options. Think of it as a Swiss Army knife.

### What's on a Card
- **Initiative** (top-left number): When you act this turn.
- **Primary Action** (big colored icon, bottom-left): The "main" use.
- **Secondary Actions** (smaller icons): Simpler alternatives.
- **Card Text** (bottom area): Special instructions.
- **Range/Radius** (right side number, if any): How far the action reaches.

### The Key Rule

> **Card text ONLY applies when you use the Primary action.**
> If you use a secondary action (like the small movement or defense icon), you IGNORE the card text entirely.

### Example
Your card has:
- **Primary:** Attack (big red sword icon) — "Move 2 spaces in a straight line. Target a unit adjacent to you."
- **Secondary:** Movement 3 (small boot icon)
- **Secondary:** Defense 2 (small shield icon)

If you choose the **PRIMARY Attack**: You follow the card text — move 2 spaces, then attack.

If you choose the **SECONDARY Movement**: You just move up to 3 spaces. The card text doesn't apply. No attacking.

### Basic vs Non-Basic Cards
- **Gold and Silver cards** = Basic (your signature moves, never upgraded).
- **Red, Green, Blue, Purple cards** = Non-basic (these get upgraded as you level up).

Don't worry about this until you start leveling up.

---

## Part 4: Attacking and Defending

### Attacking a Minion (simple)
Target an enemy minion in range. It dies. Collect 2 coins (4 for a heavy minion). That's it. Minions can't defend.

### Attacking a Hero (more involved)

**1. YOU (attacker):** Calculate your Attack total.
```
= Card's attack value + attack items + any card text bonuses
```
Announce: "I'm attacking you for 6."

**2. THEM (defender):** They may discard ONE card from their hand to defend. They don't have to — but if they don't, they're defeated.

**3. THEM:** Calculate their Defense total.
```
= Card's defense value + defense items + card text bonuses
  + friendly melee/heavy minions adjacent to them (+1 each)
  - enemy melee/heavy minions adjacent to them (-1 each)
  - enemy ranged minions within 2 spaces (-1 each)
```

**4. COMPARE:**
- Defense >= Attack → **Defended!** The defender survives.
- Defense < Attack → **Defeated!** Remove the hero from the board.

> **IMPORTANT:** Defending does NOT count as your action for the turn. You can defend as many times as you're attacked, as long as you have cards in hand. That's why saving a card for defense matters.

### When a Hero is Defeated
- Remove them from the board (they'll respawn next turn at their Throne).
- Attacker's team earns coins equal to the hero's level.
- Defeated hero's team flips Life counters equal to their lowest card tier.
- If that was the last Life counter, the defeated hero's team **loses**.

### Non-Ranged vs Ranged Attacks
- **Non-ranged:** Can only hit targets right next to you (adjacent).
- **Ranged:** Can hit targets up to the Range value away. Says "Ranged" on the card.

---

## Part 5: End of Round (After 4 turns)

Do these steps in order:

### 1. Minion Battle
Count each team's minions in the Battle Zone.
- Same number? Nothing happens.
- One team has more? The losing team removes minions equal to the difference (their choice which ones, but heavy minion goes last).

### 2. Remove Tokens and Return Markers
Clear the board of tokens. Return markers to supply.

### 3. Push the Lane (if one team lost all their minions)
The team with minions remaining wins the push.
- Flip a Wave counter. (Last one? That team **wins the game!**)
- The Battle Zone moves one zone toward the loser's Throne. (Into their Throne? The pushing team **wins!**)
- Old minions are removed. New minions spawn in the new Battle Zone.

### 4. Pick Up All Your Cards
Everything goes back to your hand. Active effects end.

### 5. Level Up (if you can afford it — mandatory!)

### 6. Pity Coin
Didn't level up this round? Take 1 free coin.

---

## Part 6: Movement Details

### Normal Movement (secondary action — small boot icon)
Move your hero up to the number of spaces shown. You **CANNOT** move through or land on obstacles (other heroes, minions, tokens, terrain).

### Primary Movement (big boot icon)
Same as above, **PLUS** the card text applies. Card text usually kicks in BEFORE you move (unless it says otherwise).

### Fast Travel (replaces any movement action)
Instead of walking step-by-step, teleport to any space in your current Zone or an adjacent Zone.

**Requirements — ALL must be true:**
- Destination is in the same Zone or an adjacent Zone.
- NO enemy heroes or minions in the Zone you're leaving.
- NO enemy heroes or minions in the Zone you're arriving in.

If there's even one enemy in either zone, you can't Fast Travel. This is why placing a single minion or hero in a zone is a strong defensive play — it blocks enemy Fast Travel.

- You can only Fast Travel once per action, regardless of movement value.
- If you Fast Travel instead of a Primary movement, card text doesn't apply.

---

## Part 7: Leveling Up

You start at Level 1. Coins are earned by defeating minions and heroes.

### How Much Does It Cost?

| From | To | Cost |
|------|-----|------|
| Level 1 | Level 2 | 1 coin |
| Level 2 | Level 3 | 2 coins |
| Level 3 | Level 4 | 3 coins |
| ... | ... | Each level costs 1 more than the last |

You **MUST** level up at end of round if you can afford it.

### What Happens When You Level Up

**Step 1 — Upgrade a Card**

Pick a non-basic card in your hand with the lowest Tier (the Roman numeral in the top-right corner). Return it to your deck.

Find the two cards of the same COLOR that are one Tier higher. Take one into your hand. Set the other aside facedown — that becomes an item.

> **Rule:** You must upgrade ALL cards to Tier II before any can go to Tier III.

**Step 2 — Gain an Item**

The card you set aside? Tuck it under your dashboard in the matching item slot (only the item icon at the bottom should show).

Each item gives **+1** to the matching stat on ALL your cards that have that icon. So a +1 Attack item boosts every card that has an Attack icon.

You always end up with 5 cards in hand (1 of each color).

### The Ultimate (endgame)
Once all your cards are Tier III, the next level-up gives you a Tier IV "Ultimate" card instead. It's a permanent ability that's always active while your hero is on the board. Place it face-up next to your dashboard.

---

## Part 8: Minions and the Lane

### The Three Minion Types
- **Melee** (4 per team): The bulk of the minion wave.
- **Ranged** (1 per team): Stands back.
- **Heavy** (1 per team): Tanky. Has special immunity.

### Heavy Minion Immunity
As long as a team has ANY non-heavy minions in the Battle Zone, their heavy minion is **IMMUNE** — nothing can affect it. You have to kill all the small minions first.

### How Minions Affect You
Minions don't attack heroes directly, but they DO affect your defense when you're attacked near them (see Part 4 defense modifiers). They also determine who pushes the lane.

### Lane Pushes
The lane pushes when one team has NO minions in the Battle Zone (either from Minion Battle at end of round, or from a hero killing the last one mid-turn).

When pushed:
- Battle Zone moves one zone toward the loser's Throne.
- A Wave counter is flipped.
- Minions respawn in the new Battle Zone.

---

## Part 9: The Stuff That Comes Up During Play

### Respawning Your Hero
If your hero is off the board at the start of your turn, you MAY respawn at an empty spawn point in your Throne Zone before acting. You can also choose not to respawn and just resolve your card (doing a Hold action).

### Card States (simplified)
| State | Meaning |
|-------|---------|
| **In Hand** | You can play it or discard it to defend |
| **Played** | It's on the board (facedown then faceup), waiting to resolve |
| **Resolved** | It's on your dashboard after you acted |
| **Discarded** | It's in your discard pile (used for defense usually) |

At end of round, ALL cards come back to your hand. Clean slate.

### Active Effects
Some cards say things like "**This Turn:**" or "**This Round:**" — these effects stick around for that duration. Turn the card sideways to remind everyone. When the duration ends (or you're defeated, or the round ends), the effect goes away.

### Tokens
Some heroes place tokens on the board. Tokens are obstacles (block movement). They get removed at end of round. Any hero can spend their attack action to "Clear" — remove tokens adjacent to them instead of attacking.

### Table Talk
- **Between turns:** Talk strategy openly (opponents hear you too).
- **After cards are revealed:** NO strategy talk. Decide on your own.
- You can state preferences ("I'd like to go first") but NOT reasoning ("I need to go first to dodge that attack").

---

## Part 10: Common First-Game Questions

**Q: Do I have to use the card text?**
A: Only if you use the Primary action. Secondary actions ignore card text.

**Q: Can I attack my own minions or teammates?**
A: Never. You can never damage friendly units.

**Q: What if I can't do anything useful with my card?**
A: Do a Hold action. Place the card, do nothing, resolve it. It's a legitimate play — sometimes the best move is not moving.

**Q: Can I defend multiple attacks in one turn?**
A: Yes, as long as you have cards in hand to discard. Each defense costs one card.

**Q: What if I run out of cards in hand?**
A: You can't defend and must announce that you're passing instead of playing a card. This is bad — managing your hand is critical.

**Q: When do I get my cards back?**
A: End of every round (after 4 turns). All cards — resolved, discarded, everything — come back to your hand.

**Q: Can I save coins for later?**
A: No. If you can afford to level up at end of round, you MUST.

**Q: What happens when I'm defeated?**
A: You're removed from the board. On your next turn, you may respawn at your Throne. Your team loses Life counters and the enemy earns coins. It hurts, but you come back.

**Q: How does the Tie Breaker coin work?**
A: When players on DIFFERENT teams tie in Initiative, the team shown on the coin goes first, then that player flips the coin. Same-team ties don't use the coin — just agree.

**Q: What are items?**
A: When you level up, the leftover card becomes an item tucked under your dashboard. Each item gives +1 to the matching stat on all your cards that have that icon. They add up over the game.

**Q: How do I read the card's Range/Radius number?**
A: Range = how many spaces away you can reach in a straight line (for Ranged attacks). Radius = how many spaces in every direction (for area effects). A value of 1 means adjacent only.

---

## Cheat Sheet: Turn Order

```
1. Everyone plays a card facedown
2. Flip all cards face-up
3. Highest Initiative acts first
   → Choose ONE action:
      • Primary action (card text applies)
      • Secondary Movement (no card text)
      • Secondary Defense (no card text)
      • Fast Travel (replaces movement)
      • Clear (replaces attack, removes tokens)
      • Hold (do nothing)
   → Place resolved card on dashboard
4. Next player acts (repeat step 3)
5. After all players: turn ends
6. After 4 turns: End of Round
   → Minion Battle
   → Remove Tokens & Markers
   → Push Lane (if applicable)
   → Retrieve all cards
   → Level Up (if able, mandatory)
   → Pity Coin (if didn't level up)
```

### Win Conditions
- Push minions into enemy Throne
- Enemy team runs out of Life counters
- Win the last push when Wave counters run out