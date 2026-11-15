# hummingbird.eightybps.com

GitHub Pages site for Hummingbird, serving its atproto OAuth client metadata at
`https://hummingbird.eightybps.com/oauth-client-metadata.json`.

That URL is Hummingbird's OAuth client ID, so it must not move or redirect.
The source of truth is `Web/hummingbird/` in the Hummingbird repository, where
`OAuthClientMetadataTests` checks it against the app's configuration; copy
changes from there.
