# Sample Completed Audit — Hong Yuen Technology Co., Ltd.

> **This is a worked example.** It is an audit of a **small office building** — an IT services company, 22 staff, one leased floor above a ground-floor lobby. **Not a school.** Read it to see the expected depth of observation: what a good evidence sentence looks like, how a "Present but Weak" rating is justified, and how a recommendation is tied to a specific finding.
>
> It was produced on a 20-minute walk with a clipboard. It is not a comprehensive security assessment, and section 6 says so honestly.

**Auditors (sample):** Group 3
**Site:** Hong Yuen Technology Co., Ltd. — 2nd floor, No. 88 Sec. 2, Gongyi Rd., Taichung
**Route walked:** Exterior loop + ground-floor lobby + 2nd-floor internal circulation + shared service corridor. 19 minutes.
**Date:** Tuesday, 21 minutes total including the reconciliation

---

## 1. Summary

Hong Yuen is a 22-person IT services reseller occupying the second floor of a small mixed-use building, with a ground-floor lobby shared with a printing shop and a noodle shop. The building's physical security is **the landlord's design**, not the tenant's choice, and that turned out to explain most of what we found. The single most important finding is that **the 2nd-floor fire stair door is propped open with a permanent wedge**, which makes the entire floor accessible to anyone who enters the ground-floor lobby and walks up an unmonitored staircase.

---

## 2. Findings

### 2.1 Perimeter

| Finding | Location | Rating | Evidence | Design / process? |
|---|---|---|---|---|
| No fence — the building is a street-front commercial property with no compound boundary | Whole site | M (n/a) | *No perimeter exists to assess; tenancy is street-front on a public footpath, so this is a building-type mismatch rather than a control failure.* | — |
| 2nd-floor windows are unbarred and openable to the street | North and east elevations | **W** | *Four casement windows on the office floor open inward and are not restricted; a passerby on the public footpath can reach the sill of the south one, which is 80 cm above pavement level.* | Design |
| Street-level approach to the building is well lit | Gongyi Rd frontage | **P** | *Continuous street lighting at roughly 8 m intervals along the frontage, and the two recessed entrance alcoves both have working fixtures.* | — |
| Ground-floor shopfronts are shuttered at close | Lobby, south side | **W** | *Both shopfront rolling shutters were down at 17:40, but the shop shutters are fitted with external padlocks and the key for the noodle shop's shutter is held by the building caretaker for "emergencies."* | Process |

### 2.2 Doors and access control

| Finding | Location | Rating | Evidence | Design / process? |
|---|---|---|---|---|
| **2nd-floor fire stair door is propped open with a rubber wedge** | East stair, 2nd-floor landing | **W** | *A yellow wedge is fitted to the bottom of the fire door; it is clearly used daily as the hinge has left a scuff arc on the paint and the wedge is scuffed on one face only.* | **Process** |
| 2nd-floor entry door from the stair has a functioning closer and a badge reader | 2nd-floor landing | **P** | *Hydraulic closer arms fully and latches on release; the reader showed no fault lamp and the badge controller logs the office's 22 staff as authorised.* | — |
| Front lobby has no access control at all | Ground-floor lobby | **M** | *The lobby is open to the street with no door, no gate, and no staff presence after 17:00; anyone can enter the building and use the open stair.* | Design |
| Roof access is a padlock with a key shared by three tenants | Roof hatch, west side | **W** | *Galvanised padlock on the roof hatch; the building caretaker confirmed one key circulates between the caretaker, the printing shop, and Hong Yuen's office manager.* | Process |
| Exterior doors' strike plates appear adequate | Lobby, north entrance | **P** | *Three 50 mm screws into the frame on each of the two exterior door strike plates; no visible pry damage or frame deformation.* | — |
| Emergency exit signage visible from the public footpath | North entrance | **W** | *An exit sign is fitted above the north entrance door, but it is the landlord's sign for the stair route, and the stair is not access-controlled at ground level, so following it leads to an unmonitored route to the office floor.* | Design |

### 2.3 Visitor management

