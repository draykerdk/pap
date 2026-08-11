> One place to start a project, join someone else’s halfway through, and reuse what another project already solved.

**Where an intention becomes a project anyone can join.**

The environment where projects and applications are created, composed, validated, copied and evolved — each with its own scope and its own community, all speaking the same modular language, so that a project can reuse what another one already solved instead of rebuilding it. Bound to UID so participation is attributable, and to the method so a project stays enterable halfway through.

## The problem it addresses

A project nobody can enter halfway through depends on the people who started it. Without a shared place where projects are composed the same way, every initiative rebuilds its own coordination from nothing and none of that work transfers.

**How it works today.** Every initiative builds its own coordination from nothing, and none of that effort transfers to the next one.

**What would change.** Projects are composed from modules in a shared format, so entering one is reading it rather than being introduced to it.

**Why the rest depends on it.** Without it, the method has nowhere to be practised at scale and every project stays the size of its founders.

## Where this stands

Drayker has internal material on the platform that is not published yet; the closest public relative is DFMPProject, which describes how a project gets proposed but not where it then lives. A repository comes only after a public charter and one worked example.

Nothing described here is implemented. This repository exists so that the first
document about it has somewhere to live and someone can argue with it in public.

## Scope

- Projects and applications as composable modules
- Reuse and cloning across projects
- Participation attributed through UID
- Relation to DFMPProject and the project queues

## Not in scope

- A running platform, an account system or a hosting service.
- A replacement for the proposal path described in DFMPProject.

## Role in the system

Where projects and applications would be composed.

**Relations.** Uses DFMP and DFMPProject · attributed through UID · runs on Dk · links units to DAF.

**Depends on.** `dfmpproject` · `uid` · `dfmp`

## First functions

These are concrete and unclaimed. Any of them can be opened as an issue and delivered
by one person.

1. Write what the platform has to guarantee a project.
2. Describe one application worth composing first.
3. Argue where DFMPProject ends and the platform begins.

## How to contribute

Read [CONTRIBUTING.md](https://github.com/draykerdk/.github/blob/master/CONTRIBUTING.md)
and [GOVERNANCE.md](https://github.com/draykerdk/.github/blob/master/GOVERNANCE.md) in
the organization. In short: open or find an issue, say in the thread that you are taking
it, branch as `fn/<issue-number>-<short-name>`, and open a pull request against
`master`. There is no separate review branch.

Participation is voluntary and implies no compensation, employment or future claim.

## Sources of truth

- This repository, for what Projects & Applications is and is not.
- [`.drayker/component.yml`](.drayker/component.yml) — the machine-readable contract,
  validated on every pull request.
- [drayker.org/project/pap/](https://drayker.org/project/pap/) — the same record
  inside the portal, with the live board.
- [drayker.com/project/pap/](https://drayker.com/project/pap/) — the case for it,
  in plain terms.

---

Part of [Drayker](https://drayker.org) · content under CC BY 4.0
