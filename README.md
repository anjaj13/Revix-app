
# Revix app
A Web3 platform that empowers YouTube creators to securely register their content as intellectual property (IP) on Story Protocol while enabling transparent revenue sharing with investors. By bridging YouTube’s Web2 ecosystem with blockchain technology, we solve two critical challenges:

1. Identity Verification: Prove true ownership of YouTube content to prevent fraudulent IP claims.

2. Revenue Accountability: Automatically track and distribute ad revenue and IP royalties to investors.

- For Creators: Protect your content, monetize remixes, and attract funding.
- For Investors: Back creators with confidence through verifiable revenue streams.
=======
## Key features
1. Social Login Identity Fusion
- Connect your YouTube channel to a Web3 wallet via Tomo’s MPC-based social login, eliminating seed phrases.
- Prove channel ownership cryptographically to prevent impersonation.

2. Easy IP Registration
- Register YouTube videos as IP on Story Protocol in seconds.
- Mint NFTs with embedded metadata (title, description, upload date).

3. Remix Intelligence Dashboard
- Track derivative works (remixes, forks) via Story Protocol’s Relationship Module.
- Visualize remix impact with heatmaps and revenue attribution.

4. Unified Revenue Proof
- Combine YouTube ad revenue (via YouTube API) + Story Protocol royalties into a single, on-chain report.
- Automate investor payouts via smart contracts.

## Run Revix app

This contains everything you need to run your app locally.
=======

**Prerequisites:**  Node.js


1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key (to generate mock data)
3. Run the app:
   `npm run dev`
