# RetroTINK-4K Decimation & Trim Tool

A calculator for finding the perfect decimation and negative trim settings on the RetroTINK-4K to achieve pixel-perfect downscaling before applying CRT or LCD effects.

**🔗 Tool Link:** [https://sjftech.github.io/RT4K-Decimation-Tool/](https://sjftech.github.io/RT4K-Decimation-Tool/)

## How to Use

### 🚀 Using a Preset
1. Select a game profile from the dropdown (e.g., **NSO**, **Capcom Fighting Collection**, or **MvC2**).
2. The optimal settings appear instantly.
3. Check the **Notes** for required console/game settings (e.g., 1080p vs 720p).

### 🛠️ Using the Custom Calculator
1. Set the dropdown to **Custom Calculator**.
2. Temporarily crop your image on the RetroTINK-4K to align with the active game content. 
   * *Tip:* Set **Scaling Mode** to **"Auto Fill Integer"** in the RetroTINK-4K menu to make manual alignment easier.
3. Reset crops, then enter your Input Signal, Active Area, and Target Resolution into the fields.
4. Hit **Calculate Settings**.

## Troubleshooting

### ⚠️ The image is off-center!
Consoles vary in horizontal phase. If your image is 1px off-center, swap the Left/Right or Top/Bottom negative trim values.

### ⚠️ Bad scale match?
Changing your console output (e.g., 1080p to 720p) alters the mathematical combinations available for decimation. If you can't get a tight match at 1080p, try switching to 720p and recalculating.