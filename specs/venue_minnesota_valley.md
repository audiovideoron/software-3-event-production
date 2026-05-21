# Venue Spec — Minnesota Valley Ballroom

## The Room

A rectangular ballroom, **118 feet wide by 60 feet deep**. Wider than deep — the long axis runs east-west. Used for general session, classroom, banquet, and movement-practice configurations.

**Ceiling height: 13' 9"** (low for a ballroom — has real consequences for screen height, line-array height, and projector placement).

## Walls and Partitions

- **Lobby wall** (north): four lobby doors, one per bay (see Airwalls below). Standard architectural quarter-arc swing.
- **Service wall** (south): **four service doors**. Positions and door widths _TBD — to be added once measured from the floor plan._
- **East and west walls**: short walls, no doors. May host portable projector screen positions during events (see "Symbols" below).

## Airwalls

The ballroom has **three airwalls** that divide the space into **four bays of roughly 29.5 feet wide × 60 feet deep** each. With all airwalls open, the room is the full 118 × 60. With airwalls closed, the room operates as up to four independent meeting spaces.

Constraints to remember when airwalls are closed:
- AV signal cabling (HDMI / HDBaseT / mic snake / power) cannot cross a closed airwall
- Acoustic isolation between bays is partial, not complete
- A closed airwall blocks sightlines from one bay into the next
- Equipment cannot be placed in the airwall track itself

## Stage

The standard stage is **24 feet wide by 12 feet deep**, built from **6′ × 8′ modular deck units**. The 24 × 12 footprint is six decks arranged three-wide by two-deep (each deck oriented 8' along the room width × 6' along the room depth). Deck height: _TODO — confirm, typical is 16" or 24"._

Stage positioning: typically against the south wall (service side), centered. Step units on both sides. Deck riser height _TBD — confirm._

## On-Stage / Adjacent Fixtures

- A **Tech operator station** at the stage's east edge — small labeled box, stagehand / monitor position.
- A **second Tech station — Front of House (FOH)** — floats at the top of the room. **This position is fixed by house infrastructure**: there is a permanent SDI + XLR snake drop at that location. Camera return and audio routing default to this point, so FOH should always be placed here when using house signal.
- A **zigzag line** along the south wall in front of the stage = **pipe and drape** (confirmed). Used to skirt the stage front and/or mask service-wall doors.

## Symbols (Cvent Prismm conventions in our drawings)

- **Fixed wall**: heavy outline with offset shadow stripe
- **Airwall**: thin single vertical line crossing the wall thickness (no shadow stripe)
- **Door swing**: quarter-arc
- **Projector screen**: Y-shape (horizontal line + projection cone). The Y marks where a **portable screen is deployed for the active layout** — the screens themselves are not wall-mounted. When an event spec calls for screens, they get placed at one of these established deploy positions or wherever the layout requires.
- **Tech station**: small labeled rectangle with two stacked monitor markers
- **Population label**: top of the drawing (e.g., "Classroom for 270")

## Standard Configurations Observed

- **Classroom for 270** — 5 columns × 9 rows of paired tables (back-to-back), 6 seats per pair, all airwalls open

_TODO: capture theater, banquet, rounds, and movement-practice capacities and standard layouts as we work through them._

## Rigging — Ground Support Only

**This room has no rigging points. All overhead support is ground-supported.** Combined with the 13'9" ceiling, this means:

- Truss must be ground-supported (towers, goalposts, totems) — no flown truss
- Line arrays must be on subs or short stacks; usable hang height ≈ 11'–12' max with safety clearance
- Lighting fixtures: trees and tower-mounted only
- Screens: freestanding tripod / cradle / pipe-and-base — no drop-down
- Projectors: floor-stand, table-stand, or projector-on-tower; no ceiling mount

## Power

_TBD — distribution panel locations, drop counts and amperages per bay._

## Lighting Controls

_TBD — house light dimming zones and control location._

## HVAC

Not tracked in our drawings for this room (not relevant to layout planning).

## Open Items

- [ ] Service wall door positions and widths
- [ ] Stage deck riser height
- [ ] Power drops: positions, amperage per drop
- [ ] Lighting controls / house light zones
- [ ] Standard configurations beyond Classroom-for-270 (theater, banquet, rounds, movement-practice)

## How to Use This Spec

Pair this venue file with an inventory file (gear catalog) and an event file (this event's requirements) to render a floor plan, generate a labor estimate, or produce a load-in schedule. Update this file when you learn a new fact about the room — the change propagates to every output that references it.
