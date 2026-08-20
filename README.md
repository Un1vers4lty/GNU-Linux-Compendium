# GNU/Linux Compendium Summary
A local/on-device application designed to solve Linux fragmentation. Uses a deterministic algorithm with tags and natural language intent parsing to have a distro search engine with embedded VM's and compatibility checkers (for software, games, hardware, etc.) and a living wiki for up-to-date advice  

# Initial Product Vision
These are the features/abilities I thought the compendium should have when I first came up with the idea for this application. These features could have been abandoned or changed, with some being a bit hard to describe in a good way.
1. Each distro has identification tags (in groups like primary use case, vibe, difficulty, base/family, versatility, and release model) to help in the search & match feature
2 The search & match feature is an ability that allows a visitor to type what they use their device for/want from it, and it uses that to match what they want with the tags of the distros to make a top x distros list
3. The ability to have a distro library which you can add distros to, which allows you to click start on those distros and use them directly on your PC via a VM directly on your computer
4. A wiki-like support area which, unlike Reddit, has tags/notifs for if the post is outdated and how so, as well as a link and/or info on newer versions
5. A built-in compatibility checker which checks how well games, creativity/productivity apps, specific hardware (specifications, peripherals, and so on), etc. work on Linux and how to tweak it to work well 
6. Run by a core team to maintain it and make sure it doesn’t sink but open for community involvement 
7. It can help you with the steps before you install a distro (such as booting said distro onto a flash drive, helping you to fetch the ISO, etc.) after you’ve chosen it and gone through the verification steps to make sure you’ve chosen it, and also make it easy to switch between distros after you've installed one

# Target Audience (Who it’s for) 
This application has two main users which it's targeting which are newcomers and power users.
1. Linux Curious: People who are new to the Linux ecosystem and want to explore the ecosystem without any stakes or pressure
2. OS Refugees: People who are escaping their current OSes (Windows or Mac) because of windows telemetry, forced co-pilot, increasing mac prices, etc. that wants a stable and good alternative
3. Power User & Distro-Hopper: Enthusiasts who want a fast, structured way to explore niche distributions, check package availability, and test-drive environments without messy dual-boot setups

# The tech-stack used to make it and why?
1. Frontend & Shell:
  - What its made with: Tauri + lightweight web framework (Svelte or Vue)
  - Why it's made with that: Tauri uses the hosts system’s native webview instead of bundling a heavy browser engine such as Electron. This keeps the app bundle size microscopic (hopefully under a few megabytes) and memory consumption low, while web frameworks like Svelte or Vue ensures that the reactive user interface renders instantly.
2. Core Engine & Parser:
  - What its made with: Rust
  - Why it's made with that: Rust provides blazing-fast string and file parsing speeds with zero-cost abstractions. Because it compiles directly to the native machine code, it can execute complex intent-matching algorithms and natural language tag lookups locally in milliseconds without bogging down the user’s system.
3. Data Storage:
  - What its made with: YAML for source files + Embedded SQLite for Runtime
  - Why it's made with that: YAML files allow open-source contributors to easily submit distro updates via simple GitHub pull requests. At app launch, the Rust core ingests those files into a local embedded SQLite database, giving you lightning-fast relational querying for complex multi-tag filtering.
4. Virtualization:
  - What its made with: Native Virtualization Framework (KVM on Linux, HVF on Mac, and WHP on Windows)
  - Why it's made with that: It uses the native virtualization hypervisors rather than one monolithic hypervisor to make sure that its VM capabilities work natively on each OS with users interested in Linux
	
# Project Status & Current Milestone
1. Current Status: Planning & Initializing (v0.1 prep)
2. Immediate Next Step: 
  - Finishing the parsing system foundations
  - Establish the tag points system
  - Writing the YAML files for the initial distros used
  - Writing the RUST intent-matching CLI
  - Initializing in the Tauri Shell
