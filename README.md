HomeInterceptor
A lightweight Android AccessibilityService for Fire OS that intercepts the Amazon launcher and automatically snaps back to your preferred custom launcher. Designed for minimal builds, no dependencies, and full compatibility with Firestick devices.

Overview
Fire OS aggressively forces the Amazon launcher to the foreground, even when users install custom launchers.
HomeInterceptor solves that by:
• 	Detecting when the Amazon launcher appears
• 	Instantly redirecting back to your chosen launcher
• 	Running silently as an AccessibilityService
• 	Requiring no root, no background services, and no extra permissions
This keeps your Firestick experience clean, consistent, and fully under your control.

Features
• 	Intercepts Amazon launcher packages:
• 	
• 	
• 	
• 	Tracks your last used launcher
• 	Automatically snaps back when Amazon tries to override it
• 	Zero ads, zero analytics, zero bloat
• 	Works on Fire OS 6, 7, and 8

Installation
1. Enable “Apps from Unknown Sources”
On your Firestick:

2. Install via Downloader
If you have a Downloader numeric code, enter it directly.
Otherwise, enter the direct APK URL from this repo’s Releases page.
Example:

Downloader will fetch and install the APK.

Enable the Accessibility Service
After installation:

Once enabled, the service will automatically keep your preferred launcher in the foreground.

How It Works
HomeInterceptor listens for:
• 	
• 	
When the Amazon launcher is detected, the service immediately launches your last known non‑Amazon launcher.
This creates a seamless “snap‑back” effect that prevents Amazon from overriding your setup.

Source Code
The entire project is included in this repository:
• 	Minimal Gradle structure
• 	No external libraries
• 	Clean Java implementation
• 	Fully reproducible build
You can compile it yourself using:


License
This project is open-source.
You may modify, fork, or redistribute it freely.

If you want, I can also generate:
• 	A polished project logo
• 	A “Releases” description
• 	A short tagline for Downloader
• 	A version history section
• 	A troubleshooting section
• 	A QR code for the APK download
Just tell me what you want to add.
