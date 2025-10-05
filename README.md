# Linux Automation Script
**Goal:** Automate repetitive text input for work on Linux (SteamOS or Debian).  
**Tools:** Bash, `xdotool`

## What I Did
- Created a script to input common text patterns automatically
- Added optional prompts, delays, and logging

## Files
- `work-automation.sh` — main script
- `examples/` — sample command lines and usage notes (create this folder later)
- `images/` — screenshots of the script in action (create this folder later)

## How to Run
```bash
# Make executable the first time
chmod +x work-automation.sh

# Example run (focus the target window before running)
./work-automation.sh --phrase "Hello world" --repeat 5 --delay-ms 500
```

## What I Learned
- Shell scripting basics (flags, variables, loops)
- Automating GUI keystrokes safely with `xdotool`
- Linux permissions and making scripts executable

## Next Steps
- Add config file support
- Add `--dry-run` mode to preview actions
- Add per-app profiles (e.g., different delays per program)
