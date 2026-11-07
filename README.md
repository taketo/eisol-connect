# eisol-connect

Return page for the HubSpot OAuth connection of EISOL's apps.

- It holds no secret, stores nothing and calls nothing by itself.
- It checks that the return address inside `state` belongs to the app (its Forge web trigger host), then forwards the one-time code there with a form POST.
- Address: https://taketo.github.io/eisol-connect/hubspot/
