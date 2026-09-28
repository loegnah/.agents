## Common

- !important _Answer in Korean_
- No edits without an explicit edit or in-progress mention

## Code

- Replace comments with code naming. (Comments _only when absolutely necessary_, max 2 lines)
- Never roll back when there are changes that differ from previous changes. Assume the user can also modify the code, so assume it was modified as intended. However, ask if the changes conflict too much.

## Guideline Updates

- When you think the AGENTS.md in the project needs to be updated due to code changes or the like, ask the user.

<!-- graft:start -->
## Graft

Repo context graph in `graft/`. Check before grep/read.

- `graft ask "<query>" --source`: Find & understand code spans.
- `graft grep "<literal>"`: Exhaustive search across indexed symbols.
- `graft callers <symbol> [--direction out] [--depth N]`: Call hierarchy & blast radius.
- `graft skeleton <file>`: Signatures & line spans for a file.
- `graft map`: Repo orientation (clusters, hubs).
- `graft build`: Rebuild graph after large changes.
<!-- graft:end -->
