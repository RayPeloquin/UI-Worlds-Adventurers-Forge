# U.I. Worlds — The Adventurer’s Forge

## Playtest packet v0.3 — Court consolidated

**Prepared for Ray Peloquin · 16 October 2026, America/New_York**  
**Status:** First tabletop playtest candidate, consolidated after the Court review. Numerical examples desk-checked; not playtested. Familiar access controls and automatic persistence remain software requirements, not implemented features.

An adventure RPG in which players investigate, invent, negotiate, and explore with individual U.I. familiars. Inventions accumulate technical histories. The campaign preserves a clear distinction between its own events and evidence about the real world.

**Core principle:** The world has consistent physical and declared magical rules. Players propose solutions and make choices. Dice resolve uncertain execution within those rules.

This is an original, system-neutral workshop and investigation layer with a minimal resolution system for the opening scene. Full combat, a complete D&D conversion, and a software implementation are outside this draft.

### Run the first session

One human can referee the four-adventurer scenario for one to four players; a smaller table can share character control. Keep the stated total load for this first playtest. For a solo review, one person may walk through the roles, but that does not test multiplayer fairness or private information.

1. Read the fixed Skybridge scene in section 11. Put its clock and shared inventory where everyone can see them.
2. Assign the ready characters in section 5, one familiar specialty per adventurer, and Story mode.
3. Read the public opening situation. Ask what each adventurer wants to do; offer the footpath and crew alongside the technical routes.
4. Give the one-sentence feasibility response before a commitment. Show more detail only when requested or decisive.
5. Resolve one committed action, then update the clock, inventory, ruling log, and affected compendium claims together.

Keep owner-private handouts separate. A shared conversation can portray several familiar voices, but it cannot give each voice privacy from information already in that conversation.

## 1. Start here: the table rules

1. Describe an intention in ordinary language.
2. The referee gives a short assessment: decisive constraint, known information, missing information, resources, time, and what a roll would decide.
3. Choose an approach. Agree on costs and possible consequences before committing.
4. Roll only for uncertain execution or discovery. Use a calculation or a declared world rule for a hard limit.
5. Record the outcome, including failed predictions and useful negative results.
6. Let players question a ruling through their familiar.

The Game Master keeps the game at the humans’ pace. Calculation time, model latency, rule discussion, and a valid challenge do not consume fictional time. An investigation or construction action does.

**Presentation dial:** Story shows constraints and choices; Workshop adds decisive numbers; Lab shows equations, assumptions, sources, and uncertainty. All three use the same underlying rules and adjudication.

**Familiar hint ladder:** Hint → Explain → Calculate → Challenge. The player chooses the depth and retains control of the character.

## 2. Five systems with separate responsibilities

| System | Responsibility |
| --- | --- |
| U.I. Game Master | Characters, setting, narrative, time, consequences, and disclosure of observations. |
| Physics Referee | Feasibility, model scope, numerical checks, explicit magical boundaries, and review of challenges. |
| Technology compendium | Claims, configurations, sources, calculations, tests, failures, and versions. |
| Campaign journal | Events, inventories, relationships, maps, agreements, and scoped precedents. |
| Manufacturing capacity | Available tools, materials, tolerances, processes, skilled labor, inspection, and time. |

A fluent explanation is not a calculation. A plausible calculation is not a validated model. A validated model of one configuration does not automatically validate a larger or modified configuration.

The referee may introduce new world content during ordinary storytelling. It may not invent a favorable rating, hidden component, resource, or performance curve solely to rescue an already committed technical action.

## 3. Feasibility before a roll

Use four assessment states:

| State | Meaning | Next step |
| --- | --- | --- |
| Supported under stated assumptions | The specified model and available evidence support the proposed operating point. | State remaining execution risks; offer a roll when needed. |
| Marginal or conditional | An identified margin is small or a condition needs confirming. | Show the condition and consequences; offer a test, redesign, or informed commitment. |
| Insufficient information | A decisive input, capability, or model is missing. | Identify the missing item and a way to obtain it. Do not invent failure odds. |
| Outside current limits | The proposal conflicts with a known limit or lacks a necessary resource or capability. | Explain the conflict and identify changes that could reopen it. |

Start with one sentence: **“[Assessment]: [decisive limit]; [what you can do next], with [main cost or risk].”** For example: “The original anchors have no established capacity, so a loaded crossing needs an assessment or another route; rolling for better knotwork cannot establish their strength.”

Use the following checklist to prepare that sentence and the commitment card. Story mode need not recite every field aloud.

Before commitment, state:

