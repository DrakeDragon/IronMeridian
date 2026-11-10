# Iron Meridian — Reading Comfort Edition

GitHub Pages release · November 10, 2026

The complete game is in `index.html`. No dependencies, external assets, accounts, build process, or backend are required.

## Publish on GitHub Pages

1. Extract this ZIP. GitHub does not unpack an uploaded ZIP automatically.
2. Create a repository or open your existing game repository.
3. Use **Add file → Upload files** to upload the extracted files to the repository root, then commit them. Ensure `index.html` is directly in the root, not in an extra folder.
4. Open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the branch containing your files (usually `main`), select **/(root)**, and click **Save**.
7. Wait for deployment. The Pages settings screen displays the published address. A project site generally uses `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.
8. Open that address on your phone and run the launch checklist below.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Only `index.html` is required to play. `.nojekyll` bypasses Jekyll processing. Documentation files are optional and are not loaded by the game.

## Update your existing game

Export your campaign from the old game's Settings first. Replace the existing `index.html` with this release, keeping the same site address. Commit the replacement and wait for deployment. Refresh the browser; clear its page cache if the old version remains.

Original-edition saves are supported. Saves use browser local storage under `iron-meridian-v1`; GitHub does not store or synchronize them. Use export/import to move progress between browsers or devices. Clearing browser data can erase progress. GitHub Pages projects on the same host share a storage origin and this game's save key.

## Reading Comfort release — 1.1.0

This release starts in **Large** text for both new campaigns and older saves without a text-size preference. Your campaign progress remains compatible.

- **Compact:** the previous edition's text sizes and dense layout.
- **Large:** 20px body/control text, with supporting text generally 18px.
- **Extra Large:** 24px body/control text, with supporting text generally 22px.

Choose a size using the **Text size** buttons above the menus or the selector in Settings. During battle, use **Aa Text** to cycle between sizes without leaving the route. The choice is saved in that browser and included in save exports.

Large modes increase text contrast and button sizes, wrap navigation, place mobile route cards in two columns, and stack information to avoid cramming larger text into small boxes. Boss names, strike warnings, and pause instructions use readable panels rather than shrinking with the battlefield camera. Browser zoom remains available.

If you update the game at its existing address, refresh after deployment. Export a campaign backup first. No progress reset or manual save conversion is needed.

## Controls and progression

- Choose a Campaign route and depart. Weapons fire automatically.
- Tap an enemy to make it the convoy's priority target.
- Repair restores surviving carriages. Barrage damages enemies. Shield reduces incoming damage. Abilities recharge in battle.
- Shield before red boss strike zones finish counting down.
- Use Train yard to add and upgrade carriages, refit weapons, and install modules.
- Research improves the whole convoy; Crew specialists add bonuses; Contracts pay additional rewards.
- Territory completions increase carriage capacity. Survival unlocks after the first territory.
- Replay cleared routes to earn salvage. All carriages are restored at stations.
- Finish with at least 70% hull for three stars, or at least 40% for two.
- Audio is disabled by default. Enable it in Settings if desired.
- Performance quality, particles, and camera shake can be adjusted in Settings.
- Switching away from the page pauses combat. Press Resume when you return.

## Launch checklist

- Confirm the public site loads and start route 1.
- Check scenery, weapon fire, enemy targeting, and all three abilities.
- Test pause/resume and returning to the station.
- Buy an upgrade, refresh, and confirm progress remains.
- Export a save and import that exported file.
- Check portrait and landscape on your intended phones.
- For slower devices, choose Performance quality and reduce effects.

## Package contents

- `index.html`: entire playable game, including graphics and save system.
- `.nojekyll`: static GitHub Pages publishing marker.
- `README.md`: deployment, controls, saves, and launch checklist.
- `RELEASE-NOTES.md`: features and verification limits.
- `SHA256SUMS.txt`: integrity checksums.

This package has not been published to a GitHub repository as part of this delivery.
