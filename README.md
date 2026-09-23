# PetScript Veterinary Rx Form

A static, one-page PetScript Pharmacy veterinary prescription form. It requires no server or build step.

## Test locally

Open `index.html` in a browser, complete the form, and click **Download Completed PDF**. The finished one-page PDF downloads directly to the CSR's computer.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html` and the `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.

GitHub will provide the public URL after deployment completes.

## PDF download

The browser creates the PDF locally and downloads it with a filename such as `PetScript_RX_Bella_Smith_2026-09-23.pdf`. It is formatted as one 8.5 × 11-inch page. The page does not email, upload, or store the prescription.

## Important

This first version is static. It does not transmit or store form data. Treat completed prescription information as sensitive and only save or send generated PDFs through PetScript-approved secure systems.