- **Goal:** what must happen, including payload, duration, environment, and acceptable consequences.
- **Basis:** established physical mechanism, explicit setting rule, or an unresolved hypothesis.
- **Bottleneck and margin:** show units and the relevant scope; mark unknowns.
- **Costs:** materials, fictional time, energy, and any irreversible loss.
- **Roll scope:** what workmanship, observation, coordination, or negotiation can change.
- **Alternatives:** normally one or two options, including a non-invention route where practical.

“Cracked anchors fail on a roll of 8 or lower” is not an engineering result. An abstract game risk can be declared as a house rule, but it must be identified as such. An unknown anchor capacity otherwise remains unknown until an appropriate investigation supplies evidence.

A good roll can reveal information the character could obtain, produce better workmanship within available materials, or identify an error in time. It cannot change a material’s established strength, create an unobserved source, or supply a missing manufacturing process.

## 4. Resources, manufacturing, and progression

Use four tracked quantities:

| Quantity | Definition |
| --- | --- |
| Materials | Inventory by type, quantity, and quality. Stock units simplify prices; they do not make wood interchangeable with cable or precision seals. |
| Time | Minutes, workshop hours, or declared scene beats. Use the same clock for all approaches. |
| Source energy | A numerical budget at a named boundary. In the opening scene, 1 energy unit = 10 kJ of electrical input energy. Also track maximum power. |
| Insight | A tagged lesson from an observation, controlled comparison, failed prediction, or corrected assumption. It is progression, not extra energy or secret knowledge. |

Acquire insight only when the party records something new that changes an understanding or design. Repeating an identical failure earns no additional insight. At most one insight is awarded per test objective and design version unless genuinely new evidence changes the conclusion.

For the first playtest, two relevant insight records can unlock **Practice +1** on related execution checks. A second pair can raise this to +2; +2 is the cap. Preserve the lesson records when spending insight. These bonuses do not change feasibility, source output, material ratings, or the time physically required for a process.

An in-world field test may establish campaign experience. It never awards real-world Demonstrated status. A familiar may improve planning and interpretation; it cannot waive a required test or measurement.

Manufacturing tiers are shorthand:

| Tier | Typical access |
| --- | --- |
| Field kit | Portable hand tools, available fasteners, simple builds, repairs, and assembly of suitable existing parts. |
| Workshop | Appropriate machine tools, fixtures, measurement, and controlled fabrication processes. |
| Specialist facility | Specialized materials, processes, inspection, and equipment for a specified demanding design. |

Each design still lists its actual capability requirements. A “Workshop” label alone does not authorize every pressure vessel, alloy, turbine, or tolerance. Hand tools can make some new objects; “field kit” does not mean repairs only. A simple skirt need not require an advanced foundry. Access to better equipment enables work, not automatic promotion of an evidence claim.

Reputation follows the campaign record: log who witnessed an outcome and what a faction values. A guild might require a witnessed test, while a merchant might value a useful result. Neither response changes the real-world evidence field.

## 5. Execution: minimal playtest rules

For the opening scene, roll a d20 and add the relevant rating:

- **Craft:** construct, repair, configure, or operate technical equipment.
- **Notice:** inspect, measure, navigate, or interpret accessible evidence.
- **Brawn:** physical effort and positioning.
- **Talk:** persuasion, bargaining, and coordination.

Use these ready characters, or distribute +5, +2, +1, and +0 among the four ratings:

| Character | Craft | Notice | Brawn | Talk |
| --- | ---: | ---: | ---: | ---: |
| Engineer | +5 | +2 | +1 | +0 |
| Scout | +1 | +5 | +2 | +0 |
| Guardian | +0 | +1 | +5 | +2 |
| Envoy | +1 | +2 | +0 | +5 |

The referee sets a target before commitment: 10 straightforward under pressure; 14 demanding; 18 very difficult. A scenario can specify another target with a stated reason.

Let margin = total roll − target.

| Margin | Default outcome |
| --- | --- |
| +5 or more | Clean success at the stated cost. |
| 0 through +4 | Success with a predeclared tradeoff, chosen where possible by the player. |
| −1 through −4 | Informative failure; apply the stated cost and report what was learned. |
| −5 or less | Failure with the predeclared consequence. Danger applies only if a credible hazard was established before the attempt. |

“Works once” is an optional tradeoff only when a physically consistent one-use variant was offered before commitment. If no valid flawed-success variant exists, a narrow success is simply success; do not invent a physically impossible flaw.

A natural 20 can include an additional supported observation, at the referee’s discretion. It neither bypasses feasibility nor guarantees discovery of a technological improvement. Roll outcomes are game abstractions, not calibrated real-world accident probabilities.

## 6. Compendium: three independent fields

The earlier single evidence ladder conflated different questions. Replace it with:

