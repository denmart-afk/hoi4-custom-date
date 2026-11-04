# Custom Start Date — HOI4 Mod

A mod for Hearts of Iron IV that adds a **"Custom Date"** scenario. It allows you to start the game on any date you choose (default is 01.09.1939).

## 🚀 How to use

1. **Choose a date**: Open [date_picker.html](https://denmart-afk.github.io/hoi4-custom-date/) in your browser, pick the date you want, and download the generated ZIP file.
2. **Install the mod**: Extract the downloaded archive to:
   `Documents\Paradox Interactive\Hearts of Iron IV\mod`
3. **Enable the mod**: In the game launcher, enable "Custom Start Date".
4. **In-game**: Select the "Custom Date: …" scenario and start playing.

---

## ✨ Features

- "Custom Date" scenario on the country selection screen (7 major powers).
- Game end date extended to 1960, so late starts don't end immediately.
- English and Russian localisation.

---

## ⚠️ Notes

- The world state uses the latest vanilla history snapshot before the chosen date. Events missing from the start data will not appear on their own.
- Start dates before 1936 may be unstable.
- Compatible with game version **1.19.\***.

---

## 🛠 For developers

If you want to change the date manually:
1. Open `common/bookmarks/custom_date.txt`.
2. Change the line `date = YYYY.M.D.12` (e.g., `1941.6.22.12`).
3. Optionally, update the scenario name in the `localisation` folder.
