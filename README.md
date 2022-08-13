<p align="center">
  <h3 align="center">wakatime-sync</h3>
  <p align="center">Update Wakatime summary data to your gist every day</p>
</p>

---

## Setup

### Prep work

1. Create a new public GitHub Gist (https://gist.github.com/)
1. Create a token with the `gist` scope and copy it. (https://github.com/settings/tokens/new)
1. Create a WakaTime account (https://wakatime.com/signup)
1. In your account settings, copy the existing WakaTime API Key (https://wakatime.com/settings/account)

### Project setup

1. Fork this repo
2. Go to the repo **Settings > Secrets**
3. Add the following environment variables:
   - **GH_TOKEN:** The GitHub token generated above.
   - **WAKATIME_API_KEY:** The API key for your WakaTime account.
   - **GIST_ID:** The ID portion from your gist url: `https://gist.github.com/superman66/`**`75f3b2ec23c7f69594ca3d9e8b7ea81d`**..
4. Run workflow manually. Because workflows aren’t being run on forked repository.
