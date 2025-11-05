# bcc-waves

**Stake your claim, defend your ground, and reap the rewards!**

> In BCC Waves, players must hold their ground against relentless waves of enemies. Success brings riches and glory, while failure forces a tactical retreat—or worse. Every site is meticulously tuned for danger, featuring timed assaults, focused spawn zones, and rewards that justify the risk.

---

## 🌟 Features

   Feature               | Description                                                                                     |
 ------------------------|-------------------------------------------------------------------------------------------------|
  **Mission System**     | Start missions at designated sites using in-world prompts. A blip and marker indicate the area. |
  **Wave Mechanics**     | Enemies spawn in waves around the site, attacking players within the radius.                    |
  **Loot Phase**         | Missions conclude with a loot phase, rewarding players with cash, gold, and items.              |
  **Remote Blip**        | Nearby players see a blip indicating active bandit waves.                                       |
  **Per-Site Tuning**    | Customize wave counts, spawn radius, and wave timeouts (in minutes) for each site.              |
  **Cooldowns**          | Prevents immediate mission restarts; optional job restrictions per site.                        |
  **Server Tracking**    | Ensures spawned NPCs are cleaned up when missions end or the owner disconnects.                 |
  **Multi-Language**     | Accessible to a global player base.                                                             |
  **Highly Configurable**| Tailor the experience to fit your server’s needs.                                               |

---

## 🔧 Dependencies

To run *BCC Waves*, ensure the following dependencies are installed **and started before** `bcc-waves` in your server configuration:

- **[vorp_core](https://github.com/VORPCORE/vorp-core-lua)**
- **[vorp_inventory](https://github.com/VORPCORE/vorp_inventory)**
- **[bcc-utils](https://github.com/BryceCanyonCounty/bcc-utils)**

---

## 📦 Installation

1. **Install Dependencies**

    Ensure all dependencies are installed and started **above** `bcc-waves` in your server configuration.

2. **Add the Resource**

    Place the bcc-waves folder in your server’s `resources` directory.
3. **Update Configuration**

    Add the following line to your `resources.cfg`:

    ```yml
    ensure bcc-waves
    ```

4. **Restart Your Server**

    Apply the changes by restarting your server.

---

## 🙌 Credits

- **Created with:** **[itskaaas](https://github.com/itskaaas)**

---

## 🔗 GitHub

For the latest updates or contributions, visit the official repository:

📌 **[bcc-waves](https://github.com/BryceCanyonCounty/bcc-waves)**

---

## 📢 Need Help?

- Reach out in the **[BCC Community](https://discord.gg/GuwS7Y7PA3)**
