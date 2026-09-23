# Changelog

## Unreleased

- Allow new structured Claude and Codex chats in workspaces on paired Orca runtimes,
  using the owning host's capabilities, session creation and native model options.
- Preserve the launch runtime and pairing across retries and renderer reloads;
  isolate cancellation cleanup and session inventories by host.
- Plain SSH terminal launches and remote orchestration worker placement retain
  their existing transport behavior.

- Evaluate structured chat before the Orca Web terminal launch path, so paired web clients
  respect the selected chat mode; document the separate server opt-in.
