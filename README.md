# aa-sandbox
Throwaway target for Agentic Automation's promote flow (dev → uat). Pushing to `uat` deploys `index.html` to GitHub Pages; the Pages URL is the health URL.

## Known pitfalls
- **"terminal đã đóng" (task failed):** the task terminal closed before the agent reported done (seen on #95–#97; #95 left an unpushed local commit). Not a repo bug. Push + `agentic pr open` right after committing, and record `agentic task evidence` / `agentic task done` as soon as the result exists, not at the end.