1. **Basis:** physical mechanism, fictional extension, or hybrid.
2. **Campaign record:** proposed, calculated in the campaign, built, tested under named conditions, field used, or retired.
3. **Real-world evidence:** attached to each specific claim, with its configuration and conditions.

Real-world claim statuses:

| Status | Required support |
| --- | --- |
| Unassessed | No adequate assessment has been recorded. |
| Research hypothesis | A testable proposal; the claimed effect or advantage is unresolved. |
| Calculated | A reproducible calculation or model, with inputs, sources, assumptions, scope, and limitations. |
| Demonstrated | An identified real configuration with observations or measurements supporting the specific claim under stated conditions. |
| Contradicted or withdrawn | Identified evidence defeats the claim, or its supporting argument has been withdrawn. Preserve the history. |
| Not applicable: fictional mechanism | A deliberate setting rule, not a claim of real-world physical existence. |

**Setting fiction is not the first rung of a ladder toward demonstrated science.** A calculation using a magical heat source can be a valid conditional calculation within the setting while that source remains fictional.

Demonstrated does not mean guaranteed, infallible, or valid at every scale. Record uncertainty, variability, and the tested envelope. Calculated does not mean “will work if the listed assumptions hold”; the model itself can be incomplete.

**Field modified is a configuration flag**, not an evidence grade. A modification creates a new version. Determine which earlier evidence still applies, which claims need recalculation, and which require retesting. Do not assign an automatic failure probability merely because a field modification occurred.

### Short record template

~~~text
NAME / ID / VERSION / AUTHOR:
FUNCTION AND SUCCESS CRITERION:
BASIS: physical | fictional extension | hybrid
CAMPAIGN RECORD: status, event IDs, conditions
REAL-WORLD CLAIMS: claim, status, configuration, source, uncertainty
MECHANISM / MAGICAL BOUNDARY:
LIMITS: mass, power, energy, time, environment, materials
COMPONENTS AND MANUFACTURING REQUIREMENTS:
TEST HISTORY / FAILURES / OPEN QUESTIONS:
CHANGE FLAGS: field modified? what changed? evidence affected?
VISIBILITY: public | party | owner | referee; allowed readers
~~~

Keep the player card short. Link longer calculations and test records by ID. Label testimony as testimony, measurements as measurements, and inferences as inferences.

## 7. Familiar rules and proposed access architecture

Every adventurer has one personal familiar, with a chosen primary specialty. Five base specialties are Cartographer, Engineer, Scholar, Naturalist, and Quartermaster. A specialty changes what the companion emphasizes and explains; it does not establish correctness.

These owner-facing example hints all use the public Skybridge facts. They are prompts for investigation, not additional observations or access to hidden answers.

| Specialty | First hint |
| --- | --- |
| Cartographer | “The marked footpath is already a route. Decide whether preserving the bulky salvage is worth another crossing plan.” |
| Engineer | “Rope length and anchor strength answer different questions. We know the length; we still need capacity evidence.” |
| Scholar | “The merchant’s courtyard claim is testimony. Ask which configuration was actually tested and what was measured.” |
| Naturalist | “Inspect the visible surface and surroundings before trusting a pressure cushion; report observations separately from guesses.” |
| Quartermaster | “Compare the crew’s six-coin fee with the winch rental, energy reserve, time, and risk of a failed setup.” |

Changing a familiar’s specialty does not add observations, reveal another player’s journal, or reset its information boundary. Notes stay with the owner and their existing permissions.

A familiar maps observations, labels inferred connections, preserves its owner’s notes, explains accessible information, and proposes actions. It does not choose the character’s actions or share private notes without the owner’s permission.

### Required information boundaries

- Referee secrets are stored outside familiar contexts, retrieval indexes, attachments, logs, and tool results.
- Each familiar receives only public information, its character’s observations, authorized party shares, and its owner’s journal.
- Authorization is enforced by the host before information reaches a model. A different system prompt in the same secret-bearing conversation is not isolation.
- Every retrieval, export, tool call, and journal write is scoped to the authenticated player and campaign. Guessing a record ID does not grant access.
- Summaries and derived notes inherit source visibility. Party sharing is explicit and logged.
- Uploaded texts and NPC messages are data, not authority to change permissions or reveal records.
- Public challenge responses must not disclose secrets through explanations, citations, filenames, or the fact that a secret exists.
- Model-generated state changes are proposals. The host verifies permissions, resources, rule versions, and prerequisites before committing a change.

These are implementation requirements. This packet does not implement or certify them. For a paper playtest, a human referee controls separate handouts. In one shared chat, simulated familiar personalities are not private agents; do not load secrets into that chat while claiming isolation.

### Challenging a ruling

