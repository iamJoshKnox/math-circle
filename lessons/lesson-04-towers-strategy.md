# Lesson 4: Towers & Strategy Games

## Theme
Kids encounter the Tower of Hanoi — a classic puzzle that rewards systematic thinking — and Nim-like strategy games where they discover that some positions are "winning" and some are "losing," independent of who is playing.

## Learning Goals
- Develop systematic problem-solving strategies (break a big problem into smaller steps)
- Discover that the Tower of Hanoi has a *minimum* number of moves and try to find it
- Experience strategy games where there is a *winning strategy* (not just luck)
- Begin to reason backwards: "If I want to win, what move should I make NOW?"

## Zvonkin References
- Tower of Hanoi: p. 55
- Strategy games and Nim: p. 184
- Games and winning strategies: pp. 183–190
- Letting children struggle productively: pp. 6–8

---

## Materials Checklist

| Item | Qty | Notes |
|------|-----|-------|
| Tower of Hanoi sets (3 pegs, 3–5 discs) | 5–8 | Can buy cheap wooden ones or make from cardboard/dowels. See DIY note below. |
| DIY Tower supplies (if no sets): cardboard squares in 3–5 sizes + 3 pencils in clay bases | 5–8 | Cut cardboard into graduated squares and poke holes in centers |
| Nim game supplies: counters/tokens (20 per pair) | 100+ | Coins, buttons, beans, or plastic chips |
| Small whiteboards + dry-erase markers | 15 | For tracking moves / strategies |
| Chart paper + marker | 1 | For class tracking |
| "Moves" tracking sheet (printed) | 15 | Table with columns: Move #, From, To (for Tower of Hanoi) |
| Math Circle Journals | 15 | |
| Projector / screen | 1 | |
| Timer | 1 | |

