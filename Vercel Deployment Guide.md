# [Vercel](https://vercel.com/) Deployment Guide
1. Create a Vercel project that imports from your GitHub fork.
2. Follow the steps that Vercel provides, making sure to:
	1. Set the root directory to `./`.
	2. Set the framework preset to `Other`.
	3. Generate a [GitHub PAT](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token).
	4. Add an environmental variable `GITHUB_TOKEN` with the value of the GitHub PAT you generated.
3. All done!