| Finding | Location | Rating | Evidence | Design / process? |
|---|---|---|---|---|
| Visitors sign in on a **paper** sheet at the noodle shop's counter, not at an office reception | Ground-floor lobby | **W** | *A spiral-bound sign-in book sits on the noodle shop counter with no office branding, and the book for 14–20 October shows 31 entries with 6 arrival times but only 2 departure times.* | Process |
| No visitor badge is issued | Lobby | **M** | *No badge stock was visible anywhere on the ground floor; a visitor proceeding upstairs is unidentifiable from any distance.* | Design |
| Reception sightline to the stair is blocked by the noodle shop counter | Lobby → east stair | **W** | *The stair entrance is visible only through a 60 cm gap between the noodle shop's counter and the partition; the counter blocks the approach entirely for anyone waiting at the far side.* | Design |
| Hong Yuen's own visitors are handled at the 2nd-floor door | 2nd floor | **P** | *The office manager opens the 2nd-floor door for visitors and signs them in on a second sheet at the desk; the process exists, it just starts one floor too late.* | — |

### 2.4 CCTV coverage

**Judged against stated purpose, not count. The site has 6 cameras.**

| Finding | Location | Rating | Evidence | Design / process? |
|---|---|---|---|---|
| North entrance lobby covered | North entrance | **P** | *Camera 1 covers the north entrance door and lobby desk from 3 m, with the whole door in frame; facial detail is sufficient at the stored resolution.* | — |
| **No coverage of the east stair** | East stairwell | **M** | *Camera 2 covers the ground-floor stair entrance only; the stair itself has no camera on any landing, including the 2nd-floor landing door.* | Design |
| **No coverage of the roof hatch** | Roof | **M** | *No camera has a field of view that includes the roof hatch door on the west side; the hatch is only visible from a camera that covers the neighbouring rooftop.* | Design |
| Coverage of the office floor interior | 2nd floor | **W** | *Camera 4 covers the main office floor from the corner, but a 3.5 m section behind the meeting room is outside its field of view, and the 2nd-floor server cabinet sits in that section.* | Design |
| Recording is continuous with 30-day retention | Recorder, 2nd floor | **P** | *Recorder menu shows 24/7 continuous recording, 1080p, and a 30-day overwrite policy.* | — |
| DVR clock is synchronised | Recorder | **W** | *Recorder clock is 3 minutes 40 seconds ahead of both the office manager's phone and the badge controller, which is enough to break a badge/video correlation without anyone noticing.* | Process |
| Live view is not monitored | Recorder | **M** | *There is no live view station and no stated monitoring schedule; the office manager confirmed they check playback only after an incident is reported.* | Process |

### 2.5 Monitoring and logging

| Finding | Location | Rating | Evidence | Design / process? |
|---|---|---|---|---|
| Badge logs retained only **14 days** | 2nd-floor door controller | **W** | *Controller is configured to 14-day retention per the access vendor's default; 30 days is the landlord's standard for the building's other doors.* | Design |
| Individual credentials for all 22 staff, no shared badges | 2nd-floor door | **P** | *22 badges issued, one per named staff member, with a printed register matching the badge serial numbers; no badge is unassigned.* | — |
| Building's other doors produce logs nobody collects | Stair, roof | **M** | *The east stair and roof controllers log to the landlord's system and the landlord's quarterly invoice does not include badge reporting.* | Process |
| No documented physical incident response path | Whole site | **M** | *There is no document on the office wall or in the shared folder naming who to call for a forced door, a fire, or a flood; the office manager's answer was "call the landlord."* | Process |

### 2.6 Environmental and power resilience

| Finding | Location | Rating | Evidence | Design / process? |
|---|---|---|---|---|
| **No water sensor in the 2nd-floor comms cupboard** | 2nd-floor corridor | **M** | *The comms cupboard and the office UPS sit on the 2nd floor, and there is no water or moisture sensor; the landlord confirmed flood risk for the building is rated low but non-zero.* | Design |
| Server and network equipment are on the 2nd floor, above ground level | 2nd-floor cabinet | **P** | *No equipment is stored at or below external ground level anywhere in the office; the backup and network cabinet are both on the 2nd-floor slab.* | — |
| **No UPS or generator coverage for the server cabinet** | 2nd-floor cabinet | **W** | *A 600 VA UPS sits under the desk, but it is not connected to the server cabinet; the manager believes it "backs up the network" and could not say what it is actually connected to.* | Process |
| **Records storage is on the 2nd-floor cabinet and a single location** | 2nd floor | **W** | *Contracts and the tax file are in one metal cabinet; the server backup is a USB disk on a shelf in the same corridor as the server.* | Design |
| Roof appears sound and drained | Roof | **P** | *Membrane is continuous with no visible ponding or lifted flashing, and the two roof drains were clear at the time of the walk.* | — |
| External lighting has a 12 m dark stretch on the east side | East elevation | **W** | *Between the alley light at the south end and the stair light at the north end there is an unlit 12 m stretch at the base of the east stair, which is the ground-floor stair entrance.* | Design |