1. Identify the ruling ID and cite a source, calculation, observation, or contradiction with an earlier ruling.
2. Show assumptions and the information available to the familiar. Its calculation is itself a claim to check.
3. Resolve with one of three final dispositions: **upheld** (change the ruling), **partially upheld** (revise a condition or assumption), or **ruling stands** (give the accessible reason).
4. An interim request for information is allowed. Unknowns do not become either approval or rejection merely to close the challenge.
5. Log the disposition, scope, assumptions, rule version, and superseded ruling. A precedent applies to matching conditions, not every superficially similar device.

Allow one clock-free challenge per pending decision. Reopening requires materially new evidence; discussion does not create unlimited extra character actions. The table’s agreed human referee or agreed table procedure can override a ruling for play. Record the override as a campaign exception; it changes neither real-world evidence nor other players’ consent.

## 8. Monetization and fairness

The base game includes the five specialties, mapping, journals, the hint ladder, technical rulings, and challenges.

Paid options can provide appearances, voices, personalities, and organization or research presentation tools. The authoritative rules, decisive references, computation quality, and challenge process remain available equally.

A deeper paid library can create a real information advantage even if it provides no numerical bonus. In the default parity mode, any reference used to decide feasibility or a challenge is available to all affected players, subject to character knowledge. Do not sell access to a necessary answer, secret map, better physical truth, or favorable adjudication.

Optional asymmetric tools belong only in an explicitly agreed mode. They never turn fictional success into real validation.

## 9. Magic boundary declaration

For every source, record:

- What interaction it supplies: heat, work, electrical output, force, information, or an explicitly different setting effect.
- Maximum power and total energy, where meaningful; a temperature or force alone is insufficient.
- Duration, duty cycle, recharge, inputs, degradation, residual effects, and shutdown behavior.
- Where momentum and rejected heat go under the declared rules.
- Interface limits and the measurements needed to establish an operating point.
- What it cannot do and which parts remain fictional.

Magic can intentionally change a law of the setting. Declare that change explicitly rather than describing it as established real-world physics.

### Example record TR-001: Skimmer-Mark II

**Version:** 0.2 · **Basis:** Hybrid · **Configuration flag:** Unmodified.

**Purpose:** Move a light load over a continuous, hard, smooth surface. It is not rated for crossing open space.

**Campaign mechanism:** An explicitly fictional Zephyr air mover feeds an ordinary pressure cushion beneath a skirt. Its declared limits are 1,000 W of delivered pneumatic power, 600 Pa maximum pressure rise, and 90 kJ of stored source energy. At full output that is 90 seconds. It consumes ambient air and supplies no separate antigravity effect or certified free-air thrust.

**Campaign geometry:** Circular footprint 1.8 m in diameter; mass 40 kg; proposed payload 80 kg; target clearance 20 mm. The payload is a design target, not a guaranteed rating.

**Conditional sizing calculation:** For 120 kg total supported mass, footprint area is 2.545 m² and uniform cushion pressure is about 462 Pa. With an illustrative edge coefficient 0.6 and air density 1.225 kg/m³, a simple edge-leakage model gives approximately 1.865 m³/s and 862 W of fluid power:

- Pressure difference = mass × gravity / area.
- Leakage flow = coefficient × perimeter × clearance × √(2 × pressure difference / air density).
- Fluid power = pressure difference × leakage flow.

This leaves only about 138 W for additional flow losses within the fictional 1,000 W limit. The assessment is **marginal**, with unmeasured flow losses and geometry effects. A coefficient of 0.7 would put this estimate just above 1,000 W even before those other losses.

**Campaign history:** The merchant reports courtyard operation. Treat this as testimony until inspected or tested. A field trial records its actual load, clearance, surface, energy, and duration.

**Real-world evidence:** Pressure-supported lift is an established mechanism. A 2026 ion-propelled micro-hovercraft paper reports tether-powered hover near a surface [S1]. That does not demonstrate this 1.8 m platform or its fictional air mover. The platform configuration is unvalidated in reality; the Zephyr mechanism is Not applicable: fictional mechanism.

**Manufacturing:** Skirt fabrication, suitable structure, sealed flow paths, measurements, and the fictional air-mover interface. No automatic entitlement to these from a generic workshop tier.

**Failure modes and questions:** Leaks, uneven surfaces, pressure loss, inadequate source output, insufficient clearance, or loss of the nearby supporting surface. Inverting the unit does not establish a new thrust rating.

### Example record TR-002: Emberseal heat engine

**Version:** 0.2 · **Basis:** Hybrid · **Campaign record:** Calculated only.