**DIY Tower of Hanoi Note:** Cut 3 (or 4 or 5) squares of cardboard in graduated sizes (e.g., 2", 3", 4", 5", 6"). Label each post A, B, C. Poke pencils into lumps of clay or playdough for pegs. Works perfectly and costs nothing.

---

## Timed Script

### Opening Bell (5 min) — "Counting Moves"

**[0:00–1:30] Gathering Ritual**

> "Welcome back, Math Circle! Today we're going to play games. But not just any games — games where you can figure out the SECRET to winning. No luck involved. Pure brainpower."

**[1:30–5:00] Warm-Up: Step Counting**

> "Here's a quick puzzle. I'm standing here." (Stand at one end of the room.) "I want to get to that wall." (Point to the other end.) "I can take BIG steps or SMALL steps. What's the FEWEST number of big steps I could take? Guess before I walk."

Take giant steps. Count aloud. Kids count with you.

> "I made it in ___ steps. Could I do it in fewer? How?"

*Anticipated:* "Take BIGGER steps!" → Try it. → "Is there a limit to how big your steps can be?"

> "What's the MOST steps I could take?"

*Anticipated:* "Tiny baby steps!" → "Would I ever get there?" → "Technically, could I take a MILLION tiny steps?"

*Teacher move:* This warm-up foreshadows the Tower of Hanoi's "minimum moves" concept. Connect later: "Just like walking across the room, we want to find the FEWEST moves in our tower puzzle."

---

### Main Activity 1 (15 min) — Tower of Hanoi

**[5:00–9:00] Introduction and Rules**

Hold up or project a Tower of Hanoi set with 3 discs stacked on peg A (largest on bottom).

> "This is the Tower of Hanoi. It's a famous puzzle that's hundreds of years old. Here are the rules."

Write rules on the board:

> **RULES:**
> 1. Move ALL the discs from Peg A to Peg C.
> 2. You can only move ONE disc at a time.
> 3. You can NEVER put a bigger disc on top of a smaller disc.

> "That's it. Three rules. Sounds easy, right? Let's see."

**[9:00–10:00] Demo: 2-Disc Puzzle**

Use just 2 discs to demonstrate.

> "Let me try with just 2 discs first. Watch."

Solve the 2-disc version, narrating each move:
1. Small disc → Peg B ("I move the small one out of the way...")
2. Big disc → Peg C ("Now the big one can go to its home...")
3. Small disc → Peg C ("And the small one goes on top.")

> "Three moves! Can anyone do it in fewer? ... No? Let's see if 3 is really the minimum."

**[10:00–20:00] Kids Solve — 3 Discs**

Distribute Tower of Hanoi sets (one per 2–3 kids). Give each group a tracking sheet.

> "Now try it with 3 discs. Your goal: move them all from Peg A to Peg C. Follow the rules. And COUNT your moves. Write each move down."

*Key questions while circulating:*
- "How many moves have you used so far? Do you think you can do it in fewer?"
- "You're stuck — what rule are you about to break? Can you undo your last move?"
- "Look at your tracking sheet. Do you see any pattern in your moves?"

*Anticipated struggles:*
- Moving a big disc onto a small disc → "Check Rule 3. What does it say?"
- Going in circles (moving the same disc back and forth) → "Hmm, you've been here before. Can you try something different?"
- Frustration → "It's SUPPOSED to be hard. The best mathematicians in history found this puzzle tricky."

*Anticipated discoveries:*
- "I did it in 7 moves!" → Record on chart paper. "Can anyone do it in fewer? Let's see." (7 is the minimum for 3 discs.)
- "I see a pattern — you always move the small disc first." → "Interesting theory! Does it always work?"
- "It took us 15 moves." → "That's great — you solved it! Now the question is: can you solve it more efficiently?"

**[18:00–20:00] Class Discussion**

Record best results on chart paper:

| Discs | Fewest Moves Found |
|-------|-------------------|
| 2     | 3                 |
| 3     | 7                 |
| 4     | ? (challenge)     |

> "2 discs took 3 moves. 3 discs took 7 moves. Do you notice anything? How many moves do you PREDICT 4 discs will take?"

*Anticipated:*
- "11!" (adding 4) → "Interesting guess. Let's test it later."
- "15!" (doubling + 1) → "Where did you get that? ... 3, 7, 15? What's the pattern?"
- Blank stares → "That's fine. We'll keep exploring."

*Teacher move:* Do NOT reveal the formula (2^n - 1). Let the kids discover the pattern over time. If they test 4 discs (15 moves), the pattern becomes clearer. Plant the seed now.

*Differentiation:*
- **Too easy:** Try 4 or 5 discs. Challenge: "Can you write INSTRUCTIONS that would let someone else solve 3 discs without thinking?" (This is essentially an algorithm.)
- **Too hard:** Start with just 2 discs. Physically hold the child's hand to the correct disc if needed. Use color-coded discs and give verbal prompts: "The red one can only go on an empty peg or on the blue one."

---

### Main Activity 2 (15 min) — Nim (Strategy Game)

**[20:00–25:00] Introduction to Nim**

> "Now we're going to play a strategy game called Nim. Here's how it works."

Place 12 counters (coins/buttons) in a line on the table, visible to all.

> **RULES:**
> 1. Two players take turns.
> 2. On your turn, take 1, 2, or 3 counters.
> 3. The player who takes the LAST counter WINS.

> "That's it. Let me play against a volunteer."

**[25:00–27:00] Demo Game**

Play against a volunteer. Intentionally lose the first game by making suboptimal moves.

> "Hmm, I lost! Nice job. Let me try again..."

Play again. This time, play the winning strategy (always leave a multiple of 4 for your opponent).

> "I won this time! Was that luck? Or did I figure something out? Let's see if YOU can figure out the secret."

**[27:00–35:00] Pair Play — Finding the Strategy**

Pair kids up. Give each pair 12 counters.

> "Play at least 3 games with your partner. After each game, think: WAS there a move you could have made to win? Is there a SECRET to this game?"

*Key questions while circulating:*
- "You're about to take counters. How many are left? If you take 1, how many will your opponent have? If you take 2? If you take 3?"
- "Is there a number of counters where the person whose turn it is ALWAYS loses?"
- "What if there are 4 left and it's your opponent's turn? Can they win?"

*Anticipated discoveries (in order of likelihood):*
1. "If there are 4 left on their turn, they lose!" → "Why? What happens if they take 1? 2? 3?"
   - Take 1 → 3 left, you take 3 and win.
   - Take 2 → 2 left, you take 2 and win.
   - Take 3 → 1 left, you take 1 and win.

2. "So I want to leave 4 for my opponent!" → "Great. How do you make sure you leave 4?"

3. "If there are 8 left on their turn, they also lose!" → "Why 8? ... Because no matter what they take, you can leave them 4."

4. The full pattern: Leave 4, 8, or 12 on opponent's turn. Since we start with 12 — "Wait, does that mean the SECOND player always wins?" → "If they know the strategy, yes!"

*Teacher move:* If no one discovers the full pattern, that's FINE. The important thing is that kids experience "reasoning backwards" — thinking about what position you WANT to create. If even one kid notices the "leave 4" insight, celebrate it hugely.

> "Here's the big idea: some games have a SECRET STRATEGY that lets one player ALWAYS win. Not all games — but Nim is one of them. How cool is that?"

*Differentiation:*
- **Too easy:** Change the rules: start with 15 counters, or allow taking 1–4. "Does the strategy change?" Also try "Misere Nim" — the person who takes the LAST counter LOSES.
- **Too hard:** Start with just 5 counters (take 1 or 2). This makes the pattern much easier to see. Play teacher vs. student with only 5, guiding them to the "leave 3" insight.

---

### Game / Play (15 min) — Tournament & Variations

**[35:00–40:00] Nim Tournament**

> "Time for a mini-tournament! We're going to see who the Nim champion is."

Run a quick bracket or round-robin (depending on group size):
- Pair kids up for 1-game matches.
- Winners advance to play each other.
- Losers get to keep practicing (and often figure out the strategy faster because they're motivated!).

*Teacher move:* If the tournament ends quickly (one kid dominates with the strategy), have the champion explain their approach to the group. If they can't articulate it clearly, that's fine — ask probing questions.

**[40:00–45:00] Nim Variation: "Poison"**

> "New version! Same rules, except now the person who takes the LAST counter LOSES. We call the last counter 'Poison.' Now what?"

Let kids play 2–3 games of Poison Nim.

*Key question:*
> "Does the same strategy work? Or do you need to change something?"

*Anticipated:* Kids who mastered regular Nim will be confused at first. The strategy reverses slightly (leave 1 for your opponent instead of 0).

**[45:00–50:00] 21 Game (Oral Nim)**

> "One more game. This one needs NO materials. We count together from 1 to 21. On your turn, you say 1, 2, or 3 numbers. The person who says '21' LOSES."

Play as a whole group: go around the circle, each kid says 1–3 numbers.

Example: Kid 1 says "1, 2." Kid 2 says "3." Kid 3 says "4, 5, 6." And so on.

> "Can you figure out a strategy? What numbers do you WANT to say? What numbers do you want to AVOID?"

*Anticipated:* Kids will quickly realize saying 20 is a winning move (forces the next person to say 21). Then they'll work backwards: 16, 12, 8, 4 are all "safe" numbers.

*Teacher move:* This is the same math as Nim with counters, but in a different package. If a kid notices: "This is just like the counter game!" — celebrate that connection loudly.

---

### Cool-Down & Journal (5 min)

**[50:00–53:00] Share Circle**

> "Let's go around. Tell me: did you figure out any strategy today? Or did something surprise you?"

*Anticipated responses:*
- "I figured out the Nim secret!" → "Can you explain it WITHOUT telling us the answer? Give us a hint."
- "The tower was really hard." → "What made it hard? Where did you get stuck?"
- "I liked the 21 game." → "Did you notice it's connected to Nim?"
- "I didn't figure anything out." → "That's honest. Did you have fun? Did your brain work hard? Then you did great."

**[53:00–55:00] Journal Time**

> "In your journal, write or draw one of these:
> - The Tower of Hanoi moves you made
> - Your Nim strategy (or what you THINK the strategy might be)
> - A question you still have
> - Your favorite moment from today"

---

### Chromebook Bonus (5 min)

**[55:00–60:00] Introduce the Week's Browser Game**

> "This week's Chromebook game is the **Tower of Hanoi** — the same puzzle we played today, but on screen. Let me show you."

**Game Description:** A browser-based Tower of Hanoi game. The player drags discs between pegs. A move counter shows the number of moves used. The game offers 3-disc, 4-disc, and 5-disc challenges. The goal is to solve in the minimum number of moves. Some versions show a "par" score to beat.

*Suggested resources:*
- [Tower of Hanoi - Math is Fun](https://www.mathsisfun.com/games/towerofhanoi.html)
- [Tower of Hanoi - Math Playground](https://www.mathplayground.com/logic_tower_of_hanoi.html)

> "Start with 3 discs — see if you can beat our class record of ___ moves. Then try 4 discs. I'll ask you next week how many moves 4 discs took!"

---

## Differentiation Summary

| Challenge Level | Adjustments |
|----------------|-------------|
| **Needs support** | Tower of Hanoi: Start with 2 discs only. Nim: Start with 5 counters, take 1 or 2. Provide verbal guidance: "What happens if you take 2?" Pair with a supportive partner. |
| **On target** | Standard activities: 3-disc tower, 12-counter Nim. Focus on recording moves and looking for patterns. |
| **Needs challenge** | 4–5 disc tower. Predict minimum moves before testing. Nim with variable counters and take-limits. Write "instructions" (algorithms) for solutions. Invent their own strategy game. |

## Zvonkin Principles in This Lesson

| Principle | Where It Appears |
|-----------|-----------------|
| Questions > Answers | "How many moves does 4 discs take?" is left open. Nim strategy is discovered, not told. |
| No explaining away | Teacher does not reveal Tower formula or Nim strategy. Kids must find it. |
| Discovery is the goal | The "leave 4" Nim insight and the Tower move-pattern are genuine mathematical discoveries. |
| Manipulatives matter | Physical discs, physical counters — not worksheets. |
| Fun is non-negotiable | Tournament generates excitement. 21 game is a crowd-pleaser. |
| Vary the packaging | Nim with counters, Nim as "Poison," Nim as the 21 game — same math, three forms. |
| Journal everything | Record Tower moves, Nim strategies, open questions. |
| Let chaos happen | Tournament gets loud. Kids argue about strategy. This is productive. |
