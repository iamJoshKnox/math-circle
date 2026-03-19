# Lesson 8: Codes & Ciphers

## Theme
Codes & Ciphers — secret messages, symbol substitution, and the structure hidden in language and number

## Learning Goals
- Experience code-breaking as genuine mathematical reasoning (pattern recognition, logical deduction)
- Learn a simple substitution cipher and use it to encode and decode messages
- Encounter the idea that numbers can be represented in different bases (positional systems)
- Develop systematic thinking: keeping track of what you know, what you don't, and what you can infer
- Appreciate that math is not just about numbers — it's about patterns and structure

## Zvonkin References
- Breaking a code: p. 145
- General philosophy on puzzles and reasoning: throughout

## Materials Checklist
- [ ] "Mysterious Message" worksheets — 3 short encoded sentences using symbol substitution (prepare in advance, see below)
- [ ] Alphabet-to-number key (A=1, B=2, ... Z=26) printed, one per kid
- [ ] Blank cipher wheel templates (two concentric circles with letters, fastened with a brass brad) — one per kid, pre-cut
- [ ] Brass brads / paper fasteners (15+)
- [ ] Scissors
- [ ] Pencils and scratch paper
- [ ] Index cards (for writing secret messages)
- [ ] Base-10 blocks (units, rods, flats) — 1 set per table
- [ ] Whiteboard and markers
- [ ] Math journals
- [ ] Chromebooks with "Code Breaker" game bookmarked

---

## Timed Script

### Opening Bell (5 min) — "A Message from a Mathematician"

**Setup:** Before kids arrive, write this on the board in large letters:

```
20-8-9-19   9-19   13-1-20-8   3-9-18-3-12-5
```

**Teacher says:** (pointing at the board, looking puzzled) "I found this message taped to the door this morning. I think a mathematician left it for us. Can anyone figure out what it says?"

**Anticipated responses:**
- Kids stare, confused
- Someone might notice the numbers go up to 26 — "Like the alphabet!"
- "T is the 20th letter!"
- Slowly: "T... H... I... S..."

**Teacher move:** Let them work it out together. Help only if they're totally stuck after 2 minutes. Write the alphabet with numbers underneath on the board if needed (A=1, B=2, etc.).

**The answer:** THIS IS MATH CIRCLE

**Key question:** "How did you figure that out? What was the first clue that cracked it?"

**Teacher says:** "Today we're going to become code-makers AND code-breakers."

---

### Main Activity 1 (15 min) — "Crack the Code"

**Setup:** Distribute "Mysterious Message" worksheets. Each worksheet has 3 short sentences encoded with a simple symbol substitution (not numbers — use shapes, squiggles, and made-up symbols so it feels genuinely mysterious).

**The cipher (for teacher reference):**
Each letter maps to a unique symbol. The three sentences are:
1. "MATH IS FUN" (simple, short words, repeated letters)
2. "CATS AND DOGS" (introduces more letters)
3. "EVERY PUZZLE HAS A SECRET" (longer, uses almost all previously decoded letters plus new ones)

The worksheet includes a blank decoder key at the bottom (symbol | letter) for kids to fill in as they crack each symbol.

**Teacher says:** "These messages are written in a secret code. Every symbol stands for one letter — and it's the same letter every time. Your job: figure out what every symbol means. Work with your table. Talk to each other. Here's a hint to start: the first message is three words."

**Key question:** "Where should you start? What's the easiest thing to figure out first?"

**Anticipated strategies:**
- "The one-letter word must be A or I!"
- "This symbol shows up a lot — maybe it's E or T"
- "If that's A, then this word is A-something-something..."
- "The second word in Message 1 is only two letters — IS, IT, IN, IF..."

**Teacher move:** Circulate. When kids are stuck, ask:
- "Which symbol appears most often? What letters appear most often in English?"
- "Can you figure out any short words first?"
- "If you think this symbol is T, does that work everywhere T appears?"

**Do NOT solve it for them.** If a table is really stuck after 8 minutes, reveal ONE symbol and see if that unlocks progress.

**When tables finish:** "Check your work — does every decoded sentence make sense as English? If something looks like gibberish, you might have a wrong letter somewhere."

---

### Main Activity 2 (15 min) — "Build Your Own Cipher & Secret Messages"

**Part A — Cipher Wheels (7 min):**

**Setup:** Distribute cipher wheel templates and brass brads.

**Teacher says:** "Now you're going to make your own code machine. This is called a cipher wheel. The outer ring has the regular alphabet. The inner ring also has the alphabet. When you turn the inner ring, each letter shifts to a new letter."

**Demonstrate:** Set the wheel so A on the inner ring lines up with D on the outer ring. "Now A becomes D, B becomes E, C becomes F... This is called a Caesar cipher because Julius Caesar used it to send secret messages to his army."

**Teacher move:** Help kids assemble their wheels. This is a fine-motor challenge — some will need help with the brad.