**Fictional source:** An Emberseal delivers up to 2,000 W of heat at a source temperature of 400°C for 600 seconds, for a maximum delivered heat budget of 1.2 MJ. Those values are setting rules, not evidence of a real material.

**Conventional subsystem:** A heat engine with a 25°C sink. The temperature-based Carnot ceiling is 1 − 298.15/673.15 = approximately 55.7% [S3]. This is an upper bound, not a prediction of actual performance.

**Illustrative campaign assumption:** Gross heat-to-shaft efficiency is 10%; auxiliaries consume 20 W of that mechanical output. Gross shaft output is 200 W, net useful mechanical output 180 W, and total heat rejection including auxiliary dissipation is 1,820 W. Over 600 seconds, net useful work is 108 kJ.

If the heat exchanger, cooling system, engine, and auxiliaries cannot support that operating point, the output must be reduced or operation stopped. Neither the efficiency nor cooling capability is established merely by passing the Carnot check.

**Real-world evidence:** The heat-engine relationships are calculated under stated assumptions. The particular engine is unbuilt and unvalidated. The Emberseal remains fictional even if the engine performs successfully in the campaign.

**Manufacturing:** Appropriate rated components, fabrication, inspection, cooling, controls, and a compatible source interface. The record grants no general ability to fabricate demanding containment equipment.

**Open questions:** Actual efficiency, exchanger capability, sink performance, startup energy, residual heat, degradation, and operating envelope. Those require data or explicit campaign parameters before a field deployment.

## 10. Session zero

Agree on:

- Story, Workshop, or Lab presentation; players may request another depth during play.
- What physics is retained and which magical exceptions are declared.
- Who controls each character and how the human table resolves disputes.
- Familiar visibility, private journals, and what information players may share.
- Turn clock, challenge procedure, consequence severity, and pause/stop signals.
- Whether outcomes use tabletop dice, a recorded software roll, or fixed illustrative rolls.
- Familiar payment parity and any explicitly agreed asymmetric mode.
- How state is saved and how incorrect journal entries are corrected.

The journal is an editable record with a revision history. “The AI remembers” is not a persistence guarantee.

## 11. The Broken Skybridge — canonical v0.3 scene

**Scope:** A noncombat opening encounter for four characters and their familiars. The physical fixtures below are fictional campaign facts declared before play. They are not real construction specifications or equipment certifications.

Earlier examples mixed 60-foot and 120-foot spans, a 22 m span, three-minute and fifteen-minute clocks, and different platform clearances and payloads. This manifest is the single scene specification for this playtest. A different variant needs its own configuration ID and revised calculations and costs.

### Public situation and resources

| Item | Fixed scene value |
| --- | --- |
| Broken main bridge | 60 ft / 18.288 m gap. |
| Countdown | 12 fictional minutes: 24 beats of 30 seconds. |
| Party + gear + loaded carriage | 600 kg total for the full-load crossing. Familiar bodies are included if present. |
| Party supplies | 80 ft / 24.384 m utility rope; two unrated iron pitons; tools; 8 stock units of tagged materials; 8 coins; 30 electrical energy units = 300 kJ. |
| Original stone anchor points | Visibly cracked. Capacity unknown. |
| Merchant’s skimmer | TR-001. No documented open-gap operating point. |
| Maintenance crossing | Separate existing cable and carriage between intact service pylons; a visible service manifest can be inspected. |
| Alternative | A marked footpath takes 8 beats; bulky carriage salvage worth 4 stock units must be left behind. Personal essentials can be carried. No invention or roll is required. |

The 80-foot rope is long enough for the straight gap but has no established load capacity. Two unrated pitons in cracked masonry do not establish an adequate anchoring system.

The maintenance crossing is visible from the start, not a convenient item invented after a failed proposal. Its fictional service manifest specifies a 650 kg carriage limit and a 40 kN allowable service load at each cable attachment in the required directions, with the installed route’s envelope already assessed in-world.

Its existing winch is available for 2 coins. The manifest specifies up to 2 kN traction, a governed 0.4 m/s loaded speed on this route, electrical input up to 1.3 kW, and a stated route demand no greater than 1.5 kN for this load. Those are scenario inputs, not deductions from mass alone. Inspection must confirm the fixture identity and condition before relying on the manifest.

### Offered approaches

| Approach | Costs and limits |
| --- | --- |
| Take the footpath | 8 beats; leave the bulky salvage. |
| Hire the maintenance crew | 6 coins; 7 beats; preserve the full load. No player engineering roll; the crew uses the declared maintenance crossing. |
| Operate the maintenance crossing | 2 coins; inspect 2 beats, prepare 2 beats, cross 2 beats; reserve 10 energy units. Craft target 12 for the specified carriage setup after the inspection supports use. |
| Repair the full main span | Currently blocked by missing structural members and processes. A rope and pitons do not replace an 18.3 m bridge. This can become a later project. |
| Use the skimmer across the gap | No supported free-air operating point. Test or redesign first; a roll cannot supply missing support. |

