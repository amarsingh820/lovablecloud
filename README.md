# My CloudStream Repo

Ready-made CloudStream repo using prebuilt `.cs3` files originally from:
https://github.com/NivinCNC/CNCVerse-Cloud-Stream-Extension (branch: `builds`)

## How to use

1. Create a new public GitHub repo (e.g. `MyCloudRepo`).
2. Upload **all** files from this folder (keep filenames as-is — including `CNC Verse.cs3` with the space).
3. In `repo.json` and `plugins.json`, **find & replace**:
   - `USERNAME` → your GitHub username
   - `REPO`     → your repo name
   - `main`     → your default branch (only if not `main`)
4. Commit and push.
5. In CloudStream, add this repo URL:

   ```
   https://raw.githubusercontent.com/USERNAME/REPO/main/repo.json
   ```

   Or open this deep-link on your phone:

   ```
   cloudstreamrepo://raw.githubusercontent.com/USERNAME/REPO/main/repo.json
   ```

## Credits
All extensions © NivinCNC — original repo:
https://github.com/NivinCNC/CNCVerse-Cloud-Stream-Extension
Licensed under GPLv3.