### 2.7 Patterns across the building

**Pattern 1 — The building's controls are the landlord's, and the tenant inherited them.** The badge readers, the door closers, the cameras, the roof lock, and the retention settings are all landlord-specified. Hong Yuen pays for them and cannot configure them. The single highest-value intervention is therefore a conversation with the landlord, not a purchase.

**Pattern 2 — Weak-by-process, not weak-by-design, on almost everything.** Of the 14 items rated Weak, 9 are human process failures — a wedged fire door, a stair light with a dead bulb that "nobody has reported," a DVR clock nobody has checked, a paper sign-in book nobody owns. The design is mostly adequate for a building this small. The operating discipline is not.

**Pattern 3 — Every critical control is on the ground floor and every monitored control is on the second.** The lobby, the stair, the roof hatch, and the loading of the noodle shop's key are all unmonitored. The badge reader and the second camera are both on the floor the tenant actually occupies. **The building is monitored where people already work, and unmonitored where people enter.** That single sentence is the finding that matters most, and it is a common pattern in any multi-tenant building.

---

## 3. Three prioritized recommendations

> **Recommendation 1**
> **Control to add or change:** Fit a self-closing, alarmed fire door on the 2nd-floor east stair landing, replacing the door currently held open with a rubber wedge. Alarm to a relay that notifies the office manager's phone and the landlord's caretaker.
> **Specific finding it fixes:** 2.2, the propped east stair fire door (W) and 2.1, the open front lobby (M). Together these make the entire office floor accessible from the street.
> **Likelihood (1–5) and why:** **4 — Likely.** The lobby is open to the street with no staff presence after 17:00, so the only barrier between the public footpath and the office floor is a door that is not closed. It is expected to be used at least once, probably more, and nobody would know.
> **Impact (1–5) and why:** **3 — Moderate.** A person on the 2nd floor could reach the server cabinet, the contracts cabinet, and the UPS, and remove a USB backup disk. Twenty-two staff, no physical assets of significant value, no hazardous material. A single-day disruption and a bounded data loss.
> **Priority + justification:** 4 × 3 = **12, High.** This is the highest-scoring item in the register and it is also the cheapest to fix — a self-closing door and a relay is a few thousand NT$, and the wedge removal is free today. It is high priority on likelihood alone.
> **Cost / effort:** Self-closing door plus door closer and relay, installed by the building contractor, plus a 20-minute briefing to the noodle shop and printing shop about why the door is not to be wedged. One working day, with the landlord's agreement.

> **Recommendation 2**
> **Control to add or change:** Install one camera covering the 2nd-floor east stair landing, and synchronise the DVR clock to NTP with the badge controller as the time source. Confirm the 600 VA UPS is actually connected to the server cabinet and its runtime.
> **Specific finding it fixes:** 2.4, the missing east stair coverage (M), the 3 min 40 s DVR clock offset (W), and 2.6, the UPS not connected to the cabinet (W).
> **Likelihood (1–5) and why:** **3 — Possible.** The missing stair camera means any of the events in Recommendation 1 would be unrecorded, and the clock offset means recorded video cannot be reliably correlated with badge logs. Neither is a compromise in itself; they remove the ability to establish one.
> **Impact (1–5) and why:** **2 — Minor.** The impact is on *investigability* rather than on the event itself. A correctly synchronised clock is free; the camera is a modest addition. The limitation is honest: this does not prevent anything, and on a register it would reduce neither likelihood nor impact — it is a detective control and it makes no change to the score.
> **Priority + justification:** 3 × 2 = **6, Medium.** Priority comes from cost and from the fact that it is a prerequisite for any future investigation, not from the score. The clock fix is free and should be done this week regardless of whether the camera is approved.
> **Cost / effort:** Clock synchronisation: zero, 15 minutes, Hong Yuen can do it. Stair camera: requires landlord agreement and a cable run; budget in the low tens of thousands NT$, one week of lead time.