**Key question:** "If I shift by 3, A becomes D. What does Z become?" (C — it wraps around! This is modular arithmetic, but don't use that term.)

**Part B — Secret Message Exchange (8 min):**

**Teacher says:** "Set your cipher wheel to any shift you like. Write a short secret message on an index card — at least 4 words. Then write your shift number on the BACK of the card. Trade with someone at a different table. Decode their message!"

**Rules:**
- First try to decode WITHOUT looking at the shift number on the back
- If stuck, you can peek at the shift number

**While kids work:**
- Expect giggles, excitement, frustration
- Some kids will make encoding errors — great teaching moment: "Codes only work if you're precise"
- If someone cracks a code quickly: "Can you figure out the shift WITHOUT looking at the back?"

**Key question:** "What makes a code hard to break? What makes it easy?"

**Anticipated responses:**
- "Longer messages are easier to break because you have more clues!"
- "Short shift numbers are easy because A is almost still A"
- (This is actually the opposite of what they might expect — celebrate the paradox)

**Bridge to positional systems (last 2 minutes):**

**Teacher says:** "So we can use numbers for letters. But did you know we can also change how numbers WORK? When you write 23, that means two tens and three ones, right? But what if we only had the digits 0 and 1?"

Put up on the board: "In computer code, 1 means 1, 10 means 2, 11 means 3, 100 means 4."

**Key question:** "Can you guess what 101 means?" (5.) "This is how computers talk — they only know 0 and 1. It's called binary."

Don't belabor this. Plant the seed and move to the game.

---

### Game / Play (15 min) — "Code Breaker Challenge"

**Setup:** Three rounds, increasing in difficulty. Kids work in teams of 3.

**Round 1 — Number Code Relay (5 min):**
- Write an encoded message on the board using A=1, B=2, etc.
- Message: "7-15-15-4   10-15-2" (GOOD JOB)
- First team to decode it correctly (all members must agree) wins.
- Follow with a second message: "25-15-21   1-18-5   19-13-1-18-20" (YOU ARE SMART)

**Round 2 — Caesar Crack (5 min):**
- Write a Caesar-shifted message on the board (shift of 5):
- "RFHWJY RZNJ" (SECRET SOME — actually, encode "MATH ROCKS" with shift 5: "RFYM WTHPX")
- Wait — let me re-encode carefully. Shift 5: M->R, A->F, T->Y, H->M = "RFYM"; R->W, O->T, C->H, K->P, S->X = "WTHPX"
- So the encoded message is: "RFYM WTHPX"
- Teams can use their cipher wheels to try different shifts.
- Hint if stuck: "Try a shift of 5."

**Round 3 — Symbol Swap Showdown (5 min):**
- Each team writes a 3-word message using their own invented symbols (not the cipher wheel — completely made-up symbols).
- Teams swap messages AND a key showing 3 of the symbols decoded.
- Teams race to crack the rest.

**Teacher move during all rounds:**
- Keep energy high: "Team 2 is closing in! Team 4 just cracked the first word!"
- Celebrate both speed and accuracy: "Team 1 was fast, but Team 3 decoded every letter perfectly."

---

### Cool-Down & Journal (5 min)

**Teacher says:** "In your journal, write a secret message to yourself using any code you learned today. On the next page, write the key to decode it. Next week, see if you can still read your own message!"

**Alternative prompt:** "Draw a picture of your cipher wheel. Write about what made code-breaking hard or easy."

**Sharing:** Ask 2-3 kids to read an encoded message aloud (just the code — not the answer). The class can shout out guesses. Keep it light and fun.

---

### Chromebook Bonus (5 min) — "Code Breaker"

**Teacher says:** "This week's game is Code Breaker. You'll see an encoded message and you have to figure out what each symbol means. The game gives you hints — like how often each symbol appears — and you drag letters onto symbols to decode the message."

**Game description:** Browser-based cryptogram solver. A short encoded sentence appears with symbols replacing letters. A frequency chart shows how often each symbol appears (mirroring real letter frequency analysis). Kids drag letter tiles onto symbols to guess the substitution. Correct placements lock in green. Wrong guesses are gently flagged ("Hmm, that doesn't seem right"). Levels progress: Level 1 uses A=1 number codes, Level 2 uses simple symbol substitution with common words, Level 3 introduces Caesar ciphers where kids must figure out the shift. A bonus level lets kids encode their own messages to share via a classroom code.

**Teacher says:** "Challenge: Can you get to Level 3 this week? If you crack a Caesar cipher without hints, write CODEMASTER in your journal and show me next week."

---

## Differentiation Notes

### If too easy:
- Introduce frequency analysis: "E is the most common letter in English. Which symbol appears most?"
- Multi-layer codes: First decode numbers to letters, then apply a Caesar shift
- Binary challenges: "Write your age in binary. Write today's date in binary."
- Create a Polybius square (5x5 grid cipher) — this involves coordinates, bridging to graphing
- Ask: "Can you make an unbreakable code?" (This leads to one-time pads — genuinely deep cryptography)

### If too hard:
- For the symbol worksheet: provide the first 5 letters already decoded
- Simplify messages to 2-3 letter words: "A CAT SAT"
- For cipher wheels: set everyone to the same shift (3) and decode as a class first
- Buddy system: pair a strong reader with a less confident one
- Skip the binary teaser entirely if the group is overwhelmed
- Physical letter tiles that kids can move around are easier than writing for some kids

---

## Zvonkin Principles in This Lesson
1. **Questions > Answers:** "What letter could this be?" is asked, never told. The whole session is one long deductive puzzle.
2. **No explaining away:** The binary teaser is planted, not explained. Let it ferment.
3. **Discovery is the goal:** Every decoded message is a personal triumph.
4. **Manipulatives matter:** Cipher wheels are physical tools kids build and keep.
5. **Fun is non-negotiable:** Secret messages are inherently thrilling for 7-year-olds. Spies! Codes! Mystery!
6. **Vary the packaging:** Number codes, symbol codes, Caesar ciphers, binary — same idea, many costumes.
7. **Journal everything:** The journal becomes a secret codebook.
8. **Let chaos happen:** The message exchange will be loud and messy. Good.
