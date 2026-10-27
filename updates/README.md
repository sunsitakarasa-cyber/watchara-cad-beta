# Signed Watchara CAD beta channel

The Windows beta installer and signed public feed are active. Installers and
matching source/notice assets are in GitHub Releases. The current release is
v0.6.0-beta.191, signed sequence191. This is a beta, not a1.0 certification.

Feed: https://raw.githubusercontent.com/sunsitakarasa-cyber/watchara-cad-beta/main/updates/beta.json

`public-key.json` and `update-policy.json` contain public verification data only.
No private key, password or account credential is distributed here. The client
verifies signed metadata and every downloaded file. Save and close normally
before activation; there is no forced restart or automatic model/report upload.

Publisher workflow: qualify an exact new payload/source set, assign a new
release identifier/sequence, sign locally, upload a draft and verify every asset,
publish the prerelease, fetch the final public URLs (draft URLs may change),
verify the anonymous installer/archive, then promote beta.json and verify the
public feed. Never overwrite published assets or reuse a signed sequence for
changed metadata. Prior versions and source assets remain available.

Updates download the complete package, preserve the old version and do not
roll back CAD models. Initial trust/bootstrap changes require a new trusted
installation. Ed25519 updates are separate from Windows Authenticode signing.