> **Recommendation 3**
> **Control to add or change:** Move visitor sign-in to the 2nd-floor office door with a time-in and time-out sheet and a stock of clearly marked temporary visitor badges; back the sheet up photographically at end of day.
> **Specific finding it fixes:** 2.3, the paper sign-in book with 31 entries and 2 departure times, and the missing visitor badge (M).
> **Likelihood (1–5) and why:** **3 — Possible.** Visitors arrive at the lobby every day and are currently recorded without a departure, which makes the log impossible to use for anything. With the stair open, an unbadged visitor could also have been on the 2nd floor without appearing anywhere.
> **Impact (1–5) and why:** **2 — Minor.** No valuable physical assets, but a client-contract confidentiality exposure exists if a visitor is later alleged to have accessed a client area, and there would be no record to test it against.
> **Priority + justification:** 3 × 2 = **6, Medium.** Cheap, entirely within the tenant's control, and it does not depend on the landlord. This is the recommendation the tenant can act on unilaterally and immediately.
> **Cost / effort:** Badge stock, a second sign-in sheet, and a 5-minute daily habit. Effectively zero cost.

### Which "Present but Weak" items are weak by design, and which by process?

| Item | Design / process | Why | Cheaper to fix? |
|---|---|---|---|
| East stair fire door wedged | **Process** | The door and closer are adequate; the wedge is a daily habit | **Yes — free, today** |
| East-side 12 m dark stretch | **Process** | A working light fitting is present; the landlord says a bulb has been out "a while" and the report never reached them | **Yes — a bulb and a phone call** |
| DVR clock 3 min 40 s fast | **Process** | The recorder supports NTP; nobody configured it | **Yes — free, 15 minutes** |
| Roof padlock with a shared key | **Process** | The padlock is fine; the key circulation is the problem | Partly — cost NT$1,500 for a second lock the tenant alone holds |
| Server cabinet outside camera field of view | **Design** | The corner camera position cannot cover behind the meeting room | No — needs camera relocation or a second camera |
| Unbarred openable office windows | **Design** | The building is a commercial street-front property; window bars are not in the lease | No — landlord's capital decision |
| Paper sign-in book | **Process** | The book exists; the process around it (two timestamps, a badge) was never defined | **Yes — free, 5 minutes** |

### Name one control you rated that an attacker could defeat by entering through a different door.

**The 2nd-floor badge reader.** It is a genuine control — it logs 22 individual credentials with timestamps, and it latches properly. But it is a control on *one* door, and the building has three other ways onto the floor: the open ground-floor lobby and the east stair (unmonitored, and the fire door was wedged), the windows, and the roof hatch. **It is a real control on a door that is not the only door.** Decoration is what it becomes if the fire door stays wedged: Hong Yuen would have a complete-looking badge system and an open path to the floor beside it.

The honest statement is not "the badge reader is weak." It is "**the badge reader is strong, and it is guarding one of four approaches.**" The fix is not a better reader; it is closing the other three approaches.

---

## 4. Addendum A — Shared building network infrastructure risk

**Shared or tenant-adjacent infrastructure observed:**

| Location | Shared with | Access control on your side | Who controls it | Finding ref |
|---|---|---|---|---|
| Ground-floor lobby | Noodle shop, printing shop, Hong Yuen | **None** — open to the street | Landlord | 2.1, 2.2 |
| East stair | All three tenants + the noodle shop's upstairs seating | Fire door only (wedged) | Landlord | 2.2 |
| Roof hatch | All three tenants | Padlock, **one key shared three ways** | Landlord (key custody is shared) | 2.2 |
| Building comms cupboard, 2nd floor | Landlord's line to the carrier; also serves the printing shop's line | Landlord's lock; Hong Yuen has a key | Landlord | 2.6 |
| Noodle shop rolling shutter key | Noodle shop ↔ caretaker | Held by the building caretaker for "emergencies" | Landlord | 2.1 |

**The risk, stated specifically for this building:** the shared surfaces are the lobby, the stair, and the roof, and **all three of Hong Yuen's access-controlled assets sit behind the same unprotected lobby.** The landlord controls the doors and Hong Yuen controls the badge reader, which produces the worst version of the arrangement: the tenant pays for and relies on a control that is one floor above the actual boundary. There is also a lateral path — the printing shop operates on the 2nd floor and has a door to the shared corridor that we could not assess, so a person admitted to the printing shop is inside Hong Yuen's floor without having badged at Hong Yuen's door.