Players may propose other actions. Assess them against the same world facts. Negotiation, investigation, distraction, and retreat remain valid choices; engineering is never the mandatory solution.

### Maintenance crossing: calculation shown in Lab mode

For one idealized central-point-load case, neglect cable mass and wind and assume a 1.5 m loaded midpoint sag:

- Weight W = 600 × 9.80665 = 5,883.99 N.
- Horizontal cable component H = W × span / (4 × sag) = 17.93 kN.
- Tension at each end = √(H² + (W/2)²) = 18.17 kN.
- With an illustrative 1.5 load factor applied to this case: 27.26 kN per end.

The 1.5 factor is a declared modeling assumption, not a generally applicable design factor. This check does not certify the route or include every load case. The fictional installed-route manifest supplies the additional scenario assumptions. If its scope or condition cannot be established, the assessment returns to Insufficient information.

At 0.4 m/s, traversing the gap takes 45.72 seconds. Book two beats, or 60 seconds, for travel. At 1.3 kW, 60 seconds uses 78 kJ. Add a 20 kJ startup reserve: 98 kJ, rounded to 10 energy units / 100 kJ. Inspection, preparation, and travel together cost six beats / three minutes.

### Spending and recording the crossing

Resolve the crossing in stages so a failed setup does not spend an unattempted journey:

1. **Inspect:** spend two beats. If the manifest or condition cannot be confirmed, return to Insufficient information and reassess.
2. **Rent and prepare:** pay two coins, reserve ten energy units, and spend two preparation beats. The setup is mechanical and unpowered. Roll against Craft 12 with the outcomes below.
3. **Depart after successful setup:** spend two travel beats and debit the ten-unit operating allowance. In this simplified scene, the allowance includes startup and transit; unused operating margin is not separately tracked.
4. **If setup fails:** no departure and no powered trial occur. Release the energy reservation. The rental fee and four beats already spent on inspection and preparation remain spent; apply any stated stock loss.

After each stage, record the resource change and observation. A proposed journal update is checked against the action before it becomes the agreed record. If a correction changes resources or a claim, link the corrected entry to the original rather than silently rewriting history.

### Roll consequences, stated before commitment

The setup roll verifies uncertain operation of the existing service-compatible carriage hardware. It cannot restore cracked anchors or increase an equipment rating.

- Margin +5 or more: clean setup.
- Margin 0 to +4: setup works, but a guardian must attend the manual brake during transit and cannot perform another action then.
- Margin −1 to −4: the latch indicator fails its check; nobody departs. Spend the preparation time, record the defect, and choose repair, crew assistance, or another route.
- Margin −5 or less: an assembly tool is damaged; lose 1 stock unit and the preparation time. Nobody departs.

These branches are abstract play outcomes. No participant is suspended over the ravine merely because a failed setup roll occurred.

At clock expiry, the approaching dragon arrives and blocks the main ledge. It begins an encounter with choices and consequences; it does not cause an automatic party death. The footpath remains available until the party’s established position or actions change that fact.

### Optional platform investigation

A trial on continuous paving may establish performance for its tested load, clearance, source state, and duration. Agree on an obtainable measurement and a controlled setup first. State its time and energy cost before committing; draw energy from the platform’s own source, not the party’s electrical budget unless an interface is established.

Do not assume a rock test over the ravine is low risk or that the machine will catch itself near a wall. A nearby sidewall does not establish the continuous supporting surface assumed by the cushion model. If recovery, restraint, or safe handling cannot be established, say what is missing and offer a different test.

Record the result narrowly:

- **Campaign:** what the characters observed, with load, surface, clearance, duration, and event ID.
- **Conditional calculations:** which predictions agree with the observation and which need revision.
- **Still unresolved:** untested payloads, open-gap performance, changes of scale, and other conditions.
- **Real world:** unchanged by the fictional trial. A successful scene is not an external measurement.

The trial may answer a useful question without making the platform a viable crossing.

## 12. Sample exchange: the brass owl challenges the ruling

This is a scripted demonstration, not a record of an actual roll or experiment.

**Player:** “Can we invert the skimmer’s core and use it to pull the whole party over a cable?”

**Referee, preliminary and erroneous:** “A 1.5 kN thrust should move the 600 kg party. It can cross in 35 seconds, so roll to modify the seals.”

