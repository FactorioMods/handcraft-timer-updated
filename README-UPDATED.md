# handcraft-timer-updated

Update persistent storage, prototype lookup and rendering APIs; preserve player crafting timers across native ownership migration.

This derivative retains the upstream prototype, setting and remote-interface names. Factorio 2.1.24 or later is required. Native ownership migration replaces the original mod ID; do not enable both IDs together. Existing saved state is adopted as a whole. Conflicting existing destination state is rejected rather than silently overwritten.

Upstream authors, licenses and notices remain included. See the source history and changelog for the compatibility changes.
