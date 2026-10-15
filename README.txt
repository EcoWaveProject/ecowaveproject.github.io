ECOWAVE REDESIGN

1. Open this folder in VS Code.
2. Install the Live Server extension if you have not already.
3. Right-click index.html -> Open with Live Server.
4. The home page opens locally.
5. The Scanner buttons open the Teachable Machine model directly in a new tab.

Files:
- index.html: redesigned home page
- trashScanner.html: redesigned scanner information/launch page
- marketPlace.html: redesigned marketplace
- marketplaceUpload.html: redesigned upload page
- EcoRewards.html: redesigned rewards page
- XPStorage.html: redesigned XP dashboard
- Information.html: redesigned pollution information page
- styles.css: shared design system for all pages

The prototype uses localStorage for XP and uploaded listings, so data is stored only in the browser on that computer.


DARK MODE
A moon button (🌙) in the navigation switches the entire site to a charcoal/green dark theme. The preference is saved in localStorage, so it stays consistent across pages and browser sessions.
