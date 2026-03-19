# Lesson 7: Topology & Shapes

## Theme
Topology & Shapes — the mathematics of stretching, bending, and surfaces

## Learning Goals
- Experience topology as "rubber sheet geometry" — shapes that can stretch but not tear
- Build and explore Mobius bands and discover their one-sidedness
- Count faces, edges, and vertices of 3D solids and stumble toward Euler's formula (V - E + F = 2)
- Encounter the four color map theorem as a hands-on coloring challenge
- Develop spatial vocabulary: face, edge, vertex, surface, inside, outside

## Zvonkin References
- Mobius bands: p. 49
- Faces, vertices, edges of cubes: p. 296
- Four color theorem: p. 198

## Materials Checklist
- [ ] Strips of paper, about 1 inch wide and 11 inches long (3 per kid, so ~45 strips)
- [ ] Tape (one roll per table)
- [ ] Scissors (one pair per kid)
- [ ] Markers or crayons (multiple colors per kid, at least 4 colors each)
- [ ] Wooden or plastic 3D shape sets: cubes, triangular prisms, square pyramids, tetrahedra (at least 1 set per table of 3-4 kids)
- [ ] Printed outline maps (simple, 6-8 regions — prepare a fictional "island" map), 2 per kid
- [ ] Recording sheet for faces/edges/vertices (table with columns)
- [ ] Whiteboard and markers
- [ ] Math journals
- [ ] Chromebooks with "Euler's Formula Explorer" bookmarked
- [ ] A donut and a coffee mug (optional, for the famous topology joke)

---

## Timed Script

### Opening Bell (5 min) — "Same or Different?"

**Setup:** Kids sit on the rug. Draw these shapes on the board: a circle, a square, a triangle, and the letter "O."

**Teacher says:** "Here's a weird question. Imagine these shapes are made of stretchy rubber — like a rubber band. You can pull them and bend them, but you can't cut them or glue them. Which of these shapes are secretly 'the same'?"

**Anticipated responses:**
- "The circle and the O are the same!"
- "You could stretch a circle into a square!"
- "The triangle is just a circle with corners!"
- "They're ALL the same!" (Bingo.)

**Teacher move:** Act surprised at whoever says they're all the same. "Really? You think a square and a circle are the same? That's a bold claim. Let's think about that today."

**Key question:** "What if I drew a figure-eight? Is that the same as a circle?" (No — it has a crossing point. This is a genuine topological distinction.)

**Teacher says:** "Today we're going to explore a kind of math where a donut and a coffee mug are the same shape. It's called topology."

(If you brought a donut and mug: hold them up. Kids will laugh. "They both have exactly one hole!")

---

### Main Activity 1 (15 min) — "The Mobius Band Laboratory"

**Setup:** Distribute paper strips, tape, scissors, and markers to each kid.

**Step 1 — Build a regular loop:**

**Teacher says:** "Take one strip of paper. Curl it into a loop and tape the ends together. Just a regular loop — like a bracelet."

(Wait for everyone to finish.)

**Teacher says:** "Now draw a line down the middle of your loop, going all the way around. Don't pick up your marker."

**Anticipated result:** They draw a line on the outside and it comes back to where they started. Easy.

**Key question:** "How many sides does your loop have?" (Two — an inside and an outside.)

**Step 2 — Build a Mobius band:**

**Teacher says:** "Now take a NEW strip. Before you tape it, give one end a HALF TWIST — flip it over once — then tape the ends together."

**Teacher move:** Demonstrate slowly. Walk around and help kids who struggle with the twist. This is fiddly for 7-year-olds. That's okay.

**Teacher says:** "Now draw a line down the middle again. Go all the way around without picking up your marker."

**Anticipated responses:**
- "Wait... the line is on BOTH sides!"
- "I'm back where I started but on the other side!"
- "It only has ONE side?!" (Excitement, confusion, disbelief.)

**Teacher move:** Let the astonishment land. Don't rush to explain. Ask: "What just happened? How is that possible?"

**Key question:** "How many sides does this shape have?" (One!)

**Step 3 — Cut the Mobius band:**

**Teacher says:** "Now take your scissors and cut along the line you drew — right down the middle. What do you THINK will happen?"

**Anticipated predictions:**
- "You'll get two loops!"
- "It'll fall apart!"
- "Two Mobius strips!"

**Teacher says:** "Cut and find out."

**Anticipated responses (after cutting):**
- "WHAT! It's one big loop!"
- "It's twisted!"
- "How??"

**Teacher move:** Revel in the surprise. This is pure mathematical wonder. Say: "Does anyone want to try cutting the big loop down the middle again?" (This produces two linked loops — even more surprising.)

**Step 4 (if time) — Cut one-third from the edge:**

**Teacher says:** "Make another Mobius band. This time, cut it not down the middle, but one-third of the way from the edge."

**Result:** Two linked loops of different sizes — one is a Mobius band, one is a regular loop. Absolute chaos and delight.

---

### Main Activity 2 (15 min) — "Counting Faces, Edges, and Vertices"

**Setup:** Distribute 3D shapes and recording sheets to each table. Each sheet has columns: Shape | Faces (F) | Vertices (V) | Edges (E).

**Teacher says:** "We're going to be detectives. Each shape has flat parts called FACES, pointy corners called VERTICES, and the lines where faces meet called EDGES. Your job is to count them for each shape and write them down."

**Demonstrate with a cube:**
- "How many flat faces?" (Hold it up, count together.) "Six!"
- "How many pointy corners — vertices?" "Eight!"
- "How many edges — the lines where two faces meet?" "Twelve!"

**Teacher says:** "Now do the same for every shape at your table. Be careful — edges are tricky to count. Try marking each one with a crayon dot as you count."

