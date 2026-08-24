# Catalysts (The Features) - The main abilities and core strengths of a distribution to explain what it’s built on, who it’s for, how it looks, and what it excels at doing.

	•	Base/Family - The ancestral roots and core package architecture of the operating system
	1	Debian
	1	Focuses heavily on free software and extreme stability. Uses .deb packages and the apt package manager.
	2	Arch
	1	A minimalist, bleeding-edge ecosystem built for users who want total control. Uses pacman and features the Arch User Repository (AUR). 
	3	Slackware
	1	The oldest active distro, built to mirror traditional Unix. It eschews modern automated dependencies in favor of simple tarball packages and manual control. 
	4	Gentoo
	1	A source-based powerhouse where everything is compiled locally from scratch using portage and USE flags for ultimate optimization. 
	5	RedHat
	1	The enterprise titan. It prioritizes corporate-grade security, long-term predictability, and commercial support, utilizing the .rpm format and dnf. 
	6	SUSE
	1	The pioneering European enterprise giant. Distinguished by its advanced system admin engine (YaST) and powerful snapshot integration. 
	7	Independent
	1	A distribution built entirely from scratch with its own unique codebase and package management, without forming a massive downstream family.

	•	Difficulty - The technical barrier to entry and expected Linux skill level.
	1	Noob-Friendly
	1	Works right out of the box with graphical installers, app stores, and zero mandatory command-line use.
	2	Comfortable
	1	Easy for day-to-day use, but requires a basic understanding of how to manage repositories or troubleshoot minor papercuts.
	3	Tinkerer
	1	Designed for users who enjoy modifying configuration files, custom environments, and tailoring the system to their specific workflow.
	4	DIY-Heavy
	1	Drops the user into a command line upon installation. Expects you to manually build your system partition-by-partition, package-by-package.
	5	Guru-Level
	1	Requires deep knowledge of operating system architecture, kernel parameters, compilation flags, and manual system building.

	•	Vibe - The distinct cultural personality and aesthetic feel of the distribution.
	1	Terminal-Dweller
	1	Text-only focus. Prioritizes keyboard shortcuts, efficiency, and a lifestyle spent inside a command prompt.
	2	Retro/Nostalgic
	1	Rejects modern visual fluff, maintaining traditional, late-90s/early-2000s desktop layouts.
	3	Modern & Sleek
	1	Polished, contemporary layouts with smooth animations, high-DPI scaling, and styling that mirrors modern macOS or Windows 11.
	4	Cozy/Comfort-First
	1	Feels familiar, safe, and warm. Intended to stay out of the user's way and provide a reassuring desktop experience.
	5	Tinkerer’s Canvas
	1	Starts out completely blank for the user to make every aspect of it to their tastes. 
	6	Unbreakable Fortress
	1	Built with a set it and forget it design and locks down core files to be untamperable by accidental user mistakes or bad updates. Gives up on customization for security. 

	•	Primary Use Cases - The specific jobs or workloads the operating system is tailored to handle.
	1	General Use
	1	Everyday tasks like web browsing, watching movies, document editing, and casual computing.
	2	Gaming
	1	Comes pre-packaged or highly optimized with graphics drivers, compatibility layers (Proton/Wine), and gaming store clients and/or console modes.
	3	Creative/Multimedia
	1	Tailored for video editing, audio production, and 3D modeling, often featuring low-latency kernels.
	4	Development
	1	Stacked with programming languages, compilers, containers, and development environments out of the box.
	5	Older Hardware
	1	Stripped of heavy resource requirements to breathe new life into computers built a decade or more ago.
	6	Privacy & Security
	1	Heavily sandboxed or routed through encrypted networks to prevent user tracking and data collection.
	7	Server
	1	A headless, lean system built to run continuously in the background hosting files, websites, or applications.
	8	Enterprise
	1	Designed for massive corporate deployments, offering predictable lifecycles, volume licensing management, and compliance tools.
	9	Cybersecurity
	1	Pre-loaded with tools specifically meant for penetration testing, network mapping, and vulnerability assessment.
	10	Academic
	1	Built with specialized software suites for mathematics, statistical analysis, engineering, and scientific research.

	•	Versatility - How flexible the distribution is when you try to change its intended purpose.
	1	Specialized
	1	Hard-coded for exactly one job (e.g., routing, firewalls, or pentesting); altering its purpose usually breaks it.
	2	Opinionated
	1	The developers have a strict vision of how the OS should look and work, making it difficult to swap out default tools or desktops.
	3	Balanced
	1	Offers a strong, functional defaults package but gives you standard paths to change whatever you want without fighting the OS.
	4	Modular
	1	Made of Lego bricks. The pieces are meant to be pulled apart, swapped out, and reconfigured effortlessly.
	5	Chameleonic
	1	Can effortlessly morph from a tiny IoT footprint into a massive desktop workstation, or into an enterprise cluster.

	•	Release Model - How new software updates, features, and security patches are delivered.
	1	Standard Point 
	1	Fixed OS upgrades released on a set schedule (e.g., every 6 months), introducing batch updates to software versions.
	2	LTS (Long-Term Support)
	1	Rock-solid releases supported with critical security updates for 3 to 10 years, freezing software versions to prevent breaking changes.
	3	Pure Rolling 
	1	No version numbers exist. Software updates are pushed directly to the user the moment the upstream developers release them.
	4	Stable/Semi-Rolling 
	1	Updates roll in continuously, but only after passing through extensive automated testing or staging phases to ensure core stability.
	5	Immutable/Atomic
	1	The core operating system files are read-only. Updates are applied all at once as a single image, making it impossible for a bad update to partially corrupt the system.

	•	Community Size - The size and availability of the user base for support, guides, and troubleshooting.
	1	Mainstream
	1	Enormous global footprint. Millions of active users, corporate backing, and endless troubleshooting guides found anywhere on the web.
	2	Highly Popular
	1	Massive dedicated community with crowded subreddits, active forums, and great documentation, though less generic mainstream recognition.
	3	Niche but Strong
	1	A small, intensely dedicated group of advanced users or enthusiasts who run highly specific setups and maintain excellent wikis.
	4	Boutique
	1	A tiny passionate passion-project team. Support is highly personalized but documentation may be sparse or slow to update.
	5	Barebones
	1	Extremely minimal. You are largely on your own, reading raw source code or mailing lists to solve problems.

	•	Desktop Environments - The graphical interfaces that manage your windows, menus, and workspaces.
	1	Gnome
	1	Modern, smartphone-inspired, gesture-heavy layout built on minimalism.
	2	KDE Plasma
	1	Highly customizable, familiar Windows-style layout with massive widget options.
	3	Cinnamon
	1	A traditional, slick desktop built for a smooth transition from classic operating systems.
	4	Mate
	1	A lightweight continuation of the classic, dual-panel desktop look of the 2000s.
	5	Budgie
	1	A clean, elegant desktop that bridges the gap between modern design and traditional layouts.
	6	Xfce
	1	Visually lightweight, incredibly fast, and runs perfectly on low-spec hardware.
	7	LxQt/LxDe
	1	Ultra-low resource interfaces designed purely for maximum speed and efficiency.
	8	Cosmic
	1	A highly modern, customizable, and efficient desktop environment built entirely in Rust.
	9	Pantheon
	1	An elegant, highly-styled, desktop emphasizing consistency and minimalist beauty.
	10	Deepin DE
	1	A visually stunning layout utilizing extensive blurs, transparency, and eye-candy animations.
	11	UKUI
	1	A tailored, professional desktop layout optimized for high efficiency and corporate use.
	12	Sway/i3
	1	Tiling window managers that automatically arrange your windows dynamically without overlap, controlled entirely via keyboard.
	13	Hyprland
	1	A modern tiling window manager focusing on blazing-fast fluid animations and high visual customization.

	•	Package Ecosystems & App Delivery - The primary method and architecture the system uses to fetch, sandbox, and run user applications
	1	Native Repo First
	1	Relies on the distribution's core, highly vetted system repositories managed directly by distro maintainers.
	2	Flatpak-First
	1	Prioritizes sandboxed, universal desktop apps decoupled from system dependencies, offering fine-grained permission control.
	3	Snap-Integrated
	1	Relies on Canonical’s containerized app store ecosystem with background auto-updating daemons.
	4	AUR-Native
	1	Direct access to the massive, community-driven Arch User Repository for virtually any piece of software imaginable.
	5	Source/Compilation
	1	Expects users to compile software locally from source code or build scripts for maximum platform optimization.
