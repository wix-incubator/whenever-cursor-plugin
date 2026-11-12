# Whenever

Build and manage [Whenever](https://www.whenever.dev) automations from Cursor. Describe a recurring
task and the Cursor agent writes the workflow, checks it, and saves a draft in your Whenever
account. It can also turn workflows on, show their triggers, and read the results of past runs.
Manual and debug runs use your real connected accounts and count against your manual-run quota.

## Install

In Cursor, open **Customize**, find **Whenever** in the marketplace, and select **Add to Cursor**.

To try this repository before a marketplace release, copy it (not a symlink) into
`~/.cursor/plugins/local/whenever` and run **Developer: Reload Window**.

## Sign in

The plugin connects to `https://mcp.whenever.dev/`. In **Customize**, the Whenever MCP server shows
**Needs authentication**. Select it and sign in with your Whenever account. Cursor sees only your own workflows.
Provider connections and secrets are set up in Whenever in your browser; Cursor never sees their
values.

## Support

[Contact Wix Customer Care](https://support.wix.com/en/article/contacting-wix-customer-care-for-support).

## Privacy

[Whenever privacy policy](https://www.whenever.dev/privacy).
