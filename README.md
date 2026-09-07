# Kahol Labs Website
Static responsive website for Kahol Labs featuring ViewBoost.

## Firebase Hosting

The repository includes Firebase Hosting configuration for project `kahol-labs-website`.

### Automatic deployment

The GitHub Actions workflow deploys the site automatically on every push to `main`.

Before the first deployment, add this GitHub repository secret:

`FIREBASE_SERVICE_ACCOUNT_KAHOL_LABS_WEBSITE`

Its value must be the Firebase service-account JSON generated for the `kahol-labs-website` project. Do not commit the JSON key or share it in chat.

You can also trigger deployment manually from the repository's **Actions** tab.

Do not share Firebase passwords or private service-account keys in chat.
