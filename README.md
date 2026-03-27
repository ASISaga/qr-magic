Implementation Checklist

​Repository Secrets: Go to your GitHub Repo -> Settings -> Secrets -> Actions. Add your PAT or App Token as YOUR_DISPATCH_TOKEN.

​Tokens JSON: Ensure tokens.json exists in the root with {"bblw": "available"}.

​Deployment: Once you push these, your drinkelder.com/bblw path will automatically serve the gatekeeper.

​The "Incorruptible" Result: The user scans, the browser "checks out" the token, GitHub Actions "erases" the link from the repo, and the user is redirected to a page that only opens for that specific browser tab.