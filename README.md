# BAPP-Privacy-Policy

Static privacy policy site for BAPP. No dependencies or build step are required.

The homepage (`index.html`) is copied from
[BAPP's privacy policy](https://github.com/kerrytooley/BAPP/blob/main/public/privacy-policy.html).
Keep its policy text in sync with that source when the policy changes.

## Publish on GitHub Pages

After merging to `main`:

1. Open this repository's **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose the **main** branch and **/ (root)** folder, then **Save**.

Once GitHub Pages finishes deploying, the policy will be available at:
https://kerrytooley.github.io/BAPP-Privacy-Policy/

Use that URL in App Store Connect and Google Play Console.

## Preview locally

Open `index.html` directly in a browser, or serve the repository with Python:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000/. There is no existing automated test suite.
