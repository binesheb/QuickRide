# Updating QuickRide

QuickRide contains separate Backend and Frontend applications.

## Manual update

1. Pull the latest main commit.
2. Install Backend dependencies with a clean npm install in Backend/.
3. Install Frontend dependencies with a clean npm install in Frontend/.
4. Run the available lint/build checks for both applications.
5. Deploy Backend and Frontend independently according to their environment configuration.

## Dependency maintenance

Dependabot checks both npm projects weekly. Keep the committed lockfiles synchronized with accepted dependency updates.

## Automatic updates

No self-updater is enabled. Production deployments should be explicit and reversible so backend and frontend compatibility can be verified together.
