# Reading Comfort Edition — Release notes

Release date: November 10, 2026

## Fixed in version 1.1.1

- Replaced animation-loop rebuilding of battle buttons and status-panel controls with permanent elements.
- Ability labels and cooldowns update only when their content changes.
- Pause/resume uses a persistent label and immediately updates pause state, accessibility state, and ability availability.
- Text-size control stays mounted throughout combat.
- Paused frames no longer repeatedly rebuild controls or warning panels.
- Existing campaign progress and reading-size preferences are preserved.

Added regression checks for interactive-element stability, immediate action feedback, and paused interface update behavior. All passed alongside the existing gameplay and reading-comfort checks. Real-phone tap behavior still needs user confirmation.

## New in version 1.1.0 — Reading Comfort

- Large text is the default, including when upgrading an existing campaign.
- Compact, Large, and Extra Large choices are available above the menus and in Settings.
- In-battle Aa Text control changes size without abandoning or unpausing combat.
- Larger supporting text, stronger contrast, and larger touch targets.
- Responsive reflow for menus, route cards, status panels, dialogs, and battle controls.
- Boss names, incoming strikes, and pause instructions are shown in readable text panels.
- Canvas target labels, strike timers, and damage numbers compensate for camera scaling on small screens.
- Text preferences persist through refresh and campaign export/import.
- Existing saves, all 80 routes, and the expanded game's mechanics are preserved.

Additional checks passed for default-size migration, all eight menus in all three sizes, size-preference persistence without progress changes, invalid-setting fallback, and text controls during active and paused combat. Browser layout and physical-phone testing remain outstanding; no accessibility-standard certification is claimed.

## Retained expanded-edition features

- 80 routes across ten territories and eight mission categories.
- Ten named territory commanders with telegraphed strikes.
- Endless survival with escalating waves and a commander every five waves.
- Up to 12 weapon carriages plus the locomotive.
- Ten weapons and ten carriage upgrade marks.
- Five carriage configurations: standard, armor, rapid fire, targeting, and salvage.
- Six research disciplines with eight ranks each and boss-core hull reinforcement.
- Three crew specialists with five training ranks each.
- Seven permanent contracts and collectible rewards.
- 18 enemy types, campaign ratings, achievements, and personal records.
- Redesigned menus, detailed vehicles, moving terrain, rails, scenery, lighting, weather, turret animation, and weapon effects.
- Quality, particles, camera shake, and synthesized audio settings.
- Automatic browser saves with original-save migration and JSON export/import.
- One standalone HTML file with no runtime network requests or external dependencies.

## Verification

Automated checks passed for all eight menus, original-save migration, purchases and modules, contract payout protection, route locks, the first route, the final boss with maximum upgrades, survival progression and salvage banking, all ten region rendering paths, 18 enemy sprite types, portrait canvas rendering, and invalid-save rejection. Battlefield artwork was rendered directly and visually inspected.

## Known limits

- Full browser layout and physical-device touch testing remain outstanding; the local browser preview was unavailable during development.
- The full campaign needs extended balance testing at ordinary upgrade levels.
- Saves remain local to the browser; there is no cloud sync or shared leaderboard.
- Games on the same origin using this save key share campaign storage.
