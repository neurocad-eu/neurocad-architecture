# Trust Boundaries

## Boundary 1: External client to public API

Treat all external payloads as untrusted.

## Boundary 2: Public API to private execution systems

Translate external contract objects into internal execution-safe representations.

## Boundary 3: Artifact delivery back to clients

Expose only resolved public artifact references and approved metadata.