**Barnaby, Engineer Familiar:** “Challenge R-001. The source card gives pneumatic power and pressure limits, not 1.5 kN of free-air thrust. Inverting a pressure-cushion assembly does not preserve its supporting force. We also have no complete cable or anchor assessment. The party weighs about 5.88 kN; a cable would carry that weight, and propulsion along it needs a separate slope, friction, speed, and power assessment.”

**Barnaby:** “The proposed 35-second transit over 18.288 m implies an average speed about 0.523 m/s. Even if the unsupported 1.5 kN figure were accepted, force times that speed would be about 784 W of vehicle work rate. That is not the total source power required by a jet, and it does not establish endurance or temperature.”

**Referee:** “Challenge upheld. I withdraw the invented thrust, transit-time approval, and seal-temperature limit. The proposed conversion is currently Insufficient information. We can investigate its output, use the existing maintenance crossing, hire the crew, or take the footpath.”

**Player:** “Inspect the maintenance crossing and its service manifest. We’ll use its existing winch if it checks out.”

**Referee:** “The two-beat inspection confirms the fixture identity and stated scenario condition. Under that manifest, the crossing is supported. From here: pay 2 coins, reserve 10 energy units, then spend two preparation beats and, on success, two travel beats. That is six beats including the inspection already completed. The Craft target is 12, with the previously stated setup outcomes.”

**Illustrative fixed roll:** d20 shows 14; Engineer Craft +5; total 19; margin +7.

**Referee:** “The carriage locks correctly. The party crosses with the full load within the reserved interval.”

**Journal update:** R-001 superseded by R-002; fixture manifest referenced; 2 coins and 10 energy units spent; six beats elapsed. Party remainder: 6 coins, 20 energy units, 18 beats, and unchanged stock.

**Compendium update:** Maintenance Crossing Procedure v0.1 records one successful campaign use under the manifest conditions. The Skimmer conversion remains an unresolved proposal. No real-world evidence status is promoted.

## 13. Prior art and publication position

Preliminary landscape review, not proof of uniqueness:

| Reference | Documented overlap |
| --- | --- |
| Concordia [S4] | A Game Master interprets natural-language actions and checks physical plausibility in simulated environments. |
| DiscoveryWorld [S5] | Hypotheses, experiments, measurements, and explanatory discoveries in a simulated world. |
| UNF STEM tabletop project [S6] | Tabletop play combining STEM content with claim–evidence–reasoning. |
| CALYPSO [S7] | LLM assistance for Dungeon Masters. |
| GURPS Vehicles [S8] | Detailed vehicle design as part of roleplaying. |
| Ars Magica [S9] | Research, laboratory work, and learning from experimental results. |
| Numenera Technology Compendium [S10] | A large collection of advanced fictional technologies for adventures. |
| Familiar for Foundry VTT [S11] | AI assistance, player interaction, campaign memory, and rules enforcement. Its public FAQ also explicitly warns about revealing secrets that the model can read. This is product documentation, not an independent security audit. |
| Friends & Fables [S12] | AI-run campaigns with memory, multiplayer, maps, and world-building. These are advertised features, not independently verified here. |

The proposed contribution is the integration of scoped companion knowledge, contestable technical rulings, calculations and sources tied to claims, and separate fictional and real evidence records. Each ingredient has precedents. The full combination has not been established as unique, and competitor feature absences have not been audited.

The SRD 5.2.1 is an available foundation for a later D&D adapter [S13]. This draft does not reproduce SRD rules text or claim completed compatibility. A version incorporating SRD material must include the attribution and license notices specified by that exact SRD and clearly identify original additions.

## 14. First playtest: observations to collect

Run the scene in Story mode first. Track:

1. Could players identify at least one feasible route and the decisive constraint without a lecture?
2. Were costs and possible roll consequences stated before commitment?
3. Could Insufficient information remain unresolved without the referee inventing a rating?
4. Did a challenge change a wrong ruling without exposing secret information?
5. Did failure produce a new lesson rather than repetitive insight farming?
6. Did any campaign event incorrectly promote a real-world claim?
7. Could the non-invention route resolve the scene?
8. Could the saved state reconstruct the clock, inventory, rulings, and record versions?

An implementation later needs permission tests for cross-player reads, guessed IDs, secret-bearing retrieval, contaminated summaries, source visibility on appeals, and attempted prompt instructions inside documents. Those tests have not been run: no software access-control system has been built in this packet.

### Save-state stub

~~~text
Campaign / scene / rules version:
Clock and committed actions:
Characters / inventories / source budgets:
Public observations and map:
Owner-private notes and allowed readers:
Compendium versions and claim statuses:
Rulings, scopes, and superseded IDs:
House-rule exceptions and who agreed:
Open questions / next scene:
~~~

## 15. Court resolution ledger

