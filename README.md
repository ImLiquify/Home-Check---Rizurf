# HomeCheck access list

`revoked.txt` lists computers whose HomeCheck access has been removed.

**Remove a device:** open `revoked.txt` → pencil icon → add the machine code on a new line → Commit.
The computer locks the next time HomeCheck opens (GitHub can take ~5 minutes to update).

**Restore access:** delete that line and commit.

Lines starting with `#` are notes and are ignored.
