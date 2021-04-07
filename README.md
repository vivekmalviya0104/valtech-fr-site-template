# valtech-fr-site-template

## Build locally

you can build `valtech-fr-site-template-{version}.zip` locally.

1. Install Maven (to be able to use the packaging script).
1. Initialize the project with following command executed at the template root:

   ```bash
   npm install
   ```

1. To build the site template, run following command executed at the template root:

   ```bash
   npm run build
   ```

1. The site template ZIP file is now located below the template root: `valtech-fr-site-template-{version}.zip`.
1. Upload to an AEMaaCS site creation wizard. For installing on a local cloudready development instance use `npm run deploy`.
