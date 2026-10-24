# BluePass Studio

A free, single-page passport-style photo maker for GitHub Pages.

## Publish on GitHub Pages
1. Create a public repository, for example `bluepass`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch **main** and folder **/(root)**, then Save.
6. Wait a minute and open `https://YOUR-USERNAME.github.io/bluepass/`.

## Notes
- No paid API key or backend is required.
- AI background removal uses `@imgly/background-removal` from jsDelivr and downloads its model/WASM assets from IMG.LY's CDN on first use.
- Your photo is processed locally in the browser; it is not uploaded to your own server.
- The first processing run can be slow and needs a stable internet connection.
- This project uses the AGPL-3.0-licensed `@imgly/background-removal` library. If you publish/modify/distribute this project, review and comply with that license and include appropriate attribution/license information.
- Enhancement in this starter is modest Canvas brightness/contrast/saturation adjustment, not a separate generative AI restoration model.
- The crop is 3:4 aspect ratio. It is not a guarantee of compliance with any specific country's passport photo rules.