**Recommendation for this addendum:** ask the landlord, in writing, for three things at the next lease review: a self-closing alarmed fire door on the east stair, a second roof lock with the key held by the office manager only, and a written statement of which doors the landlord's card system actually covers. The third is free and would have taken us one phone call to learn on the day.

---

## 5. Addendum B — Typhoon and flood physical resilience

| Exposure | What we observed | Elevation / condition | Finding ref |
|---|---|---|---|
| Roof | Membrane continuous, two drains clear, no ponding, flashing seated | Roof deck, above all occupied space | 2.6 (P) |
| Roof hatch access | Padlock, key shared three ways | Roof level — a person on the roof in a typhoon is the exposure, not the building | 2.2 (W) |
| Ground floor / below grade | **None.** No plant, storage, or equipment at or below external grade | N/A | — |
| Loading / delivery point | No dedicated loading point; the noodle shop receives small deliveries at the street frontage in the open lobby | Street level, open | 2.1 (W) |
| Server / network / comms | 2nd-floor cabinet and 2nd-floor comms cupboard | 2nd-floor slab, above grade | 2.6 (W) |
| Records and archive | Metal cabinet, 2nd floor; USB backup disk on a corridor shelf | 2nd floor | 2.6 (W) |
| Power | Single building supply from the landlord; no generator; 600 VA UPS, not connected to the cabinet | N/A | 2.6 (W) |

**The risk, stated specifically for this building:** flood is **not** this building's problem — nothing is at or below external grade, and the 2nd-floor equipment is well clear. The real typhoon exposure is narrower and worth being precise about: it is (a) **the roof hatch**, which in a typhoon is both a water entry point and the one place a person on the roof would be at their least visible, and (b) **power**. A typhoon outage is typically hours; there is no generator, and the UPS does not currently reach the server cabinet, so an outage means an uncontrolled shutdown rather than a clean one. For a 22-person reseller, that is a data-integrity event and a Monday morning problem, not a catastrophic one. **The typhoon and the flood risks here are not the same risk, and treating them as one item is how the roof hatch stays unlocked.**

**Recommendation for this addendum:** two changes, both cheap. Re-key the roof hatch so the office manager holds the only key and a signed log records any roof access during a typhoon warning; and connect the existing 600 VA UPS to the server cabinet with a runtime test, so the shutdown is graceful. Neither requires capital spend, and the second is a 20-minute job.

---

## 6. What we could not assess

Be honest — a 20-minute walk with a clipboard gets you the outside and the corridor, not the controls.

| What we could not assess | Why | What would be needed |
|---|---|---|
| Lock quality and internal door hardware on the 2nd floor | Out of scope; this was an exterior and circulation walk | A separate internal walk with the building manager present |
| The printing shop's door to the shared 2nd-floor corridor | Not part of the leased area and not on the route | Landlord permission and a walk of the shared corridor |
| Whether the roof hatch padlock is currently engaged | We observed it closed from the ground-floor roof plant access; we did not go onto the roof | A roof walk, in two-person rule, with the caretaker |
| Actual badge log retention and contents | The controller menu was not accessible on a public walk | Access request to the landlord's system, or a test export |
| Whether the lobby is staffed after 17:00 on weekends | The walk was a weekday at 17:40 | A second walk at the weekend, or the staff rota |
| Fire code compliance and the legal status of the wedged door | Not an audit finding; it is a code and safety question | The building's fire safety plan and the local fire authority |

**One note on our own limits:** two of our group rated the DVR clock offset differently from the other two, because we were comparing against two different phones. We resolved it by reading the recorder menu against the badge controller's recorded event time, which agreed with the office manager's phone. It would have been easy to record a wrong number here, and the disagreement is a reminder to state *what you compared against* in every evidence sentence.

---

## 7. One question for the debrief

Prevention found the wedged door. **How would anyone have known it was wedged?**

A propped fire door is not an event, so nothing logs it. There is no sensor on it, the camera that covers the lobby points at the door and not at the landing where the wedge is, and the wedge has clearly been there long enough to wear the paint — which means the only reason it was found today is that a group with a clipboard walked past on a scheduled basis. **Detection here is an audit, not a control.** If the audit is annual, the door could be wedged for a year, and the log would show nothing at all. The cheapest fix for that specific problem is a door alarm on the fire door, which converts a control that only a human observer would ever catch into a control that reports itself.
