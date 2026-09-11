# Kelsi & Eddy — Luxury Wedding E‑Invite

A mobile-first, GitHub Pages-ready wedding invitation with a tactile burgundy envelope opening.

## Opening experience

- The sealed envelope is visible immediately on page load.
- The full envelope artwork is preloaded for a reliable first render.
- Tap the **K & E wax seal** to trigger a subtle press, followed by a slow 3D flap lift.
- The invitation card is revealed beneath the moving flap before the cover transitions away.
- The opening supports keyboard activation and `prefers-reduced-motion`.

## Brand

The BiT Affairs logo is fixed at the top-left and uses the supplied logo artwork with its black background removed.

## Files

```text
kelsi-eddy-github/
├── index.html
├── README.md
└── assets/
    ├── bit-affairs-logo.png
    ├── envelope-cover.webp
    ├── envelope-base-clean.webp
    └── envelope-flap-layer.webp
```

## GitHub Pages

1. Create or open a GitHub repository.
2. Upload the contents of this folder to the repository root.
3. In **Settings → Pages**, choose **Deploy from a branch**.
4. Select the branch containing `index.html` and the root folder.
5. Save and open the generated Pages URL.

## RSVP

The current RSVP form is front-end only: it shows an on-page confirmation and does not transmit submissions to a server. Connect it to your preferred form/backend service before treating RSVPs as production data.
