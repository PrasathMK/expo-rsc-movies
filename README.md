Expo RSC is in preview and may have unexpected behavior that's hard to understand. Errors, HMR, and deployment will all be solid when it's moved out of beta.
Add environment variables to your .env.local file:

TMDB_READ_ACCESS_TOKEN -- Get this here https://www.themoviedb.org/settings/api
This secret will only be available in the server as it's not prefixed with EXPO_PUBLIC_.