**While kids work:**
- Circulate and verify counts. Common errors: miscounting edges (skipping bottom edges), miscounting vertices on pyramids.
- If a pair finishes early, ask: "Can you find any pattern in your numbers?"

**The Big Reveal:**

After ~10 minutes, gather attention. Build a class table on the board:

| Shape | V | E | F | V - E + F |
|---|---|---|---|---|
| Cube | 8 | 12 | 6 | ? |
| Triangular prism | 6 | 9 | 5 | ? |
| Square pyramid | 5 | 8 | 5 | ? |
| Tetrahedron | 4 | 6 | 4 | ? |

**Teacher says:** "Let's fill in the last column. Vertices minus edges plus faces. For the cube: 8 minus 12 plus 6 is..."

**Anticipated response:** "2!"

**Teacher says:** "Interesting. Let's check the next one."

**Anticipated responses as the pattern emerges:**
- "It's 2 again!"
- "They're ALL 2!"
- "That's weird!"

**Key question:** "Will it ALWAYS be 2? Can you think of a shape where it isn't?" (Don't answer this. Let it hang. For the record, it's always 2 for convex polyhedra — but a donut-shaped solid breaks it.)

**Teacher says:** "This is called Euler's formula. A mathematician named Euler discovered it about 300 years ago. Vertices minus edges plus faces always equals 2. At least... for the shapes we've seen so far."

---

### Game / Play (15 min) — "The Four Color Challenge"

**Setup:** Distribute printed maps (fictional island with 6-8 regions) and crayons (at least 4 colors per kid).

**Teacher says:** "Here's a map of a made-up island. Your challenge: color every region so that no two regions that share a border have the same color. Regions that only touch at a single point don't count as sharing a border."

**Key question:** "What's the FEWEST number of colors you need?"

**Round 1 — Free exploration:**
- Let kids color. Most will use 5-6 colors at first.
- When someone finishes, ask: "Can you do it with fewer colors?" Give them a fresh map.

**Round 2 — The Four Color Dare:**
**Teacher says:** "Mathematicians proved that ANY map — no matter how complicated — can be colored with just 4 colors. Can you do this map with only 4?"

**Anticipated responses:**
- Some kids will succeed quickly
- Some will get stuck — "I need a 5th color!"
- Arguments about whether two regions "really" share a border

**Teacher move:** For stuck kids, suggest: "What if you erase that region and try a different color for it? Sometimes you have to go backwards to go forwards." This is a key life-and-math lesson.

**Round 3 — Design Your Own:**
**Teacher says:** "Draw your OWN map with at least 8 regions. Then trade with a partner. Can they four-color YOUR map?"

**Teacher move:** If a kid claims to have made a map that needs 5 colors, work through it with them. They'll find a 4-color solution — the theorem guarantees it. (But don't tell them that before they try!)

---

### Cool-Down & Journal (5 min)

**Teacher says:** "In your journal, write or draw the most surprising thing from today. The Mobius band? Euler's formula? The four-color map? Whatever surprised you most."

**Prompt ideas on the board:**
- "I was surprised that..."
- "I still don't understand how..."
- "I want to try..."

**Sharing:** 2-3 volunteers. Celebrate genuine confusion ("I don't get how the Mobius band has one side") as much as insights. Confusion means their brain is working.

---

### Chromebook Bonus (5 min) — "Euler's Formula Explorer"

**Teacher says:** "This week's game is Euler's Formula Explorer. You see 3D shapes on the screen and click to count faces, edges, and vertices. The game checks your count and then shows you V - E + F. See if the answer is always 2!"

**Game description:** Interactive 3D polyhedra viewer. Kids rotate shapes and click to highlight/count faces, edges, and vertices individually. Each click increments a counter and highlights the selected element in color to prevent double-counting. After counting all three, the game computes V - E + F and displays the result. Levels progress from simple shapes (cube, pyramid) to more complex ones (dodecahedron, icosahedron). A bonus level introduces a torus (V - E + F = 0) for advanced kids.

**Teacher says:** "Challenge for the week: Can you find V, E, and F for a shape with 20 faces? That one's called an icosahedron. Good luck!"

---

## Differentiation Notes

### If too easy:
- Mobius band: Challenge kids to predict what happens when you give the strip TWO half-twists before taping (this produces a two-sided surface — cutting it yields two linked loops)
- Euler's formula: Introduce a cylinder (V - E + F = 2 still? Actually, depends on how you define it — great discussion starter)
- Four color: Give them more complex maps with 15+ regions
- Ask: "What's the fewest colors needed for a map on a donut?" (7 — the seven color theorem for tori)

### If too hard:
- Mobius band: Pre-make some Mobius bands so kids who struggle with taping can still explore
- Euler's formula: Focus only on the cube and pyramid. Count together as a class.
- Four color: Start with a simpler map (4 regions). Pre-color one region to get them started.
- Pair kids strategically — a spatial thinker with a more verbal thinker
- For edge/vertex counting: use play-dough and toothpicks to BUILD the shapes, then count

---

## Zvonkin Principles in This Lesson
1. **Questions > Answers:** "How many sides does it have?" is asked, not told. Euler's formula is discovered from data, not stated as a rule.
2. **No explaining away:** The Mobius band is not explained — it is experienced. The wonder IS the point.
3. **Discovery is the goal:** V - E + F = 2 emerges from the kids' own counting.
4. **Manipulatives matter:** Paper strips, 3D solids, and maps — everything is touchable.
5. **Fun is non-negotiable:** Cutting a Mobius band is genuinely delightful. The four-color challenge is a game.
6. **Vary the packaging:** Three very different activities (paper craft, counting solids, coloring maps) all serve topology.
7. **Let chaos happen:** The Mobius band cutting will produce gasps, shrieks, and disorder. Welcome it.
