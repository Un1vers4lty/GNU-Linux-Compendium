# Project Roadmap 
Disclaimer: This roadmap is a rough patchwork for the order in which I would hope for it to go and is not final, but rather bound to be changed with time.

## Phase 1: Incubation & Foundations
In this phase, nothing has been set in stone. The goal is only to prove that everything does work.
  - v0.1 (Idea depth)
      - Focus: Expand the initial product vision into something that's viable as a product. Establishes the baseline data which will be used later on.
  - v0.2 (Internal CLI Prototype)
    - Focus: Pure Rust logic. A command-line script where you type natural language sentences or select parameters, and it parses the local YAML files to output the matched distro recommendations directly in the terminal.
  - v0.3 (Tauri Shell & Basic UI)
    - Focus: Tying the Rust parser to a blank Tauri window. Building a simple input box and a basic text list or grid so that when a user types a query, the recommended distros populate dynamically on screen.
  - v0.4 (Compendium Visualizer)
    - Focus: Bringing in the branding and UI design. Structuring the results into clean, readable cards with proper styling, basic filtering options, and clear layouts for the distro data.
  - v1.0 Alpha 
    - Focus: We start off this phase by having me and the devs run extensive tests on every feature on the app and where it works or where it need to be improved, after our test is finished, we hand it off to close contributors willing to participate in a closed beta to find bugs and give feedback. 
  - v1.0 Beta
    - Focus: We publish it onto the GitHub as an open beta for all to join and help use it to give feedback and find stuff to patch or change before releasing the first stable release
  - v1.0 Release Preparation:
    - Focus: Setting up the public landing page, hosting the project documentation, establishing installation guides, and laying out the contribution guidelines on GitHub while also  Locking down the feature set entirely. No new features or distros are added here; the focus shifts completely to dogfooding, end-to-end testing across operating systems, and squashing remaining bugs.
  - v1.0 (General Availability)
    - Focus: The official public launch. Tagging the release, pushing out the first stable compiled binaries, publishing the official changelog, and sharing the project with the wider community to officially open the playground.

## Phase 2: Expanding Foundation
  - v1.1 (ISO Director & Flash Wizard)
    - Focus: Integrating an ISO director to help users find ISO downloads, cryptographic verification, and a native Rust-powered USB flashing utility directly into the Tauri app interface.
      - Note: The ISO director provides direct links to the location of download for the ISO you want to download, and a guide on where to find it and paste it into the app to have it be flashed.
  - v1.2 (Compatibility & Comparison)
    - Focus: Establishing a compatibility sytem for hardware, peripheral, and apps (creativity & productivity apps, games, etc.) compatibility and guides for potential or verified tweaks you can do to make stuff work as welll as adding an advanced comparison views between distros which shows you their tags, images from what their UI looks like, all pre-installed apps and software, etc.
  - v1.3 (Library Enhancement)
    - Focus: Upgrading the local YAML metadata engine to ensure support for enhanced relational tagging (cross-referencing complex Catalysts and Antidotes) and introducing advanced multi-faceted direct filter combinations to match user preferences seemlessly as the library scales. 
  - v1.4 (Performance & Memory Audits)
    - Focus: Performing an app-wide (frontend UI, Rust backend parsing, the local assets, etc. to eliminate memory leaks, minimizing resource consumption during idle states, inefficient usage, ensuring snappy query response times, and potential or existing strain on CPU, Ram, etc. before we add the Virtual Machine Workloads.
  - v1.5 (Ecosystem Growth)
    - Focus: Expanding the community contribution tools by introducing features such as externalized plugin/extension support, and streamlined YAML schema submission tools (so users can submit new distros, updates, etc. without needing an entire codebase rework)
  - v1.6 (Wiki Support Foundations)
    - Focus: Integrating the in-app community wiki access with contextual troubleshooting articles and crowdsourced solutions mapped directly to specific distros or distro tag, hardware components, common app compatibility hurdles, etc.
  - v1.7 (Virtualization Prep & Integration)
    - Focus: Laying the foundations for the eventual additions of the VM's to the distro library feature, allowing for safe sandbox testing via lightweight VM integration (native hypervisors + efficient extra tools) so that users can test-drive/preview recommended distros/ISOs in a safe virtual environment via the app itself using their own computers parts rather than a computer somewhere else.
  - v2.0 Beta (Virtualization Update)
    - Focus: Introducing seemless VM provisioning directly inside of the app shell, upgrading teh rules engine for evaluating user hardware against an mostly (amap) offline database, integrating a crowdsourced advisor layer directly into recommendations and search flow, and upgrading the regex/keyword matching.
  - v2.0 Alpha 
    - Focus: Going through a period of just testimg all of the stuff done in the v2.0 Beta to find bugs, unpolished work, and other areas to improve upon.
  - v2.0 (Crucible)
    - Focus: The finalized update releasing the wiki in full, the VM's, and the compatibilty engine.

## Phase 3: Expanding Horizons
 - v2.1 ()
    - Focus: 