This closes consolidation for v0.3. The following decisions reconcile conflicting suggestions; they are design choices for a playtest, not claims of consensus or validation.

| Court proposal | v0.3 disposition |
| --- | --- |
| Plain-language feasibility before commitment | Adopted. One decisive sentence first; details follow the presentation dial. |
| Translate physical difficulty into a higher DC | Limited to uncertain execution of an eligible action. Missing energy, capacity, or information requires a changed design, evidence, or resource. |
| Give cracked anchors a low-roll failure threshold | Not a calculated engineering result. Capacity stays unknown unless assessed, or an explicitly named house-rule risk is agreed. |
| Keep one ladder containing fiction, calculations, and demonstrations | Replaced by separate basis, campaign record, and real-world claim evidence fields. |
| Treat “Field modified” as evidence | Configuration flag and new version; review which previous evidence still applies. |
| A platform test confirms it can cross the ravine | A test supports only the observed claim and conditions. Paved-surface hover does not demonstrate open-gap operation. |
| Assume less than 10% remaining lift over the gap or an automatic sidewall recovery | No supporting performance model or observation supplied. These outcomes are not established scene facts. |
| Use different platform clearances, payloads, and heat-source ratings interchangeably | Keep separate variants. This packet retains TR-001 and TR-002 in section 9; the device parameter sets remain unchanged from v0.2. |
| Award broad adventure-long advantage for a demonstrated or modified item | Use the bounded, relevant Practice progression in section 4. A modification alone earns no benefit. |
| Manufacturing tiers promote a claim or prohibit all new field construction | Track the required processes. Equipment access enables fabrication and tests; it does not itself supply evidence. |
| Swap familiar specialties for different hints | Allowed with the same owner-visible information and journal permissions. No secret knowledge pooling. |
| Sell better thermodynamics or more authoritative answers | Preserve equal decisive information, computation quality, and access to challenges. Optional presentation and personality can differ. |
| Call the four systems “live,” memory persistent, or familiar secrecy enforced | Requirements for later software. This deliverable is a tabletop packet, with human-managed records and handouts. |
| Describe the integrated approach as unique prior art | Keep the sourced landscape and specific proposed features; uniqueness remains unestablished. |

### Changes from v0.2

Added a short session launch, specialty hint examples, a staged spend-and-reserve procedure, platform-test recording guidance, and this decision ledger. Clarified field fabrication and faction reputation. The cable, cushion, and heat-engine example parameters and arithmetic are unchanged.

## Sources

Sources checked during the concept review on 16 October 2026. References support their stated mechanisms or documented features; they do not validate the fictional equipment.

- **S1:** [Nelson et al., Design and Flight of an Ion-propelled Micro Hovercraft Leveraging Ground Proximity Effects (2026)](https://arxiv.org/html/2608.04343v1)
- **S2:** [OpenStax, University Physics Volume 1, Examples of Static Equilibrium](https://openstax.org/books/university-physics-volume-1/pages/12-2-examples-of-static-equilibrium)
- **S3:** [OpenStax, University Physics Volume 2, The Carnot Cycle](https://openstax.org/books/university-physics-volume-2/pages/4-5-the-carnot-cycle)
- **S4:** [Vezhnevets et al., Concordia (2023)](https://arxiv.org/abs/2312.03664)
- **S5:** [DiscoveryWorld project](https://allenai.github.io/discoveryworld/)
- **S6:** [UNF, Developing a STEM Education Tabletop Roleplaying Game for Informal Science Learning](https://scholars.unf.edu/en/projects/developing-a-stem-education-tabletop-roleplaying-game-for-informa/)
- **S7:** [Zhu et al., CALYPSO (2023)](https://arxiv.org/abs/2308.07540)
- **S8:** [Steve Jackson Games / Warehouse 23, GURPS Classic: Vehicles](https://warehouse23.com/collections/steve-jackson-games/products/gurps-classic-vehicles)
- **S9:** [Ars Magica Definitive Edition publisher FAQ](https://arsmagica.backerkit.com/faq)
- **S10:** [Monte Cook Games, Technology Compendium](https://www.montecookgames.com/store/product/technology-compendium-sir-arthours-guide-to-the-numenera/)
- **S11:** [Familiar official site and FAQ](https://familiarvtt.com/)
- **S12:** [Friends & Fables official site](https://fables.gg/)
- **S13:** [Wizards of the Coast, official SRD page](https://www.dndbeyond.com/srd)

**Revision note:** Court consolidation is complete for v0.3. The next evidence comes from a human playtest: choice clarity, pace, accurate resource records, useful challenges, and whether technical reasoning improves the adventure. Software behavior and real-world invention claims remain separate work.

