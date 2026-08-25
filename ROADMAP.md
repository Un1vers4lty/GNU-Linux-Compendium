# Phase 1: Incubation & Foundations  
In this phase, nothing has been set in stone. The goal is only to prove that everything does work.
  - v0.1 (Idea depth)
      - Focus: Expand the initial product vision into something that's viable as a product. Establishes the baseline data which will be used later on.
  - v0.2 (Internal CLI Prototype)
    - Focus: Pure Rust logic. A command-line script where you type natural language sentences or select parameters, and it parses the local YAML files to output the matched distro recommendations directly in the terminal.
  - v0.3 (Tauri Shell & Basic UI)
    - Focus: Tying the Rust parser to a blank Tauri window. Building a simple input box and a basic text list or grid so that when a user types a query, the recommended distros populate dynamically on screen.
  - v0.4 (Compendium Visualizer)
    - Focus: Bringing in the branding and UI design. Structuring the results into clean, readable cards with proper styling, basic filtering options, and clear layouts for the distro data.
  - v0.5 (Closed Alpha)
    - Focus: Me and the Devs will test every aspect of the app built and use that to build upon it before we go into the Extended Alpha
  - v0.6 (Extended Alpha)
    - Focus: We get a dozen or so close contributors (if possible to get that many) to beta test this app for what its built as at that moment than add patches for its flaws
  - v0.7 (Public Beta)
    - Focus: We publish it onto the GitHub as an open beta for all to join and help use it to give feedback and find stuff to patch or change before releasing the first stable release

# Phase 2: Runway & First Major Milestone (v1.0)
This is the phase in which the app becomes a publicly available stable release, as well as the runway for this milestone.
  - v0.8 (Website Creation & Infrastructure)
    - Focus: Setting up the public landing page, hosting the project documentation, establishing installation guides, and laying out the contribution guidelines on GitHub.
  - v0.9 (Final Freeze/Release Candidate)
    - Focus: Locking down the feature set entirely. No new features or distros are added here; the focus shifts completely to dogfooding, end-to-end testing across operating systems, and squashing remaining bugs.
  - v1.0 (General Availability)
    - Focus: The official public launch. Tagging the release, pushing out the first stable compiled binaries, publishing the official changelog, and sharing the project with the wider community to officially open the playground.

# Phase 3: Expanding Foundations
  - v1.1 (ISO Fetcher & Verification Pipeline)
    - Focus: 
  - v1.2 (USB Flash Wizard Prototype)
    - Focus: 
  - v1.3 
  - v1.4 


v1.1 (ISO Fetcher & Verification Pipeline)Focus: Building the backend logic and UI hooks to securely fetch official ISO checksums and direct download links for selected distros, ensuring users pull uncorrupted images.v1.2 (USB Flash Wizard Prototype)Focus: Integrating cross-platform USB burning utilities into the Tauri app shell so users can safely select a target thumb drive and flash their chosen distro directly from the app.v1.3 (ISO & Flash Wizard Public Rollout & Polish)Focus: Stabilizing the complete onboarding loop (choose distro $\rightarrow$ fetch ISO $\rightarrow$ flash USB) with community bug testing and edge-case handling across Windows, Mac, and Linux hosts.v1.4 (Compatibility Data Schema & ProtonDB Integration)Focus: Establishing the database schema and Rust parser rules for hardware, game (ProtonDB), and application compatibility tags, pulling and caching initial crowd-sourced datasets.v1.5 (Compatibility Checker UI & Tweaking Guides)Focus: Building the interactive compatibility views into the distro cards, displaying performance ratings, known bugs, and step-by-step community tweaking guides directly inside the app.v1.6 (Advanced Distro Library & Tag Filters)Focus: Expanding user library management, adding advanced UI filtering sliders, and supporting custom tag-point weighting configurations for finer-grained searches.v1.7 (Community Patching & Performance Audits)Focus: Processing user feedback from the v1.x feature drops, squashing Rust parsing bottlenecks, and optimizing local SQLite query speeds.v1.8 (Taxonomy & Contributor Expansion)Focus: Broadening the YAML database to support niche distributions, immutable/atomic base tags, and specialized hardware profiles via GitHub pull requests.v1.9 (Pre-Virtualization Architecture Prep)Focus: Internal code refactoring and structural groundwork to safely integrate host-native hypervisors (KVM, HVF, WHP) for the upcoming major milestone.


  v1.1 (ISO Fetcher Pipeline): Building the backend logic and UI hooks to securely fetch official ISO checksums and direct download links for selected distros.v1.2 (USB Flash Wizard Prototype): Integrating cross-platform USB burning utilities into the Tauri app shell so users can safely select a target thumb drive and flash their chosen distro.v1.3 (ISO & Flash Wizard Public Rollout): Stabilizing the complete onboarding loop (choose distro $\rightarrow$ fetch ISO $\rightarrow$ flash USB) with community testing across hosts.v1.4 (Compatibility Data Schema & ProtonDB Staging): Establishing the database schema and Rust parser rules for hardware, game (ProtonDB), and application compatibility tags.v1.5 (Compatibility Checker UI & Tweaking Guides): Building the interactive compatibility views into distro cards, displaying performance ratings and tweaking guides.v1.6 (Advanced Library & Tag Filtering Sliders): Expanding user library management with advanced UI filtering sliders and custom tag-point weighting configurations.v1.7 (Community Feedback Patch 1): Processing early post-v1.0 bug reports, squashing Rust parsing bottlenecks, and optimizing local SQLite query speeds.v1.8 (Expanded Taxonomy & Niche Distro YAMLs): Broadening the YAML database to support niche distributions, immutable/atomic base tags, and specialized hardware profiles.v1.9 (Performance & Memory Optimization Pass): Auditing Tauri webview rendering and Rust string-parsing lookups to keep resource usage microscopic.v1.10 (Mid-Phase Stability & Dependency Bump): Updating backend Rust crates, Tauri dependencies, and security patches to keep the local runtime modern and secure.v1.11 (Localization & Multi-Language Staging): Laying down the infrastructure for multilingual support and expanding internal markdown rendering capabilities.v1.12 (Advanced Comparison Views): Adding side-by-side distro comparison tools so users can contrast specs, tags, and antiodtes/catalysts directly.v1.13 (Community Pull Request Tooling): Refining the documentation and tooling for open-source contributors submitting distro updates via GitHub.v1.14 (Community Feedback Patch 2): Addressing edge cases found in the library management and compatibility modules.v1.15 (Hardware Peripheral Tagging Expansion): Deepening the compatibility database to include specific peripherals, graphic cards, and Wi-Fi chipsets.v1.16 (UI/UX Polish & Theme Customization): Introducing built-in theme toggles (dark/light/custom accents) to enhance the compendium's visualizer cards.v1.17 (Telemetry-Free Analytics & Local Logging): Optional, local-only error logging tools to help users export crash reports without leaking privacy.v1.18 (Extended Stress Testing): Large-scale testing of the SQLite database with hundreds of community-submitted distro YAML files loaded simultaneously.v1.19 (Documentation & Contributor Guide Overhaul): Finalizing all public-facing docs, contributing guidelines, and schema validation references.v1.20 (Pre-Virtualization Architecture Lock): Final code refactoring and structural groundwork to safely transition the project into Phase 4 and start virtualization development.

# Phase 4: The Next Evolution

# Phase 5: Expanding Horizons
