# molecule2url
**Share your molecules simply via URL.**

<table align="center">
  <tr>
    <td align="center" width="50%">
      <img src="asset/main.png" width="100%" />
      <br />
      <b>Main Viewer</b>
    </td>
    <td align="center" width="50%">
      <img src="asset/list.png" width="100%" />
      <br />
      <b>Molecule List</b>
    </td>
  </tr>
</table>

## Usage

### Adding Molecules
1. Place your `.xyz` files (single or multi-frame) into the `molecules` folder.
2. The **comment line** (the second line of the `.xyz` file) of the first frame will be automatically used as the description in the list view.
3. Commit and push your changes to GitHub.

## Deployment (How to host your own)
You can easily host your own instance of this viewer using GitHub Pages.

1. **Fork** this repository to your own GitHub account.
2. Go to your repository's **Settings**.
3. Navigate to **Pages** in the sidebar.
4. Under **Build and deployment**, set the **Source** to `Deploy from a branch`.
5. Select `main` (or `master`) as the branch and `/ (root)` as the folder.
6. Click **Save**.

Your viewer will be live at `https://<your-username>.github.io/molecule2url/` in a few minutes!